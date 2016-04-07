ansible-maxamillion.sh
======================

Ansible playbooks and roles for maxamillion.sh

I have a machine that I use for various random tasks and I manage
it with ansible. These are the bits, posted on github because ... why not?

If these playbooks are remotely useful for others, anyone is free to
consume and modify in accordance with the GPLv3

Using
------
Edit inventory.txt appropriately.

For Fedora 23 or newer, run the bootstrap ansible playbook

    ansible-playbook bootstrap-fedora.yml -i inventory.txt

Then run the actual playbook

    ansible-playbook site.yml -i inventory.txt

Happy hacking,
-AdamM
