# Ansible playbook for Wi-Fi adaper

## Usage

```bash
# install ansible
sudo apt update
sudo apt install software-properties-common
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible

# run playbook
git clone https://github.com/chmod644/rtl8812au-setup-playbook.git
cd rtl8812au-setup-playbook
ansible-playbook playbook.yml -u ansible -i localhost, -c local --ask-become-pass
```

## Supported adapter

Please refer the source code in [msharov/rtl8812au](https://github.com/msharov/rtl8812au/blob/master/os_dep/linux/usb_intf.c).
