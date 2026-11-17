# AIR6 telephony feed

The `air6` branch starts from `9bcb6d71db03377ff49ccb099be763add9a5b059`, the telephony feed revision recorded for the previous AIR6 build. No telephony package source changes were needed for the initial source migration. The AIR6 cellular IPC and dial-up components are maintained in `royzheng/immortalwrt-packages:air6`, not moved here merely because they control a modem.

This branch is selected by `src-git telephony https://github.com/royzheng/openwrt-telephony.git;air6`. Record its actual commit in each build's `feeds.buildinfo`.
