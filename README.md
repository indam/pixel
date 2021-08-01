# pixel
Pixel modem enable China Telecom LTE

ref: https://editio.me/2020/pixel-telecom/

"下载我上传到 GitHub 的文件，把手机连接到电脑，重启到 fastboot，使用以下命令刷入并重启即可

fastboot flash modem modem_patch.img --slot all
fastboot reboot
此后如果需要使用联通卡，需要新建接入点名称（APN）配置，APN 配置为 3gnet，其余不用修改，保存即可使用。"
