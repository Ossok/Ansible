# TP Ansible

## Objectifs
- Automatiser la création d’utilisateur
- Automatiser la sauvegarde et la restauration
- Automatiser la création de base de données et gestion des droits
## Test connexion User

### Modification inventaire.ini


```bash
nano inventaire.ini
```

### Test connexion User

```bash
ansible all -i inventaire.ini -m ping
```

## Lancer le playbook
```bash
ansible-playbook -i inventaire.ini site.yml
```
