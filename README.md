luci-app-dns-forwarder
===



编译说明
# Clone 项目
git clone https://github.com/smaller09/luci-app-dns-forwarder.git package/

# 选择要编译的包 LuCI -> 3. Applications
make menuconfig
# 开始编译
make package/luci-app-dns-forwarder/compile V=99
