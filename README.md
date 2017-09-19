<p align="center">
  <img src="https://github.com/KeenTeam1990/KTKeyborad/master/Demo/Resources/icon.png" alt="Icon"/>
</p>
<H1 align="center">KTKeyboardManager</H1>

Often while developing an app, We ran into an issues where the iPhone keyboard slide up and cover the `UITextField/UITextView`. `KTKeyboardManager` allows you to prevent issues of the keyboard sliding up and cover `UITextField/UITextView` without needing you to enter any code and no additional setup required. To use `KTKeyboardManager` you simply need to add source files to your project.

#### Key Features

1) `**CODELESS**, Zero Lines Of Code`

2) `Works Automatically`

3) `No More UIScrollView`

4) `No More Subclasses`

5) `No More Manual Work`

6) `No More #imports`

`KTKeyboardManager` works on all orientations, and with the toolbar. There are also nice optional features allowing you to customize the distance from the text field, add the next/previous done button as a keyboard UIToolbar, play sounds when the user navigations through the form and more.


## Screenshot
[![KTKeyboardManager](https://github.com/KeenTeam1990/KTKeyborad.git/v3.3.0/Screenshot/IQKeyboardManagerScreenshot.png)](http://youtu.be/6nhLw6hju2A)
[![Settings](https://github.com/KeenTeam1990/KTKeyborad.git/v3.3.0/Screenshot/IQKeyboardManagerSettings.png)](http://youtu.be/6nhLw6hju2A)

## GIF animation
[![KTKeyboardManager](https://github.com/KeenTeam1990/KTKeyborad.git/v3.3.0/Screenshot/IQKeyboardManager.gif)](http://youtu.be/6nhLw6hju2A)

## Video

<a href="http://youtu.be/WAYc2Qj-OQg" target="_blank"><img src="http://img.youtube.com/vi/WAYc2Qj-OQg/0.jpg"
alt="IQKeyboardManager Demo Video" width="480" height="360" border="10" /></a>

## Warning

- **If you're planning to build SDK/library/framework and wants to handle UITextField/UITextView with IQKeyboardManager then you're totally going on wrong way.** I would never suggest to add IQKeyboardManager as dependency/adding/shipping with any third-party library, instead of adding IQKeyboardManager you should implement your custom solution to achieve same result. IQKeyboardManager is totally designed for projects to help developers for their convenience, it's not designed for adding/dependency/shipping with any third-party library, because **doing this could block adoption by other developers for their projects as well(who are not using IQKeyboardManager and implemented their custom solution to handle UITextField/UITextView thought the project).**
- If IQKeybaordManager conflicts with other third-party library, then it's developer responsibility to enable/disable IQKeyboardManager when presenting/dismissing third-party library UI. Third-party libraries are not responsible to handle IQKeyboardManager.

## Requirements
[![Platform iOS](https://img.shields.io/badge/Platform-iOS-blue.svg?style=fla)]()

#### IQKeyboardManager:-
[![Objective-c](https://img.shields.io/badge/Language-Objective C-blue.svg?style=flat)](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)

Minimum iOS Target: iOS 8.0

Minimum Xcode Version: Xcode 6.0.1

#### IQKeyboardManagerSwift:-
[![Swift 3.1 compatible](https://img.shields.io/badge/Language-Swift3-blue.svg?style=flat)](https://developer.apple.com/swift)

Minimum iOS Target: iOS 8.0

Minimum Xcode Version: Xcode 8.0

#### Demo Project:-

Minimum Xcode Version: Xcode 8.3.2


Installation
==========================

In AppDelegate.swift, just import KTKeyboardManagerSwift framework and enable IQKeyboardManager.

```swift
import KTKeyboardManagerSwift

@UIApplicationMain
class AppDelegate: UIResponder, UIApplicationDelegate {

    var window: UIWindow?

    func application(application: UIApplication, didFinishLaunchingWithOptions launchOptions: [NSObject: AnyObject]?) -> Bool {

      KTKeyboardManager.sharedManager().enable = true

      return true
    }
}
```

#### Installation with Carthage

[Carthage](https://github.com/Carthage/Carthage) is a decentralized dependency manager that builds your dependencies and provides you with binary frameworks.

You can install Carthage with [Homebrew](http://brew.sh/) using the following command:

```bash
$ brew update
$ brew install carthage


#### Installation with Source Code:-


***KTKeyboardManager (Objective-C):-*** Just ***drag and drop*** `IQKeyboardManager` directory from demo project to your project. That's it.

***IQKeyboardManager (Swift):-*** ***Drag and drop*** `IQKeyboardManagerSwift` directory from demo project to your project

In AppDelegate.swift, just enable KTKeyboardManager.

```swift
@UIApplicationMain
class AppDelegate: UIResponder, UIApplicationDelegate {

    var window: UIWindow?

    func application(application: UIApplication, didFinishLaunchingWithOptions launchOptions: [NSObject: AnyObject]?) -> Bool {

      IQKeyboardManager.sharedManager().enable = true

      return true
    }
}

LICENSE
---
Distributed under the MIT License.

Contributions
---
Any contribution is more than welcome! You can contribute through pull requests and issues on GitHub.

Author
---
If you wish to contact me, email at: Keen_Team@163.com
