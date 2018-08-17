# Freshchat Carthage


"Modern messaging software that your sales and customer engagement teams will love." Freshchat by Freshworks.

## Getting Started
Open your cart file Cartfile with the touch command via terminal: 
```
open -a Xcode Cartfile
```

Add Frreshchat's into your project and make sure to check latest version in relese section 

```
github "harishkumar-bits/FCCarthage" ~> 0.1.0
```

### Installation
Open your project folder, look for *Carthage* and then checkout to ```Carthage/Build/iOS```. 
Look for **FCCarthageSDK.framework** and add it into your project. 

Note : Please make sure you are adding FCCarthageSDK into Embedded Binaries.

### Add required resources

Freshchat requires 

**FCLocalization.bundle** - To localize Freshchat SDK

**FCResources.bundle** - Theme customization

Under root folder https://github.com/harishkumar-bits/FCCarthage/Resources download ```FCLocalization.bundle``` 
and ```FCResources.bundle``` and add them into your project.

### Initilization

Just add import statement ```#import <FCCarthageSDK/FCCarthageSDK.h>``` and you can access all Freshchat's API

Documentation - https://support.freshchat.com/support/solutions/articles/232945-freshchat-ios-sdk-integration

Theme Guide - https://support.freshchat.com/support/solutions/articles/229814-freshchat-ios-sdk-themes

Thats all :)

