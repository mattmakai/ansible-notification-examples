# Ansible notifications examples
This project provides examples for many of the Ansible notification modules
as of Ansible 1.6.1 release.

## Modules
* Hipchat
* mail
* Twilio

## Walkthrough
Copy set\_envs.sh.template to set\envs.sh and fill in your environment 
variables. 

The playbook uses the get\_url module to download a remote file
and save it to the local node. However, the filename has a typo so it fails.
We ignore the error and since the file did not download it kicks off the 
notifications modules.

