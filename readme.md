# This ansible repository is for configuring and securing debian based linux servers and machine

## This playbook is still in development

### works on ubuntu based machine

To use:

* Make a host.ini file in directory

* Edit it with remote/local node info

* Run playbook with:

```bash
ansible-playbook main.yml -i hosts.ini 
```

or

```bash
ansible-playbook main.yml -i hosts.ini --limit=<node name>
```

or to run locally

```bash
ansible-playbook main.yml -i hosts.ini --connection=local -K
```

or to run with verbose enable

```bash
ansible-playbook main.yml -i hosts.ini -k -K -vvvv
```