# OSS Dash

Open-source Android for the POCO X8 Pro Max (`dash`), based on LineageOS 24.0 with a GKI 6.6 kernel.

Sources live in [oss-dash](https://github.com/oss-dash) and [oss-dash-kernel](https://github.com/oss-dash-kernel) on GitHub, and [oss-dash](https://gitlab.com/oss-dash) on GitLab. Branch: `lineage-24.0`.

## Repository map

### Main — github.com/oss-dash

| Repository | Purpose |
| --- | --- |
| [android_local_manifests](https://github.com/oss-dash/android_local_manifests) | `repo` manifest wiring together every project below |
| [android_device_xiaomi_dash](https://github.com/oss-dash/android_device_xiaomi_dash) | Device tree for `dash` |
| [android_device_xiaomi_dash-kernel](https://github.com/oss-dash/android_device_xiaomi_dash-kernel) | Kernel device tree and configuration fragments |
| [android_device_xiaomi_dash-miuicamera](https://github.com/oss-dash/android_device_xiaomi_dash-miuicamera) | MIUI camera integration |
| [android_device_mediatek_sepolicy_vndr](https://github.com/oss-dash/android_device_mediatek_sepolicy_vndr) | MediaTek vendor SELinux policy |
| [android_hardware_mediatek](https://github.com/oss-dash/android_hardware_mediatek) | MediaTek HALs |
| [android_hardware_xiaomi](https://github.com/oss-dash/android_hardware_xiaomi) | Xiaomi HALs |
| [android_vendor_qcom_opensource_vibrator](https://github.com/oss-dash/android_vendor_qcom_opensource_vibrator) | Vibrator HAL replacement |
| [android_packages_apps_LunarisDolby](https://github.com/oss-dash/android_packages_apps_LunarisDolby) | Dolby audio application |
| [poco_dash_dump](https://github.com/oss-dash/poco_dash_dump) | Stock firmware dump, kept as a reference |

### Kernel — github.com/oss-dash-kernel

| Repository | Purpose |
| --- | --- |
| [android_kernel](https://github.com/oss-dash-kernel/android_kernel) | GKI 6.6 kernel (`kernel/platform/kernel-6.6/kernel-6.6`) |
| [android_kernel_device_modules](https://github.com/oss-dash-kernel/android_kernel_device_modules) | GKI device modules and Kleaf build entry points |
| [android_kernel_vendor_mediatek_kernel_modules](https://github.com/oss-dash-kernel/android_kernel_vendor_mediatek_kernel_modules) | MediaTek vendor kernel modules |
| [android_kernel_build_bazel_mgk_rules](https://github.com/oss-dash-kernel/android_kernel_build_bazel_mgk_rules) | Kleaf/MGK Bazel build rules |

### Vendor — gitlab.com/oss-dash

| Repository | Purpose |
| --- | --- |
| [proprietary_vendor_xiaomi_dash](https://gitlab.com/oss-dash/proprietary_vendor_xiaomi_dash) | Proprietary vendor blobs for `dash` |
| [proprietary_vendor_xiaomi_dash-miuicamera](https://gitlab.com/oss-dash/proprietary_vendor_xiaomi_dash-miuicamera) | Proprietary blobs for the MIUI camera port |
| [android_prebuilts_clang_host_linux-x86_clang-r510928](https://gitlab.com/oss-dash/android_prebuilts_clang_host_linux-x86_clang-r510928) | Prebuilt Clang toolchain |
