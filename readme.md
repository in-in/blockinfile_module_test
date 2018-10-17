```bash
sudo apt update &&
sudo apt install -y\
  build-essential\
  git\
  python3-pip\
  python3-setuptools\
  python3-wheel &&
sudo -H python3 -m pip install --upgrade\
  pip\
  setuptools\
  launchpadlib\
  virtualenv\
  ansible
```

```bash
git clone https://github.com/in-in/blockinfile_module_test.git blockinfile_module_test && cd blockinfile_module_test
```

```bash
ansible-playbook --verbose playbook.yml
```