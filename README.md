# SpartaRepos
Welcome

Vagrant.configure("2") do |config|

# choose the os/box/distro
 config.vm.box = "ubuntu/xenial64"
# config.vm.network "private_network", ip: "192.168.10.100"
# config.vm.network "private_network", ip: "192.168.56.0/21"
 config.vm.network "forwarded_port", guest: 80, host: 8081
 #vagrant destroy
 #vagrant up
 #vagrant reload
end 
-Who am I "uname -a"
-where am I 'pwd'
-list dir or all 'ls' or 'ls-1
- copy file 'cp filename destination'
- create file 'touch filename'
-create folder'mkdir filename'
-how to nevagate ' cd foldername'
- deleting file folder 'rm -rf foldername'

- **file permisssions**
- Read 'r', Write 'w' and excutable 'x'
- how to check permissions 'll'
- change permission ('chmod' permission r w or x filename)
- find out all processes running 'top'
-how to 'kill' a process
### Automate everything we have done manually###

- provision the steps of updating, upgrading and install nginx