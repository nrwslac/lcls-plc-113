IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.1

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 0

PROJECT_NAME := lcls_plc_113
PROJECT_PATH := ../../lcls-plc-113/lcls-plc-113.tsproj
PLC := tst_optics

PYTMC_OPTS := 
PREFIX := PLC:TST:OPTICS

include $(IOC_TOP)/iocBoot/templates/Makefile.base
