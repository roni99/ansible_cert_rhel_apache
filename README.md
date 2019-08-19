# Process Overview

## Assumptions
  - You have a valid domain name registered

## 1. Populate variables in vars.yml and in hosts
  - Enter the domain name of the host into [hosts][hosts]
  - Enter an email and region in [vars.yml][vars]

## 2. Running the playbook
  - > `ansible-playbook certify_rhel_apache.yml`

[hosts]: https://github.com/rlazimi-dev/ansible_cert_rhel_apache/blob/master/hosts
[vars]: https://github.com/rlazimi-dev/ansible_cert_rhel_apache/blob/master/vars.yml
