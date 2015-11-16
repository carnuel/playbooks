docker_hadoop.yml
playbook that runs 1 hadoop container on each node using --net="host"




no_docker_hadoop.yml
playbook that runs hadoop on each node, independent from docker




Folder basics:
contains basic operations like 
- clear_containers
- clear_images
- docker_restart




Folder hosts:
contains host operations like 
- setting environmental variables
- copy ssh or tls keys
- copy docker daemon config
- restart server




Folder pipework:
contains all operations related to pipework




Folder setup:
contains installing and uninstalling operations
