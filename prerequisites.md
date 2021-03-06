# Prerequisites for attendees

**For Windows users only**

If you plan to use Windows O/S for working on labs of this workshop, you are advised to install Linux based virtual machine to avoid common connectivity issues. The easiest way of doing it is by installing VirtualBox and Vagrant. 

Please perform the following:
 - [Install VirtualBox](http://download.virtualbox.org/virtualbox/5.1.14/VirtualBox-5.1.14-112924-Win.exe)
 - [Install Vagrant](https://releases.hashicorp.com/vagrant/1.9.1/vagrant_1.9.1.msi)
 - Install Ubuntu/Trusty64 box by running the following commands
 
 ```
 vagrant init ubuntu/trusty64
 vagrant up --provider virtualbox
 ```
- Within the virtual machine make sure you install NodeJS and NPM from [here](https://nodejs.org/en/download/)