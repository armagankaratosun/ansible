# Ansible Playbook for installing LAMP

You can use it in localserver by;

```bash
ansible-playbook -i "localhost," -c local --ask-sudo-pass apache.yml 
```

or you can create hosts file to run it on distant servers.

## TODO

- [ ] Add conditions for distros. 
- [ ] Make this code workable for different distros and support f.e. yum.
- [ ] Make tunings on mysql, apache etc.
