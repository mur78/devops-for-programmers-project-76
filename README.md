### Hexlet tests and linter status:
[![Actions Status](https://github.com/mur78/devops-for-programmers-project-76/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/mur78/devops-for-programmers-project-76/actions)
DevOps for Programmers: Project 76


Requirements:
    Ansible
    Python


Make Commands:

	make ping: используется для проверки доступности всех хостов
	make prepare: используется для установки ролей Ansible, указанных в файле requirements.yml
	make encrypt:  используется для шифрования файла с помощью Ansible Vault.	
	make setup: используется для запуска Ansible плейбука с tag Setup
	make deploy: используется для запуска Ansible плейбука c tag Deploy 
