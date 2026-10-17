# Evolution X 16 Build Notes — Motorola Edge 40 Neo

These notes document the kernel repository used for an unofficial Evolution X Android 16 build for the Motorola Edge 40 Neo (`manaus`).

## Build Information

- **Device:** Motorola Edge 40 Neo
- **Codename:** `manaus`
- **SoC:** MediaTek MT6879
- **ROM:** Evolution X 16.0
- **Android version:** Android 16
- **Build type:** Unofficial
- **Build date:** 17 October 2026

## Kernel Source

Repository: https://github.com/muzakkir87/android_kernel_motorola_mt6879

Branch: `seventeen`

The kernel source was included in the pinned source revisions used for the successful ROM compilation.

## Related Device Repositories

- Device tree: https://github.com/muzakkir87/android_device_motorola_manaus
- Common device tree: https://github.com/muzakkir87/android_device_motorola_mt6879-common
- Device vendor: https://github.com/muzakkir87/proprietary_vendor_motorola_manaus
- Common vendor: https://github.com/muzakkir87/proprietary_vendor_motorola_mt6879-common

## Build Result

The Evolution X ROM compilation completed successfully using:

```bash
m evolution -j16
```

Successful compilation does not guarantee successful booting or complete hardware functionality on a physical device.

## Credits and Licensing

Credit the original kernel developers and contributors. Preserve existing documentation, license files, copyright notices, and applicable source license requirements.

This is an unofficial community build and is not an official Motorola or Evolution X release.
