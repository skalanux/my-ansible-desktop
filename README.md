# my-ansible-desktop
Installation of my boxes using ansible


Install Ansible :

    $ sudo apt-get install -y -qq python python-pip
    $ sudo pip install ansible
    $ sudo ansible-galaxy install angstwad.docker_ubuntu

And execute command :

    $ ansible-playbook -i hosts site.yml -c local -K --ask-vault-pass


