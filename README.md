# vagrant-openbsd-cpp: a Vagrant box for building C/C++ binaries for OpenBSD

# VAGRANT CLOUD

https://app.vagrantup.com/mcandre/boxes/vagrant-openbsd-cpp

# EXAMPLE

```console
$ cd test
$ vagrant up
$ vagrant ssh -c "cd /vagrant && clang++ -o hello hello.cpp && ./hello"
Hello World!
```

# RUNTIME REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* The [VirtualBox](https://www.virtualbox.org) hypervisor provider

## Recommended

* [vagrant-rsync-back](https://github.com/smerrill/vagrant-rsync-back) assists in copying artifacts from the guest to the host

# BUILDTIME REQUIREMENTS

* [Vagrant](https://www.vagrantup.com)
* The [VirtualBox](https://www.virtualbox.org) hypervisor provider
* [make](https://www.gnu.org/software/make/)

# EXPORT

```console
$ make vagrant-openbsd-cpp.box
```
