# DSL2750UModemRestart
Restart the Dlink DSL-2750U Modem/Router via Shell

# Using cURL

```
curl -d 'saveCurAndReboot=Save%and%reboot&submit.htm?reboot.htm=Send' http://username:password@192.168.1.1/form2RebootOrReset.cgi
```
Replace the username and password with your modems credentials, by default the username and password is admin.

# Shell Script
First, Download the file
```
curl -O https://raw.githubusercontent.com/theamitjoseph/DSL2750UModemRestart/master/restartmodem.sh
```
Then change the username and password
```
$ chmod 755 restartmodem.sh
$ ./restartmodem
```
