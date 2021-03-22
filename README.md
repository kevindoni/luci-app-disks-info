# luci-app-disks-info
Information about connected disk devices (partitions, filesystems, SMART) for LuCI (OpenWrt webUI).

OpenWrt >= 19.07.

**Installation notes:**

    wget --no-check-certificate -O /tmp/luci-app-disks-info_0.3-4_all.ipk https://raw.githubusercontent.com/kevindoni/luci-app-disks-info/main/packages/19.07/luci-app-disks-info_0.3-4_all.ipk
    opkg install /tmp/luci-app-disks-info_0.3-4_all.ipk
    rm /tmp/luci-app-disks-info_0.3-4_all.ipk
    /etc/init.d/rpcd restart

**i18n-ru:**

    wget --no-check-certificate -O /tmp/luci-i18n-disks-info-ru_0.3-4_all.ipk https://raw.githubusercontent.com/kevindoni/luci-app-disks-info/main/packages/19.07/luci-i18n-disks-info-ru_0.3-4_all.ipk
    opkg install /tmp/luci-i18n-disks-info-ru_0.3-4_all.ipk
    rm /tmp/luci-i18n-disks-info-ru_0.3-4_all.ipk

**Screenshots:**

![](https://github.com/kevindoni/luci-app-disks-info/blob/main/screenshots/disk-info.png)
