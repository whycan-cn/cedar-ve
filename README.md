# CedarV Driver for Mainline Kernel v5.4

drivers/staging/media/sunxi/Kconfig
+
```
source "drivers/staging/media/sunxi/cedarx/Kconfig"
```

drivers/staging/media/sunxi/Makefile
+
```
obj-$(CONFIG_VIDEO_ENCODER_DECODER_SUNXI) += cedarx/
```
