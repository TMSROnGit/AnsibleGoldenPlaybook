	1. sudo apt update 
  
	2. sudo apt install ansible git -y #Installs git on machine
	
	3. git clone https://github.com/TMSROnGit/AnsibleGoldenPlaybook.git #Clones repo where the files are config files are
	
	4.  cd AnsibleGoldenPlaybook/
	
	5. ansible-galaxy install -r requirements.yml #Installs all the roles on the requirements file
	
	6. ansible-playbook local.yml #Runs playbook


Steps to apply the playbook
