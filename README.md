# Ansible Windows Example
For the indy Ansible meetup on 8/16/2016. This project outlines a simple example for provisioning a Windows machine with Ansible

Steps:

* vagrant up
* On the Windows guest VM, download and execute:
 https://raw.githubusercontent.com/ansible/ansible/devel/examples/scripts/ConfigureRemotingForAnsible.ps1
* ansible-playbook site.yml
* Verify your setup is working by going to: http://localhost on your guest.
