# Qualcomm SM4450 / Parrot common LineageOS device tree

This is the shared device tree used by the unofficial Xiaomi `mist` bring-up.

**Source baseline:** [xiaomi-ravelin/android_device_xiaomi_sm4450-common](https://github.com/xiaomi-ravelin/android_device_xiaomi_sm4450-common/tree/lineage-24.0), commit `a476fff00d6149fc988f12f43b73cde1587c7b88`.

This repository is maintained under **nAa-mist**. The pinned upstream source snapshot will be imported here, preserving source paths and executable modes. Later changes must be committed to **this** repository, not to `mist-bringup`.

The upstream configuration contains `ravelin`-specific settings. Do not assume they are verified for `mist`. The device-specific overrides belong in [device_xiaomi_mist](https://github.com/nAa-mist/device_xiaomi_mist).

Stock research and original history: [mist-bringup](https://github.com/nAa-mist/mist-bringup). No proprietary binary blobs or Xiaomi firmware should be committed here.

**Not a boot-validated ROM.**
