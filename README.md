# PathToMath

An app for pre-school children to learn basic math operations used by the Department of Psychology at University of Illinois at Urbana-Champaign.

![launchimage](https://cloud.githubusercontent.com/assets/5849363/10687933/460423f6-7936-11e5-932a-9b28eb013a00.png)
![screenshot1](https://cloud.githubusercontent.com/assets/5849363/10687911/240791e8-7936-11e5-9292-837912fee320.PNG)
![screenshot2](https://cloud.githubusercontent.com/assets/5849363/10687914/28b42ab2-7936-11e5-9da8-8fea0b18accb.PNG)


## Project Setup

PathToMath requires iOS 8. 


- Install project dependencies using [CocoaPods](http://cocoapods.org/#install). 

````
cd PathToMath-iOS
pod install
````

- Open the Xcode workspace at `PathToMath-iOS/PathToMath.xcworkspace`.

- Create your PathToMath App on [Parse](https://parse.com/apps).

- Copy your new app's application id and client key into `AppDelegate.swift`.

````swift
Parse.setApplicationId("APPLICATION_ID", clientKey: "CLIENT_KEY")
````
