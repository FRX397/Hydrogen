- Download hydrogen (client.apk) through this link :
 https://linkvertise.com/514008/hydrogen-download/1

----------

- YouTube video tutorial :

https://youtu.be/sMwPbtp7GSo

----------

- Source for more info :

https://beebom.com/how-sideload-android-apps-chromebook/?

----------

sudo apt-get install android-tools-adb -y

adb connect 100.115.92.2:5555

adb install “filename.apk”

- If you are getting an error saying “more than one device/emulator”

```Run this command: adb -s emulator-5554 install filename.apk```

--------

- “Permission Denied” or “Command Not Found”

```Run this command: adb start-server 
And do the command again “adb connect 100.115.92.2:5555”```

--------

- If it tells you to “kill the server”

```Run the command adb kill-server
Then close out of the terminal, open it back up and repeat the command again```

--------

- No such file or directory

```Double check the file is in your linux files, and compare the command to the file name to make sure it's the same name```