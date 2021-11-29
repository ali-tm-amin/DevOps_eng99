# Creating a virtual mechine with linux Ubantu 16.04
# ubantu/xenial164

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
