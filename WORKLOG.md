
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

**Solution: Delta**
```
Bundle Identifier: zyriel.alpha
```

Error: Echo
> error: SWIFT_VERSION '5.0' is unsupported, supported versions are: 3.0, 4.0, 4.2. (in target 'App')

**Solution: Echo**
```
Change the version of Swift for the "Pods" and the "App"
```

Error: Foxtrot
> Type 'UIStatusBarStyle' has no member 'darkContent'

**Solution: Foxtrot**
```
Currently updating from macOS High Sierra(10.13.6) to macOS Catalina(10.15.7)
This will allow for the update of xCode to version 12
```

**References**
1. [Capacitor](https://capacitorjs.com/)
1. [Splash Screen](https://capacitorjs.com/docs/apis/splash-screen#splash-screen)
3. [Unit Testing Your Ionic Framework App](https://youtu.be/RgD_tRXnxRo)
---
