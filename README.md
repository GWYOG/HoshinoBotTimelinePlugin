# 轴管理插件 for HoshinoBot

A [HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot) plugin which can input and search [PCR](http://priconne-redive.jp/) timeline by a customized database.


## 简介

基于 [HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot) 开发的轴管理插件，用户可在QQ群中通过机器人录入轴到后台数据库，之后可向机器人发送指令查看已经录入的所有轴。



## 功能介绍

详细功能和具体使用方法请在QQ群中发送“帮助pcr轴”查看，主要功能目前有：

- **录入轴/添加轴/上传轴**：通过机器人向后台数据库输入轴
- **查找轴/查看轴**：可以一次性查看所有输入的轴，也可以按不同boss显示对应的所有轴，或者按编号查看某一特定轴
- **更新轴/修改轴**：修改指定的轴，修改者只能是轴的上传者或者管理员
- **删除轴**：删除指定的轴，删除者只能是轴的上传者或者管理员
- **赞同轴**：对指定轴点赞或者点踩，管理员可以单次点任意数量的赞或踩以达到“置顶”指定轴的效果
- **查看轴库名**：查看此群当前使用的数据库名，此指令仅限管理员使用
- **切换轴库/修改轴库名**：切换使用的数据库，此指令仅限管理员使用。使用此指令可以实现不同群共享同一轴库的效果，同一工会的主会和分会可使用此功能


## 安装方式

1. clone或者下载此仓库的代码

2. 将timeline文件夹放入`hoshino/modules/`文件夹中

3. 打开`hoshino/config/`文件夹中的`__bot__.py`文件，在`MODULES_ON`中加入一行`'timeline',`