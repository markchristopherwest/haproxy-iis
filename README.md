## Synopsis

This Ansible playbook is designed to spawn instances in AWS or VMware to create an application stack where an HA proxy instance is placed in from of IIS instance(s)

## Code Example

ansible-playbook site.yml -i inventory.txt -vvvv -e 'host_key_checking=False' 

## Motivation

To reduce the headache of load balancing IIS via AWS of VMW.

## Installation

Install Ansible
Clone Repo
Change Directories
See Above

## API Reference

Place this behind Tower for a REST based solution!

## Tests

Test this sample by executing the playbook & then validating connectivity to load balanced services

## Contributors

Mark West of Red Hat

## License

Apache 2 Licensed