FROM centos
RUN yum update -y && \
    yum -y install wget && \
    yum -y install curl
ENTRYPOINT ["curl", "http://ip.cn"]

