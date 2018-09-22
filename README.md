# Dockerfile简单讲解

## 示例
创建一个目录，进入该命令创建并编辑Dockerfile文件，填入以下内容：
```
FROM centos
RUN yum update -y && yum -y install wget && yum -y install curl
ENTRYPOINT ["curl", "http://ip.cn"]
```
