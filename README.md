# ansible
This job is for how to build the ansible job on linux server ,and you can use it to build your own job to maintain the other server .

1.yum install ansible 
# this step will install the lastest version of ansible and python2

2.ansible --version
#check ansible available and version

3.whereis python
#check python

4.ansible ip -u ** -k -m ping
#check ansible status
# you can check ansible command if you are intersted

5.remember to create the ansible user and group

6.create ssh_key

7.add servername or ip in the /etc/ansible/hosts list 

