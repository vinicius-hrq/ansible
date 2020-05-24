# Ansible
### First
```
export AWS_ACCESS_KEY_ID='your access key'
export AWS_SECRET_ACCESS_KEY='your secret key'
```
### Run

`ansible-playbook -i hosts main.yml`

### Connection Test

`ansible -i hosts all -m ping -u ubuntu`
