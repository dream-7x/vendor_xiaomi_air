# Vendor Tree for Redmi 13C/13R 5G | POCO M6 5G (air)
## Overview
This repository contains the **proprietary vendor blobs** for the **Xiaomi Redmi 13C/13R 5G | POCO M6 5G**, codenamed **air**, extracted from **Xiaomi HyperOS OS2.0.204.0** (Android 15 base).

These files are required for building **AOSP-based custom ROMs** for this device.

---

## Device Information

| Basic | Details |
|-----|--------|
| Device | Xiaomi Redmi/Poco 13C/13R/M6 5G |
| Codename | air |
| SoC | MediaTek MT6835 Dimensity 6100+ (6 nm) |
| CPU | Octa-core (2x2.2 GHz Cortex-A76 & 6x2.0 GHz Cortex-A55) |
| GPU | Mali-G57 MC2 |
| Launch Android | Android 13 |
| Vendor Source | HyperOS 2.0.204.0 |

---

## Source Firmware

- **ROM:** Xiaomi HyperOS
- **Version:** OS2.0.204.0
- **Android Version:** 15
- **Region:** Global / India
- **Extraction Method:**  
  - `super.img` mount  
  - `vendor`, `odm`, `vendor_dlkm`, `system_ext` partitions  

---

## Directory Structure

```text
vendor_xiaomi_air/
├── proprietary/
│   ├── vendor/
│   ├── odm/
│   ├── vendor_dlkm/
│   └── system_ext/
├── radio/
│   └── ***.img
├── Android.bp
├── Android.mk
├── BoardConfigVendor.mk
├── air-vendor.mk
└── README.md