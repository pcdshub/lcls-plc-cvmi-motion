IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.4.0
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0

PROJECT_NAME := lcls-plc-cvmi-motion
PROJECT_PATH := ../../lcls-plc-cvmi-motion/lcls-plc-cvmi-motion.tsproj
PLC := cvmi_motion

PYTMC_OPTS := 
PREFIX := PLC:CVMI:MOTION

include $(IOC_TOP)/iocBoot/templates/Makefile.base
