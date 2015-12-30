#CentOS 7 Blank VMs

This vagrant file sets up three vanilla CentOS 7 vms to use for testing.

To change vagrant boxes search for a new Vagrant box on:

#Getting Started

##Requirements

###Install Vagrantm, Cygwin and Virtualbox

- [Vagrant](https://www.vagrantup.com/downloads.html)
- [Cygwin](https://cygwin.com/install.html)
- [Virtualbox](https://www.virtualbox.org/wiki/Downloads)

Make sure Vagrant is in your PATH environment variable.

##Clone Repository
```
git clone https://github.com/travmi/vagrant-centos7.git
```

##Start VMs

###Starting all three VMs

Open a Windows Command windows and go to where you cloned the repository.
Three VMs will be created when issuing 'vagrant up' or you can create a single one by running 'vagrant up agent1'.

cd vagrant-centos7

```
vagrant up
```

##Starting Single VM
cd vagrant-centos7

```
vagrant up agent1
```

##Accessing the VMs

You will need to have Cygwin installed with SSH.

- agent1 = 172.16.90.5
- agent2 = 172.16.90.6
- agent3 = 172.16.90.7

Password is "vagrant" for all VMs.
```
ssh root@172.16.90.5
```
