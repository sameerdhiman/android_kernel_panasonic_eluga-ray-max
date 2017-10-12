dts-dirs += apm
dts-dirs += arm
dts-dirs += cavium

ifeq ($(CONFIG_PROJECT_P7701),y)
dts-dirs += p7701
else
dts-dirs += qcom
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
