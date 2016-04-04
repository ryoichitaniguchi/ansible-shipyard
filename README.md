shipyard - Ansible Playbook for Shipyard
=============
## Overview

This is ansible roles for shipyard installation. 

By design, install procedure would follow official manual installation.
https://shipyard-project.com/docs/deploy/manual/

So it needs connection to dockerhub to pull related images 

and also docker should be installed in advance on target machine.

## option
"install_mode" must be specified either "manager" or "node"

## how to execute 
``` bash

  $ ansible-playbook -i sample/inventory sample/playbook.yml -K 
``` 
