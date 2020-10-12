
![Project By Elwood Berry](https://elwoodberry.dev/wp-content/uploads/2020/10/elwoodberry_logo.png)

# Work Log
In this file I will document all tasks (completed/uncompleted).

### 2020.10.01


**Added icons and splash screen**

01 - Build the project.
```
$ ionic build
```
Error: Alpha
> Cannot find module '@angular-devkit/build-angular/package.json'
```
$ npm install --save-dev @angular-devkit/build-angular
```

02 - Add IOS to the project.
```
$ ionic add cap ios
```
Error: Bravo
> [error] Analyzing dependencies
> An error occurred while running subprocess capacitor.

03 - Open the project in xCode.
```
$ ionic cap open ios
```

04 - Run the app in xCode emulator
Error: Charlie
> Must have a valid Apple ID.

Error: Delta
> Failed to create provisioning profile. The app ID "io.ionic.starter" cannot be registered....
> No profiles for 'io.ionic.starter' were found
```
Bundle Identifier: zyriel.alpha
```

Error: Echo
> error: SWIFT_VERSION '5.0' is unsupported, supported versions are: 3.0, 4.0, 4.2. (in target 'App')

**References**
1. [Generate using Capacitor](https://medium.com/@dalezak/generate-app-icon-and-splash-screen-images-for-ionic-framework-using-capacitor-e1f8c6ef0fd4)
---
