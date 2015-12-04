# ansible-zookeeper
playbook for setting up zookeeper cluster

1. change ip adresses to your actual in etc/ansible/hosts file folowing included hosts file.
2. check if ping working -$ ansible zookeeper -m ping --ask-pass
3. run playbook -$ ansible-playbook provision.yml -K
