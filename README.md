# ansible-ssh-port-probe

[![Build Status](https://travis-ci.org/nfaction/ansible-ssh-port-probe.svg?branch=master)](https://travis-ci.org/nfaction/ansible-ssh-port-probe)

Test ssh port(s) and install a one or more ssh keys for future logins

## Usage

Use the playbook in this role to probe ssh ports and install ssh keys:

``` bash
ansible-playbook <roles-path>/ansible-ssh-port-probe/ssh-port-probe.yml \
  -vvv -i <ip-of-host>, -k -u <username>
```
