ifeq ($(CONFIG_LZ4_SPEEDUP),y)
ifeq ($(strip $(cfi_check)),true)
ccflags-y += -O3
else
ccflags-y += -O3
endif
else
ccflags-y += -O3
endif

obj-$(CONFIG_LZ4_DECOMPRESS) += lz4_decompress.o
