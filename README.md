[# window10-mount-centos](https://odinxu.com/post/centos-access-windows-shared-folders/

apt-get install cifs-utils -y

mount -t cifs -o username="root",password="123456",dir_mode=0777,file_mode=0777^Counix  //192.168.0.143/dnmp  /data/wwwroot/project



#mount.cifs -o username="root",password="123456",gid=root,uid=root,dir_mode=0777,file_mode=0777,nounix  //192.168.0.143/dnmp  /data/wwwroot/project)
