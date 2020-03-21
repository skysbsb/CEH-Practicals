# CEH-Practicals
# Msfconsole Fix
Start PostGreSQL: # systemctl restart postgresql
Make sure it is working properly: # systemctl status postgresql
Now you should be listening on ports 5432 & 5433: # ss -ant
Reinitialize DB Settings (user, config files, msfdb): # msfdb reinit
Finally, launch MSF: # msfconsole



sudo ruby wpscan.rb -u http://127.0.0.1/wordpress/ --log --proxy socks5://127.0.0.1:9050 --enumerat
e u -w ../Downloads/common.txt
