- [z-lib-mirror](#z-lib-mirror)
  * [建设目标](#----)
    + [前端界面](#----)
    + [后端](#--)
      - [基于BT协议的后端](#--bt-----)
      - [基于本地存储的后端](#---------)
      - [将请求转发至telegram bot/bookszlibb74ugqojhzhg2a63w5i2atv5bqarulgczawnbmsb6s6qead.onion](#------telegram-bot-bookszlibb74ugqojhzhg2a63w5i2atv5bqarulgczawnbmsb6s6qeadonion)
  * [加入我们](#----)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# z-lib-mirror
希望建成某校校内的z-lib镜像站
## 建设目标
### 前端界面
前端应当以网页的形式, 部署在某台服务器上, 并额外具有以下要求
1. 登入界面, 需要有注册和登陆的功能, 并且应当仅限校内人员使用某校邮箱登入
2. 查询界面, 支持书名的搜索
3. 列表界面, 列出查询的所有结果, 并提供下载功能

### 后端
后端的架构尚未决定, 目前有以下三种方案, 其实这三种方案可以按照资源热门的程度同时使用
#### 基于BT协议的后端
服务器在通过数据库将书名转换为对应的id后, 从做种的若干分布式站点中下载对应的文件, 重命名后提交给前端.

注: 如果采取此方案, 可以引入一些方法实时监测做种状况, 在首页鼓励参与者对缺少冗余的种子进行做种

此方案具有如下优点:
1. 分布式, 提高了安全性
2. 可以众筹存储空间

#### 基于本地存储的后端
此方案具有如下优点:
1. 服务较为稳定
2. 

#### 将请求转发至其他网站
z-lib提供了telegram bot的书籍查询和下载接口, 并且仍可通过洋葱浏览器[访问](bookszlibb74ugqojhzhg2a63w5i2atv5bqarulgczawnbmsb6s6qead.onion)
不失为一种方法吧...
## 加入我们
QQ群: 209582754
