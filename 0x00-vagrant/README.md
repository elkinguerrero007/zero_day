# *Zero_day*
This is my first repository as a full-stack engineer


![vagrant](https://user-images.githubusercontent.com/85587286/160299036-eeab9bb0-8a3b-4cc7-b386-a1af05742327.png)


## [Ubuntu](https://ubuntu.com/)


* *Install VirtualBox: $ sudo apt-get install virtualbox


* Install Vagrant: $ sudo apt-get install vagrant


* Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64  Warning: this step can take time

* $ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine

* $ vagrant up -> it will start your virtual machine
* $ vagrant ssh -> now you are inside your virtual machine.


## *Windows*


Download VirtualBox
Install VirtualBox
Download Vagrant
Install Vagrant
Open the command prompt
Add the Ubuntu 20.04 (Focal) image to your box list:

* C:\Users\julien> vagrant box add ubuntu/focal64  


* C:\Users\julien> vagrant init ubuntu/focal64

-> it will generate a Vagrantfile with base = "ubuntu/focal64" 
-you don’t have to execute this command line everyday, only once, to create a new virtual machine

* C:\Users\julien> vagrant plugin install vagrant-vbguest -> to avoid issue with the last version of Vagrant (2.2.4 or latest)

* C:\Users\julien> vagrant up -> it will start your virtual machine 

* C:\Users\julien> vagrant ssh -> now you are inside your virtual machine. 


## *Mac OSx*

Download VirtualBox
Install VirtualBox
Download Vagrant
Install Vagrant
Open the Terminal application:
Now you will execute command line in your Terminal (each of them start with $)
Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64 Warning: this step can take time
Many other images are available here
Create your first virtual machine:

* $ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine

* $ vagrant up -> it will start your virtual machine 
* $ vagrant ssh -> now you are inside your virtual machine. 

