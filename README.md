Updated 01/26/25

I have created a fully turnkey ready to go VirtualBox VM OVA, with host OS, Docker and OpenCTI configured and installed!  This will  get you goinging quick with your own up to date OpenCTI instance with the most popular connectors!

The VM is loaded with Ubuntu 24.04 LTS Desktop with VBox guest additions.  I found the desktop is better for fixing network issues for users who use it and other usability improvements.   The newest version of Docker and Docker Compose installed, and OpenCTI 6.3.10 setup and running automatically, with all containers set to restart always. Once booted up, it will start to pull down more data soon as it is launched.

The username and password for the root user of Ubuntu are both "opencti".  The login creds for the OpenCTI admin, are "opencti@opencti.com" and the password "opencti".  The VM is set to use a bridged adapter and DHCP.  To find your IP address, pop a shell and do an "ip a" command.  Then visit the OpenCTI main login portal screen @ http://YOUR-IP:8080 . 
For more details and instructions for modification and changes, go to the "/home/opencti/OpenCTI sub-folder and read the "instructions.txt" file for more documentation.  
Click below to download the OVA file fast from one of our servers.


Download - https://mirrors.netmanageit.com/OpenCTI-6.3.10-NetmanageIT.ova


You can also visit our public read only instance of OpenCTI to do research, learn and play with the platform.  

https://opencti.netmanageit.com


OpenCTI LinkedIN howto files used in conjunction with the article links below

This repo contains the preconfigured example docker-compose.yml and .env file that goes with the OpenCTI howto article on both Dan Benders LinkedIN and CTO Corner Blog site.  

Links back to Blog - https://blog.netmanageit.com/opencti-installation-howto/
Link back to LinkedIN article - https://www.linkedin.com/pulse/opencti-installation-howto-daniel-bender/
