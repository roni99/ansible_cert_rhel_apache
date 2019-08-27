# Process Overview

## Assumptions
  - You have a valid domain name registered

## 1. Populate variables in vars.yml and in hosts
  - Enter the domain name of the host into [hosts][hosts]
  - Enter an email and region in [vars.yml][vars] (if region unknown, the value "REGION" is sufficient)

## 2. Retreive the key associated to the instance
  - Edit the path to the private key in [ansible.cfg][cfg]

## 3. Running the playbook
  - > `ansible-playbook certify_rhel_apache.yml`

[hosts]: https://github.com/roni99/ansible_cert_rhel_apache/blob/master/hosts
[vars]: https://github.com/roni99/ansible_cert_rhel_apache/blob/master/vars.yml
[cfg]: https://github.com/roni99/ansible_cert_rhel_apache/blob/master/ansible.cfg
