# Cofiguración de Ansible

**Se instalaran  y configuraran estos 2 servicios:**

* Apache
* Munin

## Primer paso, instalación del servidor web

**instalamos el servidor web en el name_web_server**

## Instalacion de Apache

**utilizamos el sguiente comando en nuestra terminal:**

`ansible-playbook -i hosts install_apache.yml`

## Instalacion de Munin

**Intalamos Munin en el name_web_server**

**utilizamos el sguiente comando en nuestra terminal: **

`ansible-playbook -i hosts install_munin.yml`

## Iniciar el servicio de Apache

**Regresamos a la carpeta dockerfile y ejecutamos el siguiente comando:**

`service start apache2`

Despues ingresamos nuevamente por medio del navegador web a la ruta `127.0.0.1`
