# BOT-OpenWRT

Using rclone to sync file from the complie vm to DAV store.

Need to create rclone file as a secrets.RCLONE_CONF

[TeraCLOUD]
type = webdav
url = https://seto.teracloud.jp/dav/

vendor = other

user = xxxxx

pass = xxxxxx

tips: pass is not only the password for the dav store

Other than Official img:

CONFIG_PACKAGE_luci-app-vlmcsd=y

CONFIG_PACKAGE_luci-app-ddns=y

CONFIG_PACKAGE_luci-app-upnp=y

CONFIG_PACKAGE_luci-ssl=y
