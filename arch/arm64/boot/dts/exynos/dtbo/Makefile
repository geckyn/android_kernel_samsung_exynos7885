
ifeq ($(CONFIG_SOC_EXYNOS7885_ANDROID_VERSION_P),y)
#dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7885-universal7885_FHD_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7885-universal7885_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7905-universal7905_FHD_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7905-universal7905_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7884) += exynos7904-universal7904_FHD_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7884) += exynos7904-universal7904_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7884) += exynos7884-universal7884_FHD_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7884) += exynos7884-universal7884_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7884A) += exynos7884b-universal7884b_FHD_P_Treble.dtbo
#dtb-$(CONFIG_SOC_EXYNOS7884A) += exynos7884b-universal7884b_P_Treble.dtbo
dtb-y += exynos7885.dtb
endif

ifeq ($(CONFIG_SOC_EXYNOS7885_ANDROID_VERSION_P),y)
dtb-$(CONFIG_MACH_EXYNOS7885_A10_OPEN) := \
	exynos7884B-a10_eur_open_00.dtbo \
	exynos7884B-a10_eur_open_01.dtbo \
	exynos7884B-a10_kor_open_00.dtbo \
	exynos7884B-a10_kor_open_03.dtbo \
	exynos7884B-a10_kor_open_05.dtbo \
	exynos7884B-a10_sea_open_00.dtbo \
	exynos7884B-a10_swa_open_00.dtbo
endif

ifeq ($(CONFIG_SOC_EXYNOS7885_ANDROID_VERSION_Q_MR),y)
dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7885-universal7885_FHD_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7885-universal7885_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7905-universal7905_FHD_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7905-universal7905_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7884) += exynos7904-universal7904_FHD_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7884) += exynos7904-universal7904_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7884) += exynos7884-universal7884_FHD_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7884) += exynos7884-universal7884_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7884A) += exynos7884b-universal7884b_FHD_P_Treble.dtbo
dtb-$(CONFIG_SOC_EXYNOS7884A) += exynos7884b-universal7884b_P_Treble.dtbo
dtb-y += exynos7885.dtb
endif

ifeq ($(CONFIG_SOC_EXYNOS7885_ANDROID_VERSION_P),y)
always         := $(dtb-y) $(dtbo-y)
subdir-y       := $(dts-dirs)
clean-files    := *.dtb *.dtbo
endif

ifeq ($(CONFIG_SOC_EXYNOS7885_ANDROID_VERSION_Q_MR),y)
always         := $(dtb-y) $(dtbo-y)
subdir-y       := $(dts-dirs)
clean-files    := *.dtb *.dtbo
endif
