## Using an Ansible Playbook to spin up EC2 instance

## 1. Provisioning Ansible controller (prerequisites)

```bash
sudo apt-get install software-properties-common -y
sudo apt-get install tree -y
sudo apt-add-repository--yes--update ppa:ansible/ansible
sudo apt-get install ansible -y
sudo apt-get install sshpass -y
sudo apt-get install tree -y
```

## 2. Install EC2 module dependencies

```bash
sudo apt install python

sudo apt install python-pip -y

sudo pip install --upgrade pip

sudo pip install boto

sudo pip install boto3
```


## 3. Create SSH keys to connect to EC2 instance

```bash
ssh-keygen -t rsa -b 4096 -f ~/.ssh/<Your_Name>_aws
```
