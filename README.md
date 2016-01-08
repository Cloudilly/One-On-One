#OneOnOne for iOS ObjC SDK
Repository contains sample codes required to build a private chat application using Cloudilly iOS ObjC SDK.

![Public](https://github.com/Cloudilly/Images/blob/master/ios_oneonone.png) 

---

#####Create app
If you have not already done so, first create an account on [Cloudilly](https://cloudilly.com). Next create an app with a unique app identifier and a cool name. Once done, you should arrive at the app page with all the access keys for the different platforms. Under iOS SDK, you will find the parameters required for your Cloudilly application. _"Access"_ refers to the access keys to be embedded in the ObjC codes. _"Bundle ID"_ can be found inside xCode project under _Targets_ >> _General_ >> _Identity_. Leave the _"APNS"_ for now. This sample project doesn't require APNS push notifications

![iOS Console](https://github.com/cloudilly/images/blob/master/ios_console.png)

#####Update Access
[Insert your _"App Name"_ and _"Access"_](../../blob/master/anonymous/ViewController.m#L21-L22). Once done, build and run the application. Open up developer console to verify connection to Cloudilly. If you have setup the anonymous chat app for other platforms, you should also test if you can send messages across platforms, ie from iOS to Web / Android and vice versa.
