# discord-no-trackers
This is a project to remove (not disable or block) as many trackers as possible from the code of Discord's Android app.

# Trackers in the Discord app
App Manager reports 7 tracker components in the Discord app

![Trackers displayed by App Manager in Discord](https://media.discordapp.net/attachments/1205307121474998284/1230303559967445054/Screenshot_20240418-014656_App_Manager.png?ex=662ce5ba&is=662b943a&hm=4ff9f9487311bbcb3fd0f44d9c72e31147fbacac1278db64d8008852124e075b&=&format=webp&quality=lossless&width=306&height=680)

# About [Pyoncord](https://github.com/pyoncord/Bunny)
The root version of Pyoncord works perfectly, just install and enable it in LSPosed as usual.

The non root solution provided on their GitHub won't work because Vendetta Manager doesn't support picking an APK to patch. Patching it with LSPatch works and I provided the pre-patched APK in releases (Note:[ armeabi-v7a is not supported by Pyoncord](https://github.com/pyoncord/Bunny/issues/17)).
