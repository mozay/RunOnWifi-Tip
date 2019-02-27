# RunOnWifi-Tip
Running android app on wifi for Macos <br /> <br />

Steps for Mac : <br /> <br />

1-  touch ~/.bash_profile; open ~/.bash_profile <br />
2-  export PATH=$PATH:/Users/<your username>/Library/Android/sdk/platform-tools/ <br />
3-  adb tcpip 5555 (for adb tcpip mode restart) <br />
4-  adb connect <your device ip> <br />
5-  adb device <br />
