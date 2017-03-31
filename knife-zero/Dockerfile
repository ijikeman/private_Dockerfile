FROM centos:6

RUN rpm -ivh https://packages.chef.io/files/stable/chefdk/1.2.22/el/6/chefdk-1.2.22-1.el6.x86_64.rpm
RUN chef gem install knife-zero
RUN yum install openssh-server

EXPOSE 2222
CMD ["/sbin/init"]
