# 让RPi显示中文

第一步 安装中文字库：

    sudo apt-get install xfonts-wqy


第二步 安装拼音输入法：
    sudo apt-get install scim-pinyin
	

第三步 设置中文
    sudo raspi-config

选择第5项目（使用空格键勾选，Enter键确认），Default locale for the system environment，然后设置 zh_CN.UTF-8


第四步 重启
    sudo reboot
