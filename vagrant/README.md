#Openstack vagrant files for devstack
These are simple vagrant files for devstack installation .
its covers all the installation steps .
The installation is using the vagrant account to simplify things.

##Prerequisits 
1.virtualbox installed

2.vagrant installed

3.git installed  ( for windows "git for windows" includes the curl command )



##Centos7
```javascript
curl -s https://raw.githubusercontent.com/yapale/myexamples/master/vagrant/Vagrantfile -o Vagrantfile
vagrant up
```

you can ssh 
```javascript
/c/Users/admin/examples/examples/vagrant/.vagrant/machines/centos7/virtualbox
ssh vagrant@172.28.128.3 -i private_key
```


##Contribute
via pull requests please 



