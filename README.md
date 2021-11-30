# SpartaRepos

## What is DevOps ##
* Breaking the silo between Dev and Ops
* Create a better culture
## Why DevOPs ##
* Ensure faster deployment.
* Stabilize work environment.
* Significant improvement in product quality.
* Automation in repetitive tasks leaves more room for innovation.
* Promotes agility in your business.
* Continuous delivery of software.
* Fast and reliable.
* problem-solving techniques.
## 4 pillars of DevOps ##
* Environments
* Deployment
* Testing and
* People

## Risks ##
* low/medium risks
### Development Env ###

• Install vagrant

• Install Ruby

## Linux Commands ##

• `sudo apt-get update -y`

#Creating a virtual mechine with Linux Ubuntu 16.04
#Ubuntu/xenial64

Vagrant.configure("2") do |config|

#Choose the os/box/distro
 config.vm.box = "ubuntu/xenial64"

config.vm.network "private_network", ip: "192.168.10.100"

#config.vm.network "private_network", ip: "192.168.56.0/21" (if firewall preveting the network config, use the local port below)
 
 #config.vm.network "forwarded_port", guest: 80, host: 8081.
 
#vagrant destroy
 
#vagrant up
 
 #vagrant reload
end 

* Who am I `uname -a`
* where am I `pwd`
* list dir or all `ls` or `ls-a`
* copy file `cp filename destination`
* create file `touch filename`
* create folder `mkdir filename`
* how to nevagate `cd foldername` to return `cd ..`
* deleting file folder `rm -rf foldername`
* cut or rename `mv filename destination`


 **File Permisssions**

- Read `r` Write `w` and excutable `x`
- how to check permissions `ll`
- change permission `chmod` permission `r` `w` or `x` `filename`
- find out all processes running `top`
-how to `kill` a process
### Automate everything we have done manually ###

- provision the steps of updating, upgrading and install nginx
- vagrant up again
- redo all the steps
- install nginx and load it in the browser

## Commands ##
* head -2
* tail -2
* pipping: `command_1 | command_2 | command_3 | .... | command_N` 
* A pipe is a form of redirection (transfer of standard output to some other destination) that is used in Linux and other Unix-like operating systems to send the output of one command/program/process to another command/program/process for further processing. ... You can make it do so by using the pipe character `|`.

`cat myfile | head -2 | tail -2`



