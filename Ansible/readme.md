# Cofiguración de Ansible

Se instalaran  y configuraran estos 2 servicios : 

<ul>
  <li>Apache</li>
  <li>Munin</li>
</ul>

<h3>Primer paso, instalación del servidor web</h3>

## instalamos el servidor web en el name_web_server

<h2>Instalacion de Apache</h2>

utilizamos el sguiente comando en nuestra terminal: 

ansible-playbook -i hosts install_apache.yml

<h2>Instalacion de Munin</h2>

## -Intalamos Munin en el name_web_server

utilizamos el sguiente comando en nuestra terminal: 

ansible-playbook -i hosts install_munin.yml

<h2>Iniciar el servicio de Apache</h2>

Regresamos a la carpeta dockerfile y ejecutamos el siguiente comando:

service start apache2

Despues ingresamos nuevamente por medio del navegador web a la ruta 127.0.0.1
