################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := 

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir.mk
-include objects.mk

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: ../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter.out

# Tool invocations
../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter.out: 
	@echo 'Building target: $@'
	@echo 'Invoking: ARM Linker'
	"../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter.out" "dmtimerCounter.map" "/lib" "/include"  "../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter.out"
	@echo 'Finished building target: $@'
	@echo ' '
	$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(OBJS) ../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter.out
	-@echo ' '

post-build:
	-"/utils/tiobj2bin/tiobj2bin.bat"  "../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter.out"  "../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter.bin"  "/bin/armofd.exe"  "/bin/armhex.exe"  "/utils/tiobj2bin/mkhex4bin.exe" & "../../../../../../../tools/ti_image/tiimage.exe" "0x80000000" "NONE" "../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter.bin" "../../../../../../../binary/armv7a/cgt_ccs/am335x/evmAM335x/dmtimer/Debug/dmtimerCounter_ti.bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: post-build

-include ../makefile.targets
