# OpenWrt-AutoBuild

基于OpenWrt-Actions-Lean+Lienol-自动化在线编译脚本  
源码和脚本来自  
[Lean](https://github.com/coolsnowwolf/lede)  丨  [ Lienol](https://github.com/Lienol/openwrt-actions )  丨  [ Lienol package](https://github.com/Lienol/openwrt-package )  丨  [P3TERX](https://github.com/P3TERX/Actions-OpenWrt)  丨  [esirplayground](https://github.com/esirplayground/AutoBuild-OpenWrt)  
复制 SSH 连接命令粘贴到终端内执行，或者复制链接在浏览器中打开使用网页终端。（网页终端可能会遇到黑屏的情况，按 Ctrl+C 即可）
cd openwrt && make menuconfig
完成后按Ctrl+D组合键或执行exit命令退出，后续编译工作将自动进行。

TIPS: 固件目录下有个config.seed文件，如果你需要再次编译可以使用它。
