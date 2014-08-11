dataunity-deploy
================

Deployment scripts for Data Unity

Installing dependencies
-----------------------

The deployment scripts use Ansible. To install ansible see the <a href="http://docs.ansible.com/intro_installation.html#latest-releases-via-apt-ubuntu" target="_blank">installation instructions on the Ansible website</a>.

Running the scripts
-------------------

To run the script use the ansible-playbook command followed by the name of the playbook, e.g:

<pre>
ansible-playbook fuseki.yml
</pre>

For playbooks which need sudo priviledges, prompt for the sudo password:

<pre>
ansible-playbook -K fuseki.yml
</pre>