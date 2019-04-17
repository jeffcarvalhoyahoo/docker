FROM  docker.io/fedora

RUN yum -y install  diffutils
RUN yum -y install  findutils  procps  

RUN yum -y clean all


COPY  wait_forever.sh  /
CMD /wait_forever.sh
