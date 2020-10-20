# vagrant-mylinux
Launch Linux server via Vagrant

## Configuration

### Base Image
- Base box image: "centos/8"
- Update all RPMs

### Additional RPMs
- git
- ansible

### Miscellaneous
- DNS workaround for VirtualBox
  (https://www.vagrantup.com/docs/virtualbox/common-issues.html)
- Enable EPEL repo (required for Ansible)
- Clone https://github.com/troppens/ansible-mylinux to /root/ mylinux
