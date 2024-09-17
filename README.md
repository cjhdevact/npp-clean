# Notepad++ Clean

## 关于本项目

本项目Fork自Notepad++官方源代码，但修改了部分代码，去除了Notepad++作者的极端言论。

任何开源软件都不应当与政治立场挂钩，本项目的目的就是去政治化。

## 功能

与Notepad++官方一致。

## 下载

转到[发布页](https://github.com/cjhdevact/npp-clean/releases)下载程序或源代码。

## 编译

这里只讲述GCC编译方式。
其它方式以及附加参数参阅官方文档：[BUILD.md](BUILD.md)

1. 安装[MinGW-w64](https://www.mingw-w64.org/)
2. 将MinGW-w64目录里的`bin`文件夹添加到Path里面
3. 打开`cmd.exe`
4. 转到源代码目录的`\PowerEditor\gcc`目录。
5. 输入`mingw32-make`命令编译。
6. 编译时长视电脑配置而定，建议使用8G内存编译，Win7 x64 4GB内存大约编译了半小时。
