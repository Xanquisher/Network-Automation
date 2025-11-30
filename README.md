# Network-Automation
This project builds a lab of four VyOS routers running as Docker containers, with their management plane reachable from an Ansible control host over SSH. It demonstrates how to use Ansible to push static route configuration changes and validate routing state before and after the change using `show ip route` outputs saved as artifacts in the repo.
