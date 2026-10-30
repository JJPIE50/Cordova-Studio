# Cordova Studio

A simpler desktop workspace for building Cordova apps
Cordova Studio brings all the mundane bits of a Cordova project into one desktop app. Rather than having to remember every command in Terminal or PowerShell you can create a project, update one you already have, manage your web files and app settings and kick off a build all from the same place.

Start fresh, or pick up where you left off
Create a new Android or iOS project or open an existing Cordova folder. When you open a project Cordova Studio looks at the files to determine which platform it is and then loads in the app details and icon where they're available.

Bring your web app files together
Add an HTML page, stylesheets, JavaScript files and images to the project. The HTML page you select is placed in Cordova's expected www/index.html location (regardless of what you actually name the file). You can also choose which web asset types you'd like to exclude when creating or updating the project.

Set up the app the way you need it
Set the app name, version and package ID, pick an icon and set your options (orientation, fullscreen etc). You can optionally enable a range of capabilities via Cordova plugins (camera, geolocation, motion, file access, network status, push notifications and biometrics). These will require the appropriate permissions and potentially some setup in the target project.

Build from the same workspace
For Android you can use Cordova Studio to kick off an APK or AAB build. On macOS you can also use it to kick off an iOS IPA build. There's a build page which keeps the progress, the percentage, the terminal output and the location of the resulting file all in one place so you can much more easily see what the tools are doing and where the finished package has gone.

Keep an eye on development tools
The dependency screen will check for tools that the selected workflow uses and show what is present and what is missing. It will not re-install any tools that it has already detected. A few of the toolchain components still come from the official vendors: Android builds require the Android SDK and a compatible Java JDK, iOS builds require Xcode, Apple signing credentials and a valid provisioning profile.

Works with normal Cordova projects
Cordova Studio is a front-end for the standard Cordova project structure and CLI. Your project is still a standard Cordova project that you can open up in your editor or work with from the command line. The Windows version is focused on Android workflows, the iOS project creation and IPA builds are available in the macOS version.

Cordova Studio — project setup, app settings and Cordova builds all in one place.
