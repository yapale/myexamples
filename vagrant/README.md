#Openstack vagrant files for devstack
These are simple vagrant files for devstack installation .
its covers all the installation steps .
The installation is using the vagrant account to simplify things.

##Prerequisits 
1.virtualbox installed

2.vagrant installed

3.git installed  ( for windows "git for windows" includes the curl command )


##Ice house
The Icehouse Vagrantfile is[ here ](https://github.com/yapale/vagrant/blob/master/Vagrantfile_icehouse)
you can use it as below: 
```javascript
curl -s https://raw.githubusercontent.com/yapale/vagrant/master/Vagrantfile_icehouse -o Vagrantfile
vagrant up
```

##Juno 
The Juno Vagrantfile is[ here ](https://github.com/yapale/vagrant/blob/master/Vagrantfile_juno)
you can use it as below: 
```javascript
curl -s https://raw.githubusercontent.com/yapale/vagrant/master/Vagrantfile_juno -o Vagrantfile
vagrant up
```
as Juno is still new , I am currently testing it .


##Contribute
via pull requests please 



