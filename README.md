默认情况下,chrony 不支持T1携带真实时间。但有的情况下需要携带真实实间

1）如果需要再让chrony发送T1时带真实时间，在/etc/chrony.conf中增加
t1_random 0
2）如果需要恢复默认值只需要把t1_random删除或改为1即可。表示继续用随机数
t1_random 1
