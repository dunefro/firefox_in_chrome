# firefox_in_chrome
Ansible playbook and Dockerfile to launch firefox inside any other browser.
Following Steps are required -
1) DNS entries must be configured and hosts file can be used if container is to be laucnhed on different nodes.
2) Completely fill the var.yml file which describe the path where the dockerfile currently is and the port which is free to get exposed.
3) Run the main.yml playbook.
4) Use any local browser and type http://<Local IP>:<exposed port>.
5) Connect as xpra client.
