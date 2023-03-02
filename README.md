<!--
Developer: Programming Wormhole
Author: Md Shirajul Islam
Github: htts://github.com/programmingwormhole
-->
<p align="center">
   <img src="https://i.ibb.co/z2C207P/New-Project.jpg" alt="Navigation Bar By Programming Wormhole" />
</p>

<div align="center">

## 🌐 Socials:
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/no.name.virus) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/shirajul_dev) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/md-shirajul-islam) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?logo=Twitter&logoColor=white)](https://twitter.com/shirajul_dev) [![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?logo=YouTube&logoColor=white)](https://youtube.com/@programmingwormhole)
</div>
<hr>

## How to use?

Add `flutter_navbar_pro:` to your `pubspec.yaml` dependencies then run `flutter pub get`


Add from pub [Stable]

```yaml
 dependencies:
  flutter_navbar_pro:
```

Then import the package to use

```dart 
import 'package:flutter_navbar_pro/flutter_navbar_pro.dart';
```

Add `FlutterNavBarPro()` to `bottomNavigationBar` property of `Scaffold()`.


## Design Overview

[I just inspired From This Bar (MyGp App)](https://camo.githubusercontent.com/891dbb2f88f1afe9eca0361dd9cca7b28d34c1781b3f2c5e95b6ffd330d6e0f8/68747470733a2f2f692e706f7374696d672e63632f6430636b683348502f312e6a7067)

<img src="https://i.ibb.co/zfLvD8V/Simulator-Screen-Shot-i-Phone-14-Pro-Max-2023-03-03-at-00-53-50.png"  width="280"/>


### **Do and don't**
- Don't make icon size too big.
    - Don't use label text too long

## How to use it
- ### For Navigation Bar Code Example
Past it inside scaffold
 ```dart
 bottomNavigationBar: FlutterNavBarPro(
          iconFirst: Icons.home,
          labelFirst: 'Home',
          iconSecond: Icons.local_offer_outlined,
          labelSecond: 'Offers',
          iconThree: Icons.person,
          labelThree: 'Account',
          iconFour: Icons.menu,
          labelFour: 'More',
          labelMiddle: 'Explore',
        ),
 ```
>>1. Here we just typed our IconData. The package already done all modification for you.
     >> So just type the IconData only. (eg: Icons.name)
>> 2. And for icon label you can't able to use any wiget under the under '' codeation you have to type your label text and the package already done all modification for you.

- ### How to use the center icon?
Past it inside scaffold
```dart
floatingActionButton: FloatingBarPro(
          middleBGColor: Colors.white,
          imageData: 'assets/images/explore.png',
        ),
        floatingActionButtonLocation: FloatingActionButtonLocation.centerDocked,
```
>> Here in imageData you have a past your own image icon path.
- ### How to change image to icon? .

>> 1. Hold on the ctrl button and click on FlutterNavBarPro()
>> 2. And comment of delete 123-125 no line codes.
>> 3. and past one line of codes here
```dart
child: Icon(Icons.access_time_filled_rounded),
```
>> Here just change the IconData with yours

<br>

[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/shirajul_dev) 
