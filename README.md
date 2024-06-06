# proprietary_vendor_xiaomi_camera

Prebuilt MIUI Camera to include in custom ROM builds.

### Supported devices
* Xiaomi 13 (fuxi)
* Xiaomi 13 Pro (nuwa)
* Xiaomi 13 Ultra (ishtar)
* Poco F6 Pro / Redmi K70 (vermeer)

### How to use?

1. Clone this repo to `vendor/xiaomi/camera`

2. Inherit it from `device.mk` in device tree:

```
# Camera
$(call inherit-product-if-exists, vendor/xiaomi/camera/miuicamera.mk)
```
