# This is K8s on Vagrant

This is a quick script that lets you start up a k8s cluster on any old Ubuntu box you may have had lying around.
Mine runs Focal Fossa, has 8 GB RAM and a 4-core i5 processor, so your results may vary. But most should work.
[Credit to original instructions that I modified are here.](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

### Instructions for use

Install Ansible and Vagrant and confirm they work using the ```--version``` flag

Clone this project

CD into the cloned dir

```vagrant up && vagrant ssh k8s-master```
