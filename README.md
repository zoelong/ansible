# ansible
This job is for how to build the ansible job on linux server ,and you can use it to build your own job to maintain the other server .

# this step will install the lastest version of ansible and python2
yum install ansible 
# check ansible available and version
ansible --version
# check python
whereis python
# check ansible status
ansible ip -u ** -k -m ping
you can check ansible command if you are intersted
# remember to create the ansible user and group
# create ssh_key
# add servername or ip in the /etc/ansible/hosts list 
