# UIButton+Game
**UIButton+Game** is a UIButton extension that makes it easy to animate a button with either a 

Pre-requisites
--------------
- iOS 8 and Swift 2

Installation
------------

There are two ways to use **UIButton+Game** in your project:
- using CocoaPods
- copying all the files into your project

### Installation with CocoaPods

[CocoaPods](http://cocoapods.org/) is a dependency manager, which automates and simplifies the process of using 3rd-party libraries in your projects. See the [Get Started](http://cocoapods.org/#get_started) section for more details.

### Podfile
```
pod 'BLJGameButton'

```

### Copying files into project
```
UIButton+Game.swift

```  
# Basic usage

## 1. Import
```swift

#import "BLJGameButton.h"
```
## 2. Implement
```swift
UIButton *gameButton = [UIButton new];

gameButton.correct { () -> () in
	//Do something following animation
}

gameButton.incorrect { () -> () in
	//Do something following animation
}

```

License
---------------
This project is released under the MIT license. See LICENSE for details.
