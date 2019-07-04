# Play book for Wi-Fi adaper

## Usage

```bash
sudo apt update
sudo apt install software-properties-common
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible

git clone https://github.com/chmod644/rtl8812au-setup-playbook.git
cd rtl8812au-setup-playbook
ansible-playbook playbook.yml -u ansible -i localhost, -c local --ask-become-pass
```