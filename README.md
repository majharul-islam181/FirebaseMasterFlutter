# firebase_master_flutter


1️⃣ First run this command: 

```
npm install -g firebase-tools
```

npm install -g firebase-tools is used to globally install the Firebase CLI (Command Line Interface) tools on your machine. This command enables developers to interact with Firebase services directly from the terminal.

2️⃣ Then : 

```
firebase login
```
It will show some permission Like : Allow Firebase to collect CLI and Emulator Suite usage and error reporting information?  Yes.

After accepting all information : 
Success! Logged in as majharul.workplace@gmail.com

3️⃣ Then : 
```
flutter pub global activate flutterfire_cli
```
**The command (`flutter pub global activate flutterfire_cli`) is used to globally activate the `flutterfire_cli` tool, which is part of the FlutterFire ecosystem. This tool simplifies the process of integrating Firebase services into your Flutter app.**

**Reasons for using flutterfire_cli:**

*(`Simplified Firebase Integration:`)*

 Automatically configures your Flutter app to use Firebase services.

 Generates the necessary Firebase configuration files (google-services.json for Android, GoogleService-Info.plist for iOS).`)*
 

*(`Multi-platform Support:`)*

Supports Firebase configuration for multiple platforms (Android, iOS, web, macOS).

Ensures consistent setup across different platforms.

*(`Firebase Project Management:`)*

Assists in linking your Flutter app to a Firebase project.

Helps in setting up Firebase services such as *`Authentication`*, *`Firestore`*, *`Realtime Database`*, *`Cloud Functions`*, and more.
Ease of Use:

 *`Reduces the manual steps needed to integrate Firebase`* , especially when managing multiple Firebase projects or environments.
Provides a streamlined command-line interface to manage Firebase configurations.

```Warning: Pub installs executables into C:\Users\User\AppData\Local\Pub\Cache\bin, which is not on your path.
You can fix that by adding that directory to your system's "Path" environment variable.
A web search for "configure windows path" will show you how.
Activated flutterfire_cli 1.0.0.
```
*`solution: `*

go to environment variable set  *`C:\Users\User\AppData\Local\Pub\Cache\bin`* this path to system variables

``` 
flutterfire --version
```
4️⃣ Then: 
```
flutterfire configure
```
if any issues found then check again C:\Users\User\AppData\Local\Pub\Cache\bin, and check flutterfire.bat file available or not.
```
C:\Users\User\AppData\Local\Pub\Cache\bin\flutterfire.bat --version
 ```

if available the run 

```
C:\Users\User\AppData\Local\Pub\Cache\bin\flutterfire.bat configure
 ```

5️⃣ Then
```
flutterfire configure
```
then it will show like: 
*`? Which platforms would you like to configure? (Use arrow keys)
  [ ] Android
  [ ] iOS
`*

Select the platfrom and if they want package name: com.example.firebase_master_flutter

*After that fireabse will successfully added with your project*












