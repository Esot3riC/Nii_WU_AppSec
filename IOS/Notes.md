# IOS testing
- Language used to develop IOS apps are **Objective-C (old) & Swift(New)** . **Xcode** is IDE use for development
- iOS supports Armv8-A in iOS 7 and later on 64-bit Apple SoCs([Apple silicon](https://en.wikipedia.org/wiki/Apple_silicon), mainly using the **ARM architecture**). iOS 11 and later only supports 64-bit ARM processors and applications. IOS device come with [ARM architecture](https://intellipaat.com/blog/tutorial/ios-tutorial/ios-architecture/).
- implementatiosn (**.m**) file containes the business logic for IOS application 
- we can downgrade & [sign using objection](https://github.com/sensepost/objection/issues/428) the .ios application's minimum OS version in xCode

## Tools

#### Jailbreak IOS device
- UnCover + altstore
- Checkrain (MAC, Linux)
- 3uTools (base machine)

#### Jailbreak bypass:
- [Hestia](https://www.youtube.com/watch?v=4S8PluepMgw&ab_channel=BurhanRana)
- [Liberty lite](https://gowthamr1.medium.com/jailbreak-detection-bypass-using-libertylite-tweak-8b27d24f4125), [video](https://www.youtube.com/watch?v=8yWM25W6RVU&ab_channel=BurhanRana)
- [FlyJB](https://www.youtube.com/watch?v=gFs-J4ysX70&ab_channel=BurhanRana) Best tool

#### SSL pinning bypass:
- [SSL Kill Switch2](https://mukhilan.com/Ios/iso-ssl-bypass/)

#### Other important tools: 
- [X code Utilities](https://mac.install.guide/commandlinetools/index.html):- Command line tool in MACos
- iTunes
- IPA Installer ([Cydia Impactor](https://www.youtube.com/watch?v=WfLM109DudA&ab_channel=CydiaImpactor))
- Filza (Cydia):- IOS file manager 
- [sideloadly](https://sideloadly.io/):- Install .IPA file in IOS device from base machine
- [3uTools](https://www.youtube.com/watch?v=1ap1GvEKHjE&ab_channel=SaundersTech) (Install .IPA file in IOS device from base machine)
- SSH Server (Cydia)
- MobaXterm/Putty (window):- create SSH session with IOS device
- WinScp:- data transfer b/w IOS and base machine
-[NewTerm2](https://chariz.com/get/newterm)


#### Sign and install .IPA file using 3uTool:
1. create an Apple developer IDE
1. got the iPhone device UDID number from 3uTool or iTunes(connect iPhone with laptop)
1. go to 3uTool > toolbox > IPA signature
1. upload IPA and enter AppleID details 
1. follow link: https://www.3u.com/tutorial/articles/10212/how-to-use-ipa-signature
1. install IPA: go to 3uTool > iDevice > Apps > Import & install IPA


