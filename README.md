# CMD_Challenge

### Windows
C:\Users>
Check cache connection of wireless lan 
```
netsh wlan show profile name="tanapark_107" key=clear | findstr "SSID name Key content"
```
Just show SSID and Password
