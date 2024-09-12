---
layout: aws_page
permalink: /AWS_setup_Windows
title: AWS Setup Windows
header1: Workshop Pages for Students
header2: AWS Setup Windows
image: /site_images/Bioinfo_Logo.jpg
home: https://bioinformaticsdotca.github.io/
---

### Logging into the Amazon Cloud During the Workshop  


* These instructions will **ONLY** be relevant in class, as the Cloud will not be accessible from home in advance of the class.
 

### Windows Log in (Remote Desktop Connection) <a id="windows"></a>

* Press the Windows key and type “Remote Desktop” into the search bar and click "Remote Desktop Connection" OR Press Win + R to open the Run dialog and type **mstsc** and press Enter.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/win_remote_desktop_connection.jpg?raw=true" alt="win_remote_desktop_connection" width="50%">
* Click "Show Options". In the <B>Computer</B> field, enter your hostname ("xx.uhn-hpc.ca" where xx is your student number). Use <B>cbw</B> as your <B>User Name</B>.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/win_remote_desktop_connection_host.jpg?raw=true" alt="win_remote_desktop_connection_host" width="50%">
* Click "Local Resources" tab and click "More..." button.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/win_remote_desktop_connection_local.jpg?raw=true" alt="win_remote_desktop_connection_local" width="50%">
* Check the drive you want to see in your cloud instance like C: drive. You will be able to transfer files between your local machine and the cloud instance.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/win_remote_desktop_connection_C.jpg?raw=true" alt="win_remote_desktop_connection_C" width="50%">
* Click "OK" and then "Connect". Use the password in the Slack chennel. You may see the following warnings. Click "Connect" or "Yes" to continue.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/win_remote_desktop_connection_warn1.jpg?raw=true" alt="win_remote_desktop_connection_C" width="40%">
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/win_remote_desktop_connection_warn2.jpg?raw=true" alt="win_remote_desktop_connection_C" width="40%">

### Mac Log in (Microsoft Remote Desktop) <a id="mac"></a> 

* <B>Microsoft Remote Desktop</B> can be installed in <B>App Store</B> on your Mac.
* Launch <B>Microsoft Remote Desktop</B> from your Applications folder.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/mac_MRD.jpg?raw=true" alt="mac_remote_desktop" width="50%">
* In the Microsoft Remote Desktop window, click the + button in the top bar and select "Add PC".  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/mac_MRD_add.jpg?raw=true" alt="mac_remote_desktop_add" width="50%">
* In the "PC name" field, enter your hostname ("xx.uhn-hpc.ca" where xx is your student number).  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/mac_MRD_info.jpg?raw=true" alt="mac_remote_desktop_info" width="50%">
* Click "Folders" tab and check "Redirect folders" then add the folders you want to share with your AWS instance. You will be able to transfer files between your folders and your AWS instance.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/mac_MRD_folders.jpg?raw=true" alt="mac_remote_desktop_folders" width="50%">
* Click "Add" and then double click the PC you just added. Use <b>cbw</b> as the Username and the password from Slack channel.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/mac_MRD_user.jpg?raw=true" alt="mac_remote_desktop_user" width="50%">
* Click "Continue" when you see the warning.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/mac_MRD_warn.jpg?raw=true" alt="mac_remote_desktop_warn" width="50%">

### Linux Log in (Remmina) <a id="mac"></a> 
* Follow the instructions at [Remmina web site](https://remmina.org/how-to-install-remmina/) to install Remmina and remmina-plugin-rdp.
* Launch remmina and click "+" to add a profile.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/linux_remmina.jpg?raw=true" alt="linux_remmina" width="50%">
* Fill in the following information:
  * Name: Profile name like CBW.
  * Protocol: Choose "RDP - Remote Desktop Protocol".
  * Server: your hostname ("xx.uhn-hpc.ca" where xx is your student number).
  * Username: <b>cbw</b>.
  * Password: the password from Slack channel.
  * Share folder: your local directory you want to share with your AWS instance. You will be able to transfer files between your local directory and your AWS instance.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/linux_remmina_add1.jpg?raw=true" alt="linux_remmina" width="50%">
* Click "Yes" when you see the warning.  
  <img src="https://github.com/bioinformaticsdotca/AWS_stuff/blob/master/linux_remmina_warn.jpg?raw=true" alt="linux_remmina_warn" width="50%">

