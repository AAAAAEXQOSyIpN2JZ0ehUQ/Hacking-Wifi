![logo](https://github.com/AAAAAEXQOSyIpN2JZ0ehUQ/Hacking-Wifi/blob/main/Imagenes/hacking-wifi.png)

# Hacking-Wifi
**Kali linux - drivers y herramientas para hacking Wifi**

## :information_source: Descripci�n
Kali linux - drivers y herramientas para hacking Wifi est� dise�ado para automatizar la 
instalaci�n y verificaci�n de diversos controladores y herramientas esenciales para 
la auditor�a de seguridad de redes wifi. El objetivo principal es asegurar que todos 
los componentes necesarios est�n instalados y configurados correctamente para 
realizar auditor�as de redes wifi y pruebas de penetraci�n.

## :computer: Instalaci�n
```bash
cd /opt
sudo rm -rf Hacking-Wifi
sudo git clone git@github.com:AAAAAEXQOSyIpN2JZ0ehUQ/Hacking-Wifi.git
sudo chmod +x Hacking-Wifi/*
cd Hacking-Wifi
ls -ltha
```

## :key: Acceso Directo
```bash
cd 
sudo echo "cd /opt/Hacking-Wifi && sudo ./menu.sh" > hackingwifi
sudo chmod +x hackingwifi
sudo mv hackingwifi /usr/local/bin/
cd
```

## :computer: Instalaci�n en una L�nea
```bash
wget https://raw.githubusercontent.com/AAAAAEXQOSyIpN2JZ0ehUQ/Hacking-Wifi/refs/heads/main/install.sh -O - | sudo bash
```

## :rocket: Modo de Uso

Ejecutar el scrip:

```bash
hackingwifi
```

## :star2: Caracter�sticas y Funcionalidades Principales

1 - Comprobaci�n de Permisos de Root:

* El script verifica si se est� ejecutando con permisos de superusuario (root) y, en caso contrario, solicita que se ejecute con sudo.

2 - Actualizaci�n de Repositorios y Paquetes:

* Opci�n para actualizar los repositorios (apt-get update).
* Opci�n para actualizar los paquetes instalados (apt-get full-upgrade).

3 - Instalaci�n de Controladores de Red:

* Instalaci�n de controladores espec�ficos para adaptadores de red Realtek, como rtl8188eus, rtl8188fu, y opcionalmente rtl8814au-dkms.

4 - Configuraci�n de Controladores de Audio:

* Intenta configurar y activar los controladores de audio, asegurando la correcta funcionalidad del sonido en el sistema.

5 - Instalaci�n y Verificaci�n de Herramientas Esenciales y Opcionales:

* Verificaci�n e instalaci�n de herramientas esenciales como git, aircrack-ng, wifite, hcxdumptool, pyrit, airgeddon, fluxion, entre otras.
* Instalaci�n de herramientas adicionales como sparrow-wifi, feedingbottle, lazyaircrack, y Wifi-Hack, entre otras.

6 - Configuraci�n y Creaci�n de Diccionarios de Contrase�as:

* Creaci�n de un diccionario combinado a partir de m�ltiples fuentes de listas de contrase�as para usar en ataques de fuerza bruta.

7 - Mostrar Informaci�n del Sistema:

* Muestra la configuraci�n de red, interfaces inal�mbricas, dispositivos USB y capacidades inal�mbricas del sistema.

## :hammer_and_wrench: Requisitos 
-  Sistema Operativo: Kali Linux/Unix

Este script es una herramienta poderosa para cualquier profesional de la seguridad 
inform�tica que utilice Kali Linux, ya que simplifica y automatiza muchas de las 
tareas comunes de configuraci�n y actualizaci�n necesarias para una auditor�as de redes wifi y pruebas de penetraci�n.

## :open_file_folder: Estructura del Repositorio

| Icono            | Nombre              | Descripci�n                               |
|------------------|---------------------|-------------------------------------------|
| :file_folder:    | Desarrollador       | Carpeta de Desarrollador del proyecto     |
| :file_folder:    | Herramientas        | Carpeta de herramientas extras            |
| :file_folder:    | Im�genes            | Carpeta para im�genes del proyecto        |
| :page_facing_up: | .gitattributes      | Archivo para configuraci�n de Git         |
| :page_facing_up: | LICENSE             | Archivo de licencia del proyecto          |
| :book:           | README.md           | Archivo de documentaci�n principal        |
| :package:        | install.sh          | Script de instalaci�n automatizada        |
| :page_facing_up: | menu.sh             | Herramienta de utilidades                 |

## :star2: Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar este script o encuentras alg�n problema, si�ntete libre de abrir un *pull request* o *issue*.

## :warning: Advertencias

- Uso Responsable: Este script est� dise�ado para ser utilizado en dispositivos y redes que te pertenecen o para las que tienes permiso de uso. No lo utilices para actividades no autorizadas.

## :email: Contacto 
* :busts_in_silhouette: **Dzhoni**: [GitHub](https://github.com/AAAAAEXQOSyIpN2JZ0ehUQ/Hacking-Wifi) - Desarrollador Hacking-Wifi

? https://t.me/AAAAAEXQOSyIpN2JZ0ehUQ [  ???? ] ?
