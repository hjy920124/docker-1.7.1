rpm -ivh lxc-libs-1.0.9-1.el6.x86_64.rpm
rpm -ivh lua-alt-getopt-0.7.0-1.el6.noarch.rpm
rpm -ivh lua-filesystem-1.4.2-1.el6.x86_64.rpm
rpm -ivh lua-lxc-1.0.9-1.el6.x86_64.rpm  
rpm -ivh lxc-1.0.9-1.el6.x86_64.rpm  
rpm -ivh docker-io-1.7.1-2.el6.x86_64.rpm


rpm -ivh device-mapper-libs-1.02.117-12.el6.x86_64.rpm --force --nodeps

service docker start
