FROM centos:centos7.9.2009

RUN yum -y install \
           telnet \
           wget \
           vim \
           bash-completion \
           tcpdump \
           traceroute \
           ssh \
           nmap-ncat

RUN yum -y update

CMD ["/bin/bash"]

USER 1001

# k -n centos-linux exec -it pod/centos-linux-8476884db-24fqc -- bash