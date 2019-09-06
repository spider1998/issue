# issue

****
fatal: Out of memory, malloc failed (tried to allocate 2000000000 bytes)
--
    :git config --global http.postBuffer 1024
    
****
curl: (56) GnuTLS recv error (-54): Error in the pull function.
--
    :git config --global http.postBuffer 2000000000


****
gradle:What went wrong: A problem occurred evaluating project ':service-asset-management'. > Could not find method compileOnly() for arguments [project ':sitewhere-hbase'] on project ':service-asset-management'.
--
    :gradle版本太低，升级
    

****
MySQL字段时间差查询
--
    eg: select * from 表名 where DATEDIFF(DATE(now()),DATE(时间字段名)) > 值-差值;
    
    
****
localhost、127.0.0.1可以访问，ip不能访问
--
    eg: 打开端口：sudo ufw allow 80、sudo ufw enable、sudo ufw reload
    
    
    








