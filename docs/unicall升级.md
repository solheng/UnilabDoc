# 升级指南

## 安装包下载
将升级包update-unicall-20220627.zip放入unicall根目录下


### 安装包存放路径
![安装包升级存放路径.png](img/安装包升级存放路径.png)

以管理员权限运行update.exe, 执行结果显示Update Succeeded即为安装成功

![安装包升级成功.png](img/安装包升级成功.png)
## 可能遇到的问题
![unicall升级遇到的问题.png](img/unicall升级遇到的问题.png)

## Linux服务更新说明
放到应用程序根目录，然后在根目录启动 Terminal，执行 ./update 命令

如上图所示，执行过程中出现拒绝访问的报错信息，可关闭当前unicall相关程序或重启计算机后再次重新运行更新脚本

类库缺失

* 异常点检测算法工具库（pyod）
* 机器学习模型合并工具库combo
* xgboost
* seaborn
* minepy

cmd 通过pip安装对应类库
`pip install {package}`


