# Windows2019RDP-AP
Windows Server 2019 Github with RDP Access (ngrok AP)

Tutorial Create RDP/VPS Windows Free: https://youtu.be/VnEJv49oKR8

View code: https://github.com/tinhocthuchanh2022/RDPwindows2019

Create Free VPS/RDP: 2CPU ; 7GB RAM with Github:

- Step 1: Create account on https://ngrok.com/ and https://github.com
- Step 2: Visit https://dashboard.ngrok.com to get NGROK_AUTH_TOKEN
- Step 3: Click on Fork in the right corner of the screen to save to your Github.
- Step 4: Settings > Secrets > New repository secret
 + Name: NGROK_AUTH_TOKEN
 + Value: Paste Your Authtoken -> Visit https://dashboard.ngrok.com/auth/your-authtoken
- Step 4: Add secret
- Step 5: Action > RDP-Windows > Run workflow
- Step 6: Connect To Your RDP
 + IP: 0.tcp.ap.ngrok.io:port
 + Username: administrator
 + Password: THTH-channel
- Done!!! 


