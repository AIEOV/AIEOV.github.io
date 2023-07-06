服务器asf挂卡

不可用root用户执行

    mkdir asf
    cd asf
打开 https://github.com/JustArchiNET/ArchiSteamFarm/releases 

    wget 最新版本
安装解压软件

    sudo apt install unzip
 解压

    unzip ASF-linux-x64.zip
配置文件生成 https://justarchinet.github.io/ASF-WebConfigGenerator/#/

创建屏幕

    screen -S asf
运行

    ./ArchiSteamFarm


