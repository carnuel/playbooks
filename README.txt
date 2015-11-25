basics:
- clear_containers
- clear_images
- docker_restart



database:
- cadvisor on nodes
- database on manager



hadoop_docker:
- main playbook for running hadoop using host interface, includes database



hadoop_no_docker:
- main playbook for installing hadoop and setting up configurations
- set/unset HADOOP - environment variables
- install/delete hadoop
- copy resources



hadoop_swarm:
- main playbook for setting up swarm and starting hadoop, includes database
- clearcontainers
- daemon configuration



hosts:
- basic operations on hosts
- TLS and SSH
- reboot 
- reset daemons



install:
- install/uninstall playbooks for docker, compose, machine, consul, virtualbox



pipwork:
- pre-swarm setup
