# Getting-Started-with-Ansible
Objectives: Automate system administration tasks on managed hosts with Ansible.  Learn how to write Ansible playbooks to standardize task execution.

## Installing Ansible
 For now ansible is not supporting windows OS, so we are using the linux system for ansdible.
 ### Installation steps are given follow for linux system (UBUNTU)
 Debian/Ubuntu:
    The easiest way to install Ansible on a Debian or Ubuntu system is to use the official apt package.
* $ sudo apt-add-repository -y ppa:ansible/ansible
* $ sudo apt-get update
* $ sudo apt-get install -y ansible
* If you get an error like “sudo: add-apt-repository: command not found”, you’re probably missing the python-software-properties package. Install it with the command:
* $ sudo apt-get install python-software-properties

Once Ansible is installed, make sure it’s working properly by entering ansible --version on the
command line. You should see the currently-installed version:

$ ansible --version