# Ansible Ping Test

Questo repository contiene un playbook minimale per testare la connettività SSH con i server target tramite il modulo `ping` di Ansible.

## Esecuzione manuale

```bash
ansible-playbook -i inventories/cliente1/hosts.yml ping.yml

