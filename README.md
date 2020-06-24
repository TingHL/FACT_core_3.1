# FACT_core_3.1
## 说明 

安装时无需访问墙外资源 速度较慢   
已经将资源安装在http://112.126.82.245/files/ 和码云上    
到期时间:2021-4-6

## 安装建议   

安装步骤按照[FACT的安装步骤](https://github.com/fkie-cad/FACT_core/blob/master/INSTALL.md)进行

- npm 国内源  
  https://www.cnblogs.com/baby123/p/10753728.html



- 更改pip源  
    https://www.jianshu.com/p/ac4df573b9d9

- docker 镜像加速器

    在安装运行完 ./pre_install.sh之后,使用阿里云镜像加速器服务  
    https://yq.aliyun.com/articles/29941  
    https://help.aliyun.com/document_detail/60750.html

- 其他
```
sudo apt-get install openssl
sudo apt-get install libssl-dev
```