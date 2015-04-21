# android_hardware_qcom_display-caf-new
android_hardware_qcom_display-caf-new for qcom msm8974 those stock kernle do not support PipeType and overlay_list(基于msm8974平台，给那些不升级官方内核想适配CM11，但内核又不支持PipeType 和 overlay_list的童鞋准备的)

other:
--------
```
frameworks/native/services/surfaceflinger/Android.mk

ifeq ($(TARGET_QCOM_DISPLAY_VARIANT),caf-new)
#    LOCAL_CFLAGS += -DQCOM_B_FAMILY
endif
```
