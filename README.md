# Hikivision-backdoor-scanner-snapshot-saver

Effects Hikvision IP Camera versions 5.2.0 - 5.3.9 (Builds 140721 < 170109)

reference:

• https://www.exploit-db.com/exploits/44328

Uses the backdoor auth key "auth=YWRtaW46MTEK" put in place by hikvision support to remotely fix and reset customers camera's

Ex : http://SERVER/onvif-http/snapshot?auth=YWRtaW46MTEK


Uses hikvision backdoor to bypass auth and view live snapshot of camera

To save vulnerable devices, paste your camera IP's in Server.txt and run main.py

To save live snapshots of saved devices, run snapshot.py

