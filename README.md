# Rancher- CLI
This ansible role will install Rancher Command Line Interface <br/>
<br/>
Requirements<br/>
ansible installation<br/>
<br/>
Role Variables
<br/>
Available variables are listed below, along with variables <br/>
vars/main.yml<br/>
<br/>
### Default instatllation direction is in /usr/local/bin, can be customized as required.<br/>
<pre>
rancher_cli_install_dir: /usr/local/bin
</pre>
<br/>
### The version can be customized as required in the vars.<br/>
<br/>
<pre>
rancher_cli_version: v1.6
</pre>
<br/>
Dependencies<br/>
Example Playbook : ~/ansible/playbooks/test.yml<br/>
<pre>
---
- hosts: all
  become: true 
  roles:
    - docker
</pre>
Testing the role with vagrant<br/>
Dependencies: Vagrant must be installed<br/>
<pre>
vagrant up
</pre>
<br/>
License<br/>
Example Playbook : ~/ansible/playbooks/test.yml<br/>
<br/>
MIT / BSD
