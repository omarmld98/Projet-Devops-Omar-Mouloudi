Projet de construction d'envirennement de production et staging avec ansible.

Nom: Omar Mouloudi

Objectifs:
Construction d'un environnement de production et staging et deploiment d'une page php et établir une connexion avec deux base de données distincts.

Commandes pour lancer nos playbooks:

ansible-playbook webservers.yml -i inventories

ansible-playbook dbservers.yml -i inventories

ansible-playbook main.yml -i inventories

Nos base de données:
prod_user: omar2
prod_db_name: db_omar2
mysql_prod_pass: omar123
stag_user: omar1
stag_db_name: db_omar1
mysql_stag_pass: omar123
