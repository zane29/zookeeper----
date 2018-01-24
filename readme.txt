zkLevamAppConfig-101.script使用方法
1，进入一台linux服务器找到zookeeper的bin目录

例如：ssh root@10.10.9.28
cd /home/avx/hq-work/zookeeper-3.5.2-alpha2/bin


2,利用Xftp工具将zkLevamAppConfig-101.script文件放入bin目录

例如：将zkLevamAppConfig-101.script放入/home/avx/hq-work/zookeeper-3.5.2-alpha2/bin文件夹中


3，在bin目录执行命令初始化数据命令

例如：
cd /home/avx/hq-work/zookeeper-3.5.2-alpha2/bin
./zkCli.sh -server 10.10.9.103:2181 < zzkLevamAppConfig-101.script
