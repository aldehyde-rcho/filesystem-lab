# filesystem-lab

### 操作系统实验

最初始版本来源：https://blog.csdn.net/u011915301/article/details/45031213

315荣誉出品（？） 2022

#### 编译并运行：

首先在目录下创建两个空文件"buffer.disk"和"disk.disk"

``` shell
$ gcc filesystem.c -o filesystem.o
$ ./filesystem.o
# fmt
```

##### 操作列表

| 编号 | 命令 | 作用 |
| --- | ------ | --------------- |
| 0 | fmt | 格式化磁盘 |
| 1 | quit | 退出文件系统 |
| 2 | mkdir | 创建文件夹 |
| 3 | rmdir | 移除文件夹 |
| 4 | cd | 进入目录 |
| 5 | ls | 列出当前目录下文件和文件夹 |
| 6 | mk | 创建文件 |
| 7 | rm | 移除文件 |
| 8 | vim | 调取vim操作文件 |
| 9 | pr | 列出磁盘当前信息 |


wu branch下面的是最后提交的版本。太懒了懒得合并了。

HDU 操作系统 操作系统课程设计 实践 文件系统

感谢潘老师和其他帮助完成这一作业的朋友们
