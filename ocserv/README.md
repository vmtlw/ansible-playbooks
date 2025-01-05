### Запустите playbook, указав инвентарь:

```bash
ansible-playbook -i inventory configure_ocserv.yml
```
или передавая host и ssh ключ в агрукументах
```bash
ansible-playbook -i '192.168.1.100,' configure_ocserv.yml --user=root --private-key=~/.ssh/id_ed25519
```
