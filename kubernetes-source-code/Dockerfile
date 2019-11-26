FROM centos

RUN yum install -y wget
RUN mkdir 1.14.2
RUN wget https://dl.k8s.io/v1.14.2/kubernetes-client-linux-amd64.tar.gz
RUN wget https://dl.k8s.io/v1.14.2/kubernetes-server-linux-amd64.tar.gz


RUN wget https://github.com/projectcalico/calicoctl/releases/download/v3.6.1/calicoctl 

RUN yum install openssh-clients -y
