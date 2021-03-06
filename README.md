ENSwiftSideMenu
===============

A simple side menu for iOS 8 written in Swift language. Using UIDynamics, UIGestures and UIBlurEffect.

##Demo
![](http://i.imgur.com/U5gvMTN.gif)

##Requirements
* Xcode 6
* iOS 8

##How to use
1. Import `SideMenu.swift` and `MenuTableViewController.swift` to your project folder
2. Set your view controller responds to `SideMenuDelegate` protocol
3. Implement `sideMenuDidSelectItemAtIndex(index: Int)` function in view controller
4. Initilize the menu with source view and menu item titles:
```swift
  sideMenu = SideMenu(sourceView: self.view, menuData: ["UIDynamics", "UIGestures", "UIBlurEffect"])
```
Customize menu table view cells in `MenuTableViewController.swift`
