Demo to WebApp...

* MySQL VM.
* Two VMs running apache-php container to connect to the MySQL DB.
* HAProxy using both web containers.

Maintenance playbooks to update the DB and Web hosts.\
Playbook to add sample data to the DB.\
Playbook to update the website.

Ansible-galaxy roles used - info in the roles dir.\

MySQL passwords (mysql_root, mysql_robb)  to be stored in vars/secrets vault file.\


