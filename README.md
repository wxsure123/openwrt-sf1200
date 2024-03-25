# 1806_SDK

## 需求无线/系统/芯片方向的高手加盟，欢迎联系 phoenix.shen@siflower.com.cn 必回复

切记，不要删除WiFi
SF1200的WiFi灯需要自行设置开启
SFT1200只有一个灯不需要设置

编译教程
git clone https://github.com/zheshifandian/openwrt-sf1200.git
cd openwrt-18.06
./scripts/feeds update -a && ./scripts/feeds install -a
make menuconfig
load .config.sf1200 或 load .config.sft1200
自行修改需要的app
make -j1 download && make -j1 V=99

https://www.right.com.cn/forum/thread-7348817-1-1.html
