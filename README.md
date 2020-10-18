# vagrant-mylinux
Launch Linux server via Vagrant

## Configuration

### Base Image
- Base box image: "centos/8"

### Additional RPMs
- git
- ansible

### Miscellaneous
- DNS workaround for VirtualBox
  (https://www.vagrantup.com/docs/virtualbox/common-issues.html)
- Enable EPEL repo (required for Ansible)
