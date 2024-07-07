default:
	echo "No default!"

install-docker:
	ansible-playbook ansible/playbooks/install-docker.yml -i inventory.ini --ask-become-pass -l localhost

copy:
	ansible-playbook ansible/playbooks/copy-file.yml -i inventory.ini --ask-become-pass -l localhost

up:
	ansible-playbook ansible/playbooks/run-compose.yml -i inventory.ini --ask-become-pass -l localhost

del-ec2:
	ansible-playbook ansible/playbooks/ec-down.yml -i inventory.ini

install-py:
	ansible-playbook ansible/playbooks/install-python.yml -i inventory.ini

cre-ec2:
	ansible-playbook ansible/playbooks/ec-create.yml -i inventory.ini
