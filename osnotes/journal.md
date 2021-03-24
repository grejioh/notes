# gcc4.x x
# docker
## docker cgproxy bug
https://github.com/springzfx/cgproxy/issues/3


## docker 

文件夹链接
```shell
sudo docker run -it -v /home/grejioh/ucore-2_root:/root --name ucore_lab_env registry.cn-hangzhou.aliyuncs.com/nzpznk/oslab-c-env /bin/bash
```
启动bash
```shell
sudo docker exec -it container_name /bin/bash
```
bug
更新了linux kernal后会有bug, 重启后bug消失



