# qq
qqsb、Tencentsb  
8亿QQ绑定数据、腾讯泄露数据  

下载地址  
  
种子 https://mega.nz/file/ct9iVLia#Zd48MrnZehsNyPd0FWX9FZ1TTc7Q9Ket-zJvboABwPw  
磁力链接 magnet:?xt=urn:btih:963fd90eee4db809ed4224d1ca7a0639c443cf4b  
magnet:?xt=urn:btih:c81e0644fd67f73d81b94a31e3fc726679638a98&dn=pcht-v1  

# 举报一次腾讯安全的全体员工死个爹妈  
使用方式：  
建立数据库，建立表 user，  
qq 的两字段 qq 和 phone，  
WB的两字段 phone 和 uid ，  
字段类型想节省空间用 bigint 就够，不然用 char 或其他。  
修改语句中的文件路径。  
语句中的 IGNORE  字段是重复数据时不覆盖，去掉就是覆盖，自行决定覆不覆盖，有重复数据不好建立唯一索引。  
还要修改mysql的配置文件，下面的语句才能执行： 在 my.ini 文件中的 mysqld 段添加 secure_file_priv=”
导入完再添加索引。  
我导入两个库分别花了二十多分钟。  
不过还是分表分库或用 nosql 吧，一个表 8e 数据，建立索引了也吃不消，mysql 单表两千万条数据左右才吃得消。  

qq8e 的导入:  
LOAD DATA INFILE ‘D:/qq_6.9_8e_update.txt’ IGNORE  
INTO TABLE `user`  
FIELDS terminated by ‘—-‘  
lines terminated by ‘\n'(qq,phone)  
WB 5e 的导入:  
LOAD DATA INFILE ‘D:/0/weibo_2019_5e.txt’ IGNORE  
INTO TABLE `user`  
FIELDS TERMINATED BY ‘\t’  
LINES TERMINATED BY ‘\n'(phone,uid)  

备用地址  
https://www.kjsv.com/  
https://www.newyuanma.com/512.html  
https://www.qiqiboke.com/1041.html  
https://www.zslsb.com/qitafx/2219.html  
https://www.hzgzn.com/zybk/10418.html  
https://www.vpsche.com/10919.html  

自建TG社工库机器人[@shegongku58bot](https://t.me/shegongku58bot)
