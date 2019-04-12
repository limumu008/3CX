# 3CX
Install, configure firewall, configure Trunk
1. Installation
* Download 3CX from https://www.3cx.com/phone-system/download-links/ (e.g Windows Version).
* Enter a license key(40 days free trail).
* Fill out all the information.(Subdomain, PBX Default Ports-Private Branch Exchange, Internal IP or FQDN-Fully Qualified Domain Name, Extension Length, etc.)
* Once done all the info, the 3CX installation is ready. Open a browser by putting FQDN into.
* Manage Extension-> Click the first one-> Send a welcome email.
2. Configuring the Firewall
* Configure SonicWall Firewall --> https://www.3cx.com/docs/sonicwall-firewall-configuration/


800. Configure Yealink T46S phone for 3CX

https://www.3cx.com/sip-phones/yealink-t4-series/
* Upgrade to the required firmware. Download the lastest required firmware https://www.3cx.com/support/phone-firmwares/.
* Check firmware version and upgrade https://www.3cx.com/sip-phones/firmware-update-yealink/
* Go to ip address, put user name and password.
* Go to settings -> upgrade -> choose the latest firmware and upgrade -> wait for 5 mins.
* Factory Reset -> hold ok button on the phone -> click yes for factory reset.
* Provision the phone -> Management Console -> Phone -> click new phone -> add Ext or assign Ext -> IP phone Setting -> Local LAN
900. Voip---Voice over Internet Protocol(SIP Trunk)


999. Trouble Shooting
* If the ip address and FQDN doesn't work, just go to Services -> Running 3CX PhoneSystem Nginx Server.
