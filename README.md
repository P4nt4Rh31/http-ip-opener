Este proyecto consiste en un script en Python diseñado para automatizar la apertura de múltiples direcciones IP en un navegador web utilizando un puerto especificado por el usuario. Esta herramienta es particularmente útil en el contexto de pruebas de penetración (pentesting), donde es necesario verificar rápidamente la accesibilidad y respuesta de múltiples direcciones IP a través de diferentes puertos. El script utiliza tkinter para proporcionar una interfaz gráfica de usuario (GUI) y webbrowser para abrir las URLs en el navegador predeterminado.

Características

Interfaz Gráfica de Usuario (GUI): Facilita la entrada del puerto TCP y la interacción del usuario.
Lectura de Direcciones IP desde un Archivo: Las IPs se leen desde un archivo de texto (ips.txt) que contiene una dirección IP por línea, simplificando la gestión de grandes listas de IPs.
Apertura de URLs Automatizada: Dependiendo del puerto ingresado, el script abre las URLs en HTTP o HTTPS en el navegador web predeterminado.

Paso 1: Clonar el Repositorio git clone https://github.com/P4nt4Rh31/http-ip-opener.git

Paso 2: Navegar al Directorio del Proyecto cd http-ip-opener

Paso 3: Crear el Archivo ips.txt nano ips.txt

Guarda y cierra el archivo presionando Ctrl+O, Enter, y Ctrl+X.

Paso 4: Ejecutar el Script python abrir_ips.py

Ingresar el Puerto TCP

Script created by Arturo Correa 'P4nth4_R31'

============================================================================================================

This project consists of a Python script designed to automate the opening of multiple IP addresses in a web browser using a user-specified port. This tool is particularly useful in the context of penetration testing (pentesting), where it is necessary to quickly verify the reachability and response of multiple IP addresses through different ports. The script uses tkinter to provide a graphical user interface (GUI) and webbrowser to open the URLs in the default browser.

Characteristics

Graphical User Interface (GUI): Facilitates TCP port entry and user interaction.
Reading IP Addresses from a File: IPs are read from a text file (ips.txt) that contains one IP address per line, simplifying the management of large lists of IPs.
Automated URL Opening: Depending on the port entered, the script opens URLs in HTTP or HTTPS in the default web browser.

Step 1: Clone the Repository git clone https://github.com/P4nt4Rh31/http-ip-opener.git

Step 2: Navigate to the Project Directory cd http-ip-opener

Step 3: Create the ips.txt file nano ips.txt

Save and close the file by pressing Ctrl+O, Enter, and Ctrl+X.

Step 4: Run the python script abre_ips.py

Enter the TCP Port

Script created by Arturo Correa 'P4nth4_R31'
