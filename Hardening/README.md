# so-hardening

Primera version de role de Hardenig 

Dentro de la carpeta Hardening/roles se encuentra el role completo

Para efectos de pruebas se cuenta con varios playbooks y estos a su vez estan tagueados, por lo que si se desea unicamente usar unas partes del role se puede hacer con el paramentro --tag ejemplo

ansible-playbook -i hosts  main.yml --tag sshd


Los diferentes tags son:
yum
services
filesystem_configuration
sshd
login_defs
rhosts
