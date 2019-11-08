FROM centos

RUN yum install -y wget
RUN mkdir 1.16.2
RUN wget /root/1.16.2/https://dl.k8s.io/v1.16.2/kubernetes-client-linux-amd64.tar.gz
RUN wget /root/1.16.2/https://dl.k8s.io/v1.16.2/kubernetes-server-linux-amd64.tar.gz
RUN mkdir 1.14.2
RUN wget /root/1.14.2/https://dl.k8s.io/v1.14.2/kubernetes-client-linux-amd64.tar.gz
RUN wget /root/1.14.2/https://dl.k8s.io/v1.14.2/kubernetes-server-linux-amd64.tar.gz

RUN wget https://github.com/etcd-io/etcd/releases/download/v3.4.3/etcd-v3.4.3-linux-amd64.tar.gz

RUN yum install openssh-clients -y
