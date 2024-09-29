# Full firmware file

This repository was built using the OpenWRT hash `9c413397d99dbd66739ffb1f89d00a74dfbfe45a`
It is the OpenWRT repository required for building Ultari, a captive portal, with build settings pre-configured in the `.config` file.
You can customize the build using the `make menuconfig` command.

Before trying to build, `./scripts/feeds update -a` and `./scripts/feeds install -a` to install required feeds.


## License

OpenWrt is licensed under GPL-2.0
