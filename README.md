## Preinstalled
* setting the ssh passwordless login
```
# su
# ssh-keygen -t rsa
# ssh-copy-id root@localhost
```
* install ansible command
```
# yum install -y epel-release
# yum install -y ansible
```
* setting environment variable for not checking ssh key
```
# export ANSIBLE_HOST_KEY_CHECKING=False
```
