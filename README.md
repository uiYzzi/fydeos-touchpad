# fydeos-touchpad
解决fydeos触摸板无法轻触
### 哪些情况下可用？
在命令行输入**evtest**查看系统有没有识别到你的触控板并且给出反馈数据，若有，则可试一试这个方法。
### 如何使用
下载本项目并放置在fydeos的下载目录，在命令行使用sudo cp命令替换系统的/etc/gesture文件夹
