# FACT_core_3.1
## 说明 

安装时无需访问墙外资源 速度较慢   

删除了linter、oms插件   

## 建议 

- 更改pip源

https://blog.csdn.net/lambert310/article/details/52412059

linux下，修改 ~/.pip/pip.conf (没有就创建一个)， 修改 index-url至tuna，内容如下：

​        [global]

​       index-url = https://pypi.tuna.tsinghua.edu.cn/simple

- docker 镜像加速器

https://help.aliyun.com/document_detail/60750.html

