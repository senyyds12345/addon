# addon
- addon是一个便捷的mcaddon项目管理器,您可以用他创建/构建项目
# 安装
1.构建
```bash
dpkg-deb build addon
```
2.安装
```bash
dpkg -i addon.bash
```
# use
- 在使用前,必须初始化
```bash
addon init
```
- 该参数的会检查依赖是否下载,如果有一个依赖命令没有下载,会提示您输入y和n,输入y下载完,n则退出下载界面
- 您可以使用"--help"参数来了解如何使用
