# apm
Android Package Manager is designed to download and install apk as easily as apt using adb.
The repository feature allows you to add multiple repositories to get more apks.

Download repo.ini and place it in the same directory as apm.
Please put the apm in the same folder as the platformTool (adb, etc.)
It doesn't work properly.
Run it from the command line

## How to create a repository
Create a store.ini in your server
[repo].
(application name) = (direct URL to apk)

Write this as a reference
Please allow bot access from the server, or you will get a 403 error.
## How to add repository to APM
apm add-repo (URL of the repository)
Please type
You will be asked for the name of the repository.
Now you are done!
##How to install APK
Type apm apps and enter the name of the app in the output.

apm install (app name)
##How to uninstall
apm uninstall (package name)
Uninstall with
However, the package name is in the form of com.example.app.
##About Reboot Bootloader Recovery
As the name suggests, Reboot is a reboot.
Bootloader starts Bootloader after reboot (Fastboot is also available)
Recovery will launch recovery (e.g. TWRP)


## レポジトリの作成の仕方
サーバー内にstore.iniを作成します
[repo]
(アプリケーション名) = (apkへのダイレクトURL)

これを参考に記述してください
サーバーからはbotのアクセスを許可してください でないと403エラーが出ます
## レポジトリのAPMへの追加の方法
apm add-repo (レポジトリのURL)
と入力してください
するとレポジトリの名前を求められますので入力してください
これにて追加は完了です
##APKのインストール方法
apm appsと入力し出力されたアプリ名を入力します

apm install (アプリ名)
## アンインストールの方法
apm uninstall (パッケージ名)
でアンインストール
ただしパッケージ名はcom.example.appのような形式になっております
## Reboot Bootloader Recoveryについて
その名の通りRebootは再起動
Bootloaderは再起動後にBootloaderを起動(Fastbootの場合もあります)
Recoveryはリカバリーを起動します(TWRPなど)
