# Project Name
TARGET = ex_SDMMC

# Sources
CPP_SOURCES = SDMMC.cpp

# Library Locations
LIBDAISY_DIR = ../../libdaisy
DAISYSP_DIR = ../../DaisySP

# FatFs
FATFS_DIR = $(LIBDAISY_DIR)/Middlewares/Third_Party/FatFs/src
C_INCLUDES = -I$(FATFS_DIR)
C_SOURCES = \
	$(FATFS_DIR)/diskio.c \
	$(FATFS_DIR)/ff.c \
	$(FATFS_DIR)/ff_gen_drv.c \
	$(FATFS_DIR)/option/ccsbcs.c \

# Core location, and generic makefile.
SYSTEM_FILES_DIR = $(LIBDAISY_DIR)/core
include $(SYSTEM_FILES_DIR)/Makefile

