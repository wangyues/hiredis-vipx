# hiredis-vipx
hiredis-vip是唯品会在hiredis基础上开发的，支持redis cluster的客户端。

hiredis-vip链接：https://github.com/vipshop/hiredis-vip

hiredis-vipx在此基础上添加修改的内容：

1.添加密码支持

      redisClusterSetOptionAuth(cc, "Jyy222");
      
2.修改hiredis-vip不支持redis 4.x的问题
