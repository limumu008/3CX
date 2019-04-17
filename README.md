# 3CX
Install, configure firewall, configure Trunk

3CX Academy https://www.3cx.com/3cxacademy/videos/basic/

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
801. Configure WindowsApp for 3CX
* Go setting -> Configure Accounts -> Choose account -> Configure credentials extension/ID/Password(If it's not new, just choose the one in the 3CX Phone System Management Console.)

900. Voip---Voice over Internet Protocol(SIP Trunk)

Steps are in here. https://www.3cx.com/docs/voip-ms-canadian-sip-trunk/

https://voip.ms/m/accountinfo.php#
* Finances -> Add Funds
* Main Menu -> Account Settings -> Inbound Settings -> Apply SIP and IP PBX Server.
* DID numbers -> Order DID -> Manage DID and make sure the routing points to SIP/IAX and main account

Configuring Trunk with 3CX 
* Adding Trunk -> Country: CA, Provider: VoIP.ms, Main Truck-No.
* General -> Registrar: [Check 3CX VoIP.ms Configuration Guide] -> Authentication ID: SIP User ID and Password.

999. Trouble Shooting
* If the ip address and FQDN doesn't work, just go to Services -> Running 3CX PhoneSystem Nginx Server.
