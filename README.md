# disable-login-list-playbook-example
Playbook example to disable login list 

You will have to edit this file to make it work for your system.
To run the playbook:  
<pre>
$ ansible-playbook disable-login-list-playbook.yml --ask-become-pass  
</pre>

You will need the sudo/become password for the ansible/ssh user to run this playbook.  

To develop an ansible role:  
Write the playbook with descreet tasks.  
Create files and templates needed for tasks.  
Test and make sure that the playbook works as expected.  
Create directory ./roles relative to your playbook(s)
Change directory to ./roles
Use ansible-galaxy command:  
ansible-galaxy init "rolename"  
In this case:  ansible-galaxy init motd-setup-ansible  
and edit appropriate files.

Take a look at https://github.com/customizedcode/disable-login-list 
and compare the files mentioned above.

License
--------
MIT
-----
Roy Kim
customizedcode.us
https://github.com/customizedcode
