# http_ip_opener

This project consists of a Python script designed to automate the opening of multiple IP addresses in a web browser using a user-specified port. This tool is particularly useful in the context of penetration testing (pentesting), where it is necessary to quickly verify the reachability and response of multiple IP addresses through different ports. The script uses tkinter to provide a graphical user interface (GUI) and webbrowser to open the URLs in the default browser.

Characteristics

Graphical User Interface (GUI): Facilitates TCP port entry and user interaction.
Reading IP Addresses from a File: IPs are read from a text file (ips.txt) that contains one IP address per line, simplifying the management of large lists of IPs.
Automated URL Opening: Depending on the port entered, the script opens URLs in HTTP or HTTPS in the default web browser.

Step 1: Clone the Repository git clone https://github.com/P4nt4Rh31/http-ip-opener.git

Step 2: Navigate to the Project Directory cd http-ip-opener

Step 3: Create the ips.txt file nano ips.txt

Save and close the file by pressing Ctrl+O, Enter, and Ctrl+X.

Step 4: Run the python script http_ip_opener.py

Enter the TCP Port

Script created by Arturo Correa 'P4nth4_R31'
