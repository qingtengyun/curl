## Unix系统Curl程序安装

由于Unix系统默认情况下，不存在可以支持上传或下载的工具，由此，需先安装自行编译的Curl程序，以满足Agent安装包的下载能力；

### 环境要求

Curl支持如下系统版本：

| 系统类型    | CPU架构       |
| ------- | ----------- |
| AIX     | Power PC 64 |
| Solaris | x86_64      |
|         | Sparc64     |

### 安装步骤

1. 下载对应操作系统版本的curl；
2. 将curl放到本机的/tmp路径下；
3. 将curl赋予执行权限（chmod 755 curl）；
4. 在/tmp路径下，以root用户权限执行命令即可；




