# APUE

UNIX 环境高级编程阅读笔记以及代码仓库

## 配置学习环境
### 获取源代码
- 地址：[APUE主页](http://www.apuebook.com/)
- 下载之后解压得到 `apue.3e` 文件

### 添加文件到系统库
- 添加作者自定义的 `apue.h` 和 异常处理的 `error.c` 
- 在 `apue.h` 文件最后一行 `#end if` 之前添加 `#include "error.c"`
- 添加文件到系统库

```shell
$ cp ./include/apue.h /usr/local/include/
$ cp ./lib/error.c /usr/local/include/
```
### 编译
- 切换目录到 `apue.3e/intro`
- 使用 `cc hello.c` 编译 `hello.c`
- 如果没有报错就是正常的，反之可以参考[Mac下配置APUE(UNIX高级环境编程)学习环境](http://www.jianshu.com/p/62e81768052c)

## 项目导航

| Contents | Link | Date |
| --- | --- | --- |
| 01 UNIX System Overview |  |  |
| 02 UNIX Standardization and Implementations |  |  |
| 03 File I/0 |  |  |
| 4 |  |  |
| 5 |  |  |
| 6 |  |  |
| 7 |  |  |
| 8 |  |  |
| 9 |  |  |
| 10 |  |  |
| 11 |  |  |
| 12 |  |  |
| 13 |  |  |
| 14 |  |  |
| 15 |  |  |
| 16 |  |  |
| 17 |  |  |
| 18 |  |  |
| 19 |  |  |
| 20 |  |  |

