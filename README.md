# Qualcomm SM4450 / Parrot common LineageOS 24.0 device tree

**nAa-mist canonical source:** `device/xiaomi/sm4450-common`.

Imported **all 57 upstream source files**, including original executable modes,
from [xiaomi-ravelin/android_device_xiaomi_sm4450-common](https://github.com/xiaomi-ravelin/android_device_xiaomi_sm4450-common/tree/lineage-24.0)
at pinned source commit `a476fff00d6149fc988f12f43b73cde1587c7b88`.
The initial import was verified against the upstream Git blob SHAs and modes.

- **Device-specific changes:** [device_xiaomi_mist](https://github.com/nAa-mist/device_xiaomi_mist).
- **Common vendor extraction destination:** [vendor_xiaomi_sm4450-common](https://github.com/nAa-mist/vendor_xiaomi_sm4450-common).
- **Stock research only:** [mist-bringup](https://github.com/nAa-mist/mist-bringup).

Future shared hardware fixes must be committed **here**, not in the research archive.
The initial upstream tree includes `ravelin`-specific settings (e.g., audio SKU),
so it is *not* automatically compatible with all `mist` variants.

The binary proprietary vendor tree, final kernel integration, full ROM compilation,
and real-device boot test are **not completed**. No firmware binaries are committed.
