# OpenWRT-CI
Github action compile  OpenWRT

LEDE源码：
https://github.com/coolsnowwolf/lede

IMMORTALWRT源码：
https://github.com/immortalwrt/immortalwrt

# 固件简要说明：

固件每周六早上0点自动编译。

固件信息里的时间为编译开始的时间，方便核对上游源码提交时间。

X64系列，包含X64、X86

# 目录简要说明：

Depends.txt——环境依赖列表

workflows——自定义CI配置

Scripts——自定义脚本

Config——自定义配置

  -- General.txt 为通用配置文件，用于设定各平台都用得到的插件。

  -- X64.txt 为各平台主要配置文件，用于设定机型及额外插件。
