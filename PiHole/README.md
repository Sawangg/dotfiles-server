# PiHole + Unbound

## ☸️ Deploy
Then you can run the playbook
```sh
ansible-playbook -k -K playbook-deploy.yml -e @../global_vars.yml
```

## 🔥 Reset
Simply run the following Ansible playbook
```sh
ansible-playbook -k -K playbook-reset.yml
```

_You can remove `-k -K` if you don't need a SSH password_
