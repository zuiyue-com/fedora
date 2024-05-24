# fedora

- 禁用 GPG CHECK /etc/ostree/remotes.d/fedora.conf

# 鼠标禁用

- 禁用电源管理对触摸板的控制：在/etc/UPower/UPower.conf文件中，找到IgnoreLid=true这一行，如果没有这一行，就添加它。这将告诉电源管理在盖子关闭时忽略触摸板。

# 查找触摸板的设备ID
xinput list

# 启用触摸板
xinput enable <device-id>
