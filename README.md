# Steps to Run this playbook `ec2-instance-create.yml` to Launch EC2 instance on your AWS ACCOUNT

1. Install `python 2.7` or later version
2. Intstall `Ansible` on your system from where you want run playbooks

```bash
sudo apt update
sudo apt upgrade
sudo apt install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
ansible --version
```
3. Install `boto` library package

```bash
pip3 install boto3   ( for python3 )
pip install boto     ( for python2 )
```
4. Configure AWS CLI using command `aws-configure`
5. Clone this repo on your system
6. Finally run this playbook by using this command `ansible-playbook ec2-instance-create.yml`
7. while runnig this playboook, you will asked to input few information like aws region name, ami name, subnet id, keypair name etc.
