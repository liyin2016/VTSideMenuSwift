# VTSideMenu
A simple SWift sideMenu lib for iOS
#Getting Started

**Using [CocoaPods](http://cocoapods.org)**

1.Add the pod `VTSideMenu` to your [Podfile](http://guides.cocoapods.org/using/the-podfile.html).
```ruby
pod 'VTSideMenu', '~> 1.0.0'
```
2.Run `pod install` from Terminal, then open your app's `.xcworkspace` file to launch Xcode.

3.`#import UIViewController+SideMenu.h` wherever you want to use the API.

**Manually from GitHub**

1.Download the `UIViewController+SideMenu.h` , `UIViewController+SideMenu.m` ,`VTSideMenuManager.h` , `VTSideMenuManager.m` files in th [Source directory](https://github.com/VincentDengSZ/VTSideMenu)  


2.Add the files to your Xcode project.

3.you don't need import any file if you use the api with Swift
#Example Usage

**Example location**

Check out the [example project](https://github.com/VincentDengSZ/VTSideMenuSwift/tree/master/VTSideMenuSwiftDemo) included in the repository. It contains a few demos of the API in use for various scenarios. 

**Usage**

The way to create a SideMenu is:


```Swift
VTSideMenuManager.initSideMenu(sideMenu: SideMenuViewController(), width: 250)
```
#License
MIT

