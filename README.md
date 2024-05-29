# xitee DevOps Homework

This is a repository for a DevOps homework as part of the hiring process of xitee. \
The components used are Ubuntu 22.04 LTS and VirtualBox hypervisor. \
The recommended commands to run this repository (after creating a fresh VM) are: \
<code>
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible

sudo apt install ansible git
git clone github.com/AdamTrn/xiteeHW
cd xiteeHW
sudo ansible-playbook xitee-homework.yml
</code>