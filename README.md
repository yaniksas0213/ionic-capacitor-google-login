## GOAL

On top of the provided app (on `Github` repo), configure the `Capacitor` plugin:

https://github.com/CodetrixStudio/CapacitorGoogleAuth.

So the app can login with `Google`. Then, when clicking the button: `Login with Google` the `Google` token will show up.

![image](https://drive.google.com/uc?id=1Jex73MFTTZg5dJdrTHKMhBQSuoSs3t50)

Please, configure a dummy app on your own `Google` account. When everything is working properly, please, provide also the configuration you used so we can do the same on our own `Google` account.

## Useful Commands

The provided project was generated with:

```
$ ionic start ionic-capacitor-google-login sidemenu --type=react --capacitor
$ ionic capacitor add android
```

**Requirements:**

```
You need to have Android Studio installed on your system.

$ choco install androidstudio
```

**To run the project:**

```
$ DEV_PC_IP_ADDRESS=192.168.1.220 # Windows (use your own IP address)
$ npm run build && ionic capacitor run android -l --address=$DEV_PC_IP_ADDRESS

[Android Studio will open. Then click "Run" button]
```

## Google Setup

```
https://console.developers.google.com/apis/credentials
https://console.developers.google.com/apis/credentials?project=<project-name>
Maybe it is necessary to enable Google+ API at:
https://console.developers.google.com/apis/library/plus.googleapis.com
```
