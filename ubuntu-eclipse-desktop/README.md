## Run Eclipse Desktop from a vagrant box

### Prerequites

You will need to have the following tools.

* [VirtualBox](https://www.virtualbox.org)
* [Vagrant](https://www.vagrantup.com/)

### Set-up

From the root of this directory, executing below command will setup the VM like described in the Vagrantfile.

```shellscript
$ vagrant up
```

### To Start xfce desktop Use Below Command

```shellscript
$ startxfce4 &
```
Note: for 32-bit vagrant box modify config.vm.box to "ubuntu/trusty32"