default:
	echo "No default!"

install-docker:
	ansible-playbook ansible/playbooks/install-docker.yml -i inventory.ini --ask-become-pass -l localhost

copy:
	ansible-playbook ansible/playbooks/copy-file.yml -i inventory.ini --ask-become-pass -l localhost

up:
	ansible-playbook ansible/playbooks/run-compose.yml -i inventory.ini --ask-become-pass -l localhost
