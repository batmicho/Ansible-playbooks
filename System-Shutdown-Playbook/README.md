# Shutdown the hosts defined in /etc/ansible

[cd-lab]

192.168.0.105 ansible_connection=ssh ansible_user=<yourUsername>
192.168.0.106 ansible_connection=ssh ansible_user=<yourUsername>
192.168.0.107 ansible_connection=ssh ansible_user=<yourUsername>

-- Or create a file names 'hosts' add your hosts same as above and run with command:

ansible-playbook -i hosts playbook.yml -k

# run

ansible-playbook playbook.yml -K
