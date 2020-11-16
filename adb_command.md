# adb常用命令

## 查看应用包名

- 查看当前打开的应用包名

> adb shell dumpsys window | grep mCurrentFocus

- 列出安装的应用包名

> adb shell pm list package 列出所有应用的包名(-s:列出系统应用，-3:列出第三方应用，-f:列出应用包名及对应的apk名及存放位置，-i:列出应用包名及其安装来源)