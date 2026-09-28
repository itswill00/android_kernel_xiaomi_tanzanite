# tanzanite bring-up (base emerald_r-u-oss)

Base: emerald_r-u-oss squashed, no history (depth=1 clone, .git removed to keep push small).
Pinned: Xiaomi_Kernel_OpenSource@b183d9cc + MTK_kernel_modules@30a11c8 (see BASE_EMERALD.txt).

Device: Redmi Note 14 4G tanzanite, MT6789, HyperOS OS2.0.207.0.VOGMIXM, GKI 5.10.226 (ab12786767).
Files: tanzanite_full.config (from /proc/config.gz), tanzanite.fragment deltas, DTB/DTBO notes + binaries.
Next: bump 5.10.209 -> 5.10.226, add tanzanite.dts overlay, fastboot boot test (no flash).
