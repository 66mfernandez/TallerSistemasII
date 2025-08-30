Proyecto Ansible – Automatización de Servidores

Requisitos
- Ansible instalado en el nodo de control
- Conexión SSH a los servidores remotos
- Acceso sudo en los hosts

Ejecución
1. Clonar el repositorio:
   git clone https://github.com/tuusuario/proyecto-ansible.git
   cd proyecto-ansible

2. Se ultiliza esto comando para ejecutar los playbook con los permisos del superusuario
ansible-playbook -i inventory.ini playbook.yml --become --ask-become-pass
