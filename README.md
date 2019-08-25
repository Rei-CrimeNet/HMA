<div align="center">
  <br>
  <img width="200" height="100" alt="Logo" src="https://i.imgur.com/UZCjUj8.png" />
  <br>
  <br>
<a href="https://github.com/Rei-CrimeNet/HMA/tree/master/releases" target="_blank">
  <img height="50" weight="50" align="center" src="https://i.imgur.com/RlDlpnp.png"/>
</a>


  <br>
 <a href="https://www.youtube.com/channel/UCsN9VagvRj4sIKXoU5hVubg" target="_blank">
<img  height="30" weight="30" src="https://cdn.iconscout.com/icon/free/png-256/youtube-88-227910.png"/>
</a>   
  <br>
 </div>

![#DA70D6](https://placehold.it/15/b3b0b2/000000?text=+) `Released at 25.08.2019`  

**TS3 HideMyAss**  - release 3.3.1
=========
What is this?
---------
This is a TS3Client Plugin that decrypts Teamspeak 3 command packets on the fly and displays them in Teamspeak's own Console and other things too.

Features
---------
* Shows incoming/outgoing command packets of your client.
* Ability to hide certain commands to keep focusing on the important stuff.
* Ability to block certain outgoing commands to hide your connectioninfo for example.
* Ability to send own commands through your client.
* Ability to modify shown client version.
---------

> NOTE: You can also inject the DLL with the injector of the latest release.
---------
Injection
---------
Send a chat message with ~cmd and append a command where (spaces) are replaced with ~s.
Example:
```
~cmdsendtextmessage~stargetmode=2~smsg=hi
```
to send
```
sendtextmessage targetmode=2 msg=hi
```
