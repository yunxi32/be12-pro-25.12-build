# BE12 Pro 25.12 firmware build

Builds Tenda BE12 Pro firmware from chasey-dev/immortalwrt-mt798x-rebase,
branch 25.12-dev-wifi7, pinned to commit 4ab9dab8f909e9b3499e35d89b32d14ee1da80c5.
Uses the upstream MT7987/MT7992 low-memory preset and pinned package feeds.

This repository contains generic build configuration only. Router backups,
credentials, WAN settings, Wi-Fi settings and VPN identities are kept locally.

Firmware artifacts include sysupgrade and recovery images, checksums, package
manifests, effective build configuration, revisions and partition size checks.
Build success alone does not guarantee runtime compatibility. Validate the image
on the device before flashing, and keep a verified backup and recovery plan.
