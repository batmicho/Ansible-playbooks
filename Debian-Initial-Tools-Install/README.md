# Ansible simple playbook for Debian initial installation.

This Ansible playbook to install Docker and some tools: curl, tmux, git, vim, htop, python-pip, nginx.

# Parameters

Add the usernames with which you are accessing the hosts in host file.

#hosts

add your hosts in the host file.

#run

Run it with:

```
ansible-playbook -i hosts playbook.yml -K
```

Copyright
==========

Copyright (c) 2018 M.D
