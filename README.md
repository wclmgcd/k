# k
openwrt一键编译脚本（非原创，原作者ITdesk）


使用方法

1.先将脚本下载到ubuntu的根目录，其他目录会报错！

下载命令: git clone https://我的连接

2.ssh连接 执行脚本 sh kenzo


测试系统：ubuntu18.4 

             需要全局梯子           
                   
                   不要用root用户进行编译！！！！！
                   
                   
                   
1.支持不在home底下也能正常运行

2.只需要执行脚本就可以操作你任意的openwrt文件夹

3.新增国内DL服务器（感谢LGA1150）

4.新增选择 6.其他选项，可以单独使用个别模块，如：支持单独只搭建编译环境，而不进行编译

5. 创建文件时加入判断，防止覆盖之前的目录

6.删除之前的个别文件，脚本执行目录随意没有要求了，但Home目录底下的Openwrt目录禁止改名移动

7.我也不知道说啥！
