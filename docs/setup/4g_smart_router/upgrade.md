# UPGRADE

Click `UPGRADE` to check any available update and upgrade the firmware.

![firmware](https://static.gl-inet.com/docs/en/3/setup/4g_smart_router/upgrade/firmware.jpg)



---

## Online Upgrade

You can find the current firmware version here. If your router is connected to the Internet, it will check for the newer firmware version available for download.

![firmware](https://static.gl-inet.com/docs/en/3/setup/4g_smart_router/upgrade/firmware1.jpg)



*Note: It is suggested to uncheck **Keep setting**. If you keep the settings and encounter problems after the upgrade, please reset the router.*



---


## Upload Firmware

Click `Local Upgrade` to upload a firmware file to the router. Simply drag and drop your firmware file to the area indicated.

![firmware](https://static.gl-inet.com/docs/en/3/setup/4g_smart_router/upgrade/firmware2.jpg)



###Official OpenWrt/LEDE firmware

You can download the official firmware from our [website](http://download.gl-inet.com/firmware/). 

- GL-MiFi: [http://download.gl-inet.com/firmware/mifi/](http://download.gl-inet.com/firmware/mifi/)

Find the available firmwares from the folder according to your device model, and they are located in different sub-folders:

**v1**: Official GL.iNet OpenWrt/LEDE firmware.

**clean**: Clean versions of OpenWrt/LEDE firmware with Luci admin page only.

**testing**: Beta version of GL.iNet OpenWrt/LEDE firmware.



### Compile your own firmware

You can compile your own firmware and flash to the router. Please refer to [github.com/domino-team/openwrt-cc](https://github.com/domino-team/openwrt-cc).



### Third party firmware

You may also try other firmwares such as DDWRT.



*Note: If you uploaded an incompatible firmware thus bricked the router, please use Uboot to re-install the correct firmware.*



---

## Auto Upgrade

You can enable auto upgrade. The router will search for available update and upgrade automatically according to the time that you set.

![firmware](https://static.gl-inet.com/docs/en/3/setup/4g_smart_router/upgrade/firmware3.jpg)
