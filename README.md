This list comes from keeping track of what has been useful and not useful from
the past few years of learning iOS on my own. I'm compiling this to be a sort
of reference guide for the students in my upcoming class at [The Flatiron School](http://flatironschool.com/iOScurriculum.html "Flatiron School iOS Curriculum").

The goal here is for a student to achieve gradually increasing layers of quality. I recommend going
through the guide in order following the beginner tutorials first. Once you've
completed all of the beginner tutorials then go through it again hitting the
intermediate, and then advanced items.

If you have questions on any of the material, or think one of the items linked
isn't the best representation of a topic, raise an issue! If you have additions
you'd like to add send me a pull request.

Also get
[this](http://www.amazon.com/iOS-Programming-Ranch-Guides-ebook/dp/B007OWBAB0/ref=sr_1_1?s=books&ie=UTF8&qid=1375307739&sr=1-1&keywords=ios+programming+the+big+nerd+ranch+guide+3rd+edition) book. It's the Big Nerd Ranch book I reference throughout the
guide.


Basic iOS
=========

This will get you going to write super simple app. It's not going to look
pretty, but it'll work. After following the beginner tutorials you should be
able to make a super simple ToDo list app. Go ahead. Give it a try!

Beginner
--------

  - [Beginning Storyboard in iOS
    5](http://www.raywenderlich.com/5138/beginning-storyboards-in-ios-5-part-1 "Beginning Storyboards in iOS 5")
  - Big Nerd Ranch Chapter 1
  - Big Nerd Ranch Chapter 3
  - Big Nerd Ranch Pages 85-86
  - Big Nerd Ranch Chapter pages 92-100

Advanced
---------
  - BNR Chapter 8

Objective-C
===========

Objective-C is the language of iOS and it is most likely pretty different than
what you've done before. To get started you just need a bit of knowledge of
Objective-C, but to really master iOS development you need to get a solid
understanding of the language. The best Rails developers are also the best Ruby
developers. The same is true in the Objective-C/iOS world.
Beginner
--------
 - [Objective C
Primer](http://developer.apple.com/library/mac/#referencelibrary/GettingStarted/Learning_Objective-C_A_Primer/index.html "Learning Objectiv-C: A Primer")
 - Big Nerd Ranch Chapter 2

Advanced
---------
  - Programming in Objective-C (5th Edition)
    - Yup it's an entire book on Objective-C. It's a great reference book and
      will make you an expert in Objective-C.
  - Big Nerd Ranch Chapter 27
  - [Programming With
    Objective-C](http://developer.apple.com/library/mac/#documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html
    "Programming With Objective-C")

XCode
=====
XCode is what you develop iOS apps in. A craftsman knows his/her tools. Make
sure you know yours.

Beginner
--------

  - [14 Essential Xcode Tips and
    Tricks](http://mobileorchard.com/14-essential-xcode-tips-tricks-and-resources-for-iphone-devs/)
  - [XVim](https://github.com/JugglerShu/XVim "XVim") - Make XCode more like
    Vim



Object Orientated Principles
=============

The iOS ecosystem relies heavily on a few Object Orientated principles. The
beginner items covers the stuff that is somewhat unique to iOS
Beginner
--------

  - [iOS Design Patterns:
    Delegation](http://blog.teamtreehouse.com/ios-design-patterns-delegation-part-2-2
    "iOS Design Patters: Delegations")
  - [Intro to
    Protocols](http://iosdevelopertips.com/cocoa/introduction-to-protocols.html "Intro to Protocols")

Advanced
--------

 - [Intro to Object Oriented
   Programming](http://www.appcoda.com/objective-c-object-oriented-programming-intro/ "Intro to Object Oriented Programming")
 - [OOP with
   Objective-C](http://developer.apple.com/library/ios/#documentation/Cocoa/Conceptual/OOP_ObjC/Introduction/Introduction.html#//apple_ref/doc/uid/TP40005149-CH1-SW2 "Object-Oriented Programming with Objective-C")
 - [Using Categories With Core
   Data](http://useyourloaf.com/blog/2010/03/23/using-categories-with-core-data.html "Using Categories with Core Data")
 - [Cocoa Design
    Fundementals](http://developer.apple.com/library/mac/#documentation/Cocoa/Conceptual/CocoaFundamentals/CocoaDesignPatterns/CocoaDesignPatterns.html#//apple_ref/doc/uid/TP40002974-CH6-SW6 "Cocoa Design Fundementals Website")

Core Data
=========

Core Data is a persistent data store. It is not a database. This is seriously
one of the most confusing technologies in the iOS ecosystem, but it is
something *you must learn*. I the integrating with APIs section you'll learn
even more about Core Data and how to save both locally and sync up to the
cloud. Think about all of the apps you use. Most of them can be boiled to down
to displaying some data that is synced to a service.
Beginner
--------

  - BNR Chapter 16
  - [Core Data Tutorial for iOS: Getting
    Started](http://www.raywenderlich.com/934/core-data-tutorial-for-ios-getting-started "Core Data Tutorial for iOS: Getting Started")
    - Make sure you read all three parts. The NSFetchedResultsController part
      is super important and how you connect Core Data to UITableViews.

Advanced
--------
  - [Pro Core Data for
    iOS](http://www.amazon.com/Pro-Core-Data-Second-Edition/dp/1430236566/ref=pd_sim_b_26 "Pro Core Data For iOS")
    - Told you it was a big topic.

Libraries
---------

  - [MagicalRecord](https://github.com/magicalpanda/MagicalRecord "Magical
    Record GitHub Page")


Reference
---------

  - [Core Data Quickie](http://borkware.com/quickies/one?topic=Core%20Data
    "Core Data Quickies")

Integrating with APIs and Social Media
=====================
Nothing exists in a vacuum. Apps are expected to share effortlessly and backup
to the cloud. The beginner section has some of the super simple stuff and is
all you really need to get started. Once you've figured out some of the built
in features of iOS and Helios, the intermediate section will show you how to
add custom sharing features as well as the basics of talking to custom APIs.

I'm purposefully exposing you to the native iOS SDK networking stack before
AFNetworking and the other libraries. It's *very* hard to debug problems with
the libraries if you don't understand the underlying technologies.



Beginner
--------

  - [Mattt Thompson: Build an iOS App in 20 Minutes with Rails and
    AFIncrementalStore](https://www.youtube.com/watch?v=8wrFn6flYdQ "Youtube
    Video of a Mattt Thompson Talk on using Helios")
  - [Integrate Twitter and Facebook Sharing in Your
    App](http://www.appcoda.com/ios-programming-101-integrate-twitter-and-facebook-sharing-in-ios-6/
    "Integrate Twitter and Facebook Sharing in Your App")

Intermediate
------------
  - [Subclassing
    UIActivity](http://blog.goosoftware.co.uk/2013/05/04/subclassing-uiactivity/ "Subclassing UIActivity Video")]
  - [Building an iOS app with AFIncrementalStore and Core Data Buildpack](https://devcenter.heroku.com/articles/ios-core-data-buildpack-app "Heroku Article on Core Data Buildpack") - This is the howto for Helios
  - BNR Chapter 25
  - BNR Chapter 28 (skip everything on designing an rss parser)
  - [Getting Started with the Facebook
    SDK](https://developers.facebook.com/docs/tutorials/ios-sdk-tutorial/show-friends/
    "Getting Started with the facebok SDK")
  - [Sharing Providers for UIActivity](http://uiactivities.com/ "UIActivities
    Home Page")]

Advanced
--------

  - BNR Chapter 29
  - [Developing RESTful Apps with
    RestKit](http://mobile.tutsplus.com/tutorials/iphone/restkit_ios-sdk/
    "Developing RESTful Apps With RestKit")
  - [Networking made easy with
    AFNetworking](http://mobile.tutsplus.com/tutorials/iphone/ios-sdk_afnetworking/)
  - [AFNetworking and
  Caching](http://cleveryou.net/post/51558182158/afnetworking-caching-guide)

Libraries
---------

  - [AFNetworking](https://github.com/AFNetworking/AFNetworking "AFNetworking
    Github Page")
  - [Helios](http://helios.io/ "Helios Home Page")
  - [RestKit](http://restkit.org/ "RestKit Home Page")

Social Media SDKs
-----------------

  - [Foursquare](https://github.com/baztokyo/foursquare-ios-api "Foursquare API
    SDK")
  - [Dropbox](https://www.dropbox.com/developers/sync/start/ios "Dropbox Sync SDK")
  - [Twitter](https://dev.twitter.com/docs/ios "Twitter iOS SDK")
  - [Facebook](https://developers.facebook.com/ios/ "Facebook iOS SDK")
  - [Instagram](https://github.com/crino/instagram-ios-sdk "Instagram iOS SDK")


Core Location/MapKit
=============

One of the biggest reasons mobile is such an interesting platform is the
ability to use location information. Think how much worse your phone would be
without Google Maps, Yelp, Foursquare, etc. Integrating Core Location is
actually quite easy.

After you learn how to use CoreLocation you need to learn how to present that
data with MapKit. MapKit allows integrated maps into your app. The advanced
section gives you some resources to use Google Maps instead of Apple Maps for
your integrated map views. Google Maps has some interesting features such as
Street View support, but it's very much icing on the cake. Nobody will complain
if you just use the standard MapKit.

Beginner
--------

  - Big Nerd Ranch 88-92
  - Big Nerd Ranch Chapter 5

Advanced
--------

###Google Maps SDK
  - [Official Google Maps
    Documentation](https://developers.google.com/maps/documentation/ios/start#getting_the_google_maps_sdk_for_ios "Official Google Maps Documentation")
  - [Google Maps API for iOS with Interface
    Builder](http://weblog.invasivecode.com/post/43675553480/google-maps-api-for-ios-with-interface-builder "Gooel Maps for iOS with Interface Builder")
  - [Google Maps
    CocoaPod](https://github.com/CocoaPods/Specs/tree/master/GoogleMapsKit
    "Google Maps CocoaPod Github Page")

Mobile Design
=============
Different screen size and interactions require different thoughts on design.
Below are two fantastic resources, but there is always more. 

Beginner
--------

  - [Apple Human Interface
    Guidelines](http://developer.apple.com/library/ios/#documentation/UserExperience/Conceptual/MobileHIG/Introduction/Introduction.html "Apple Human Interface Guidelines")
  - [Starter's Guide to iOS
    Design](http://taybenlor.com/2013/05/21/designing-for-ios.html "Starter's
    Guide to iOS Design")


Customizing UIKit
===================
AutoLayout is the new way of defining how your layouts work based on different
rotations and screen sizes. You are lucky because you will learn AutoLayout from
the very beginning but sadly The Big Nerd Ranch book doesn't include information on AutoLayout because it's
an iOS 5 book. I've included supplementary AutoLayout tutorials because of the
lack of information in the Big Nerd Ranch book.

Learning how to customize your app's UI is what separates the good apps from
the great. Think about all of the apps you use. Do any of them use the standard
UI elements? Nope. I bet you barely know what the standard iOS controls look
like. If you're interested open up the settings or contacts app.

This is a huge topic and much of what you'll do has been done by others and
answered on StackOverflow. After you've read this information and have specific
questions search on StackOverflow for answers. Very rarely are you doing
something completely unique.

Beginner
--------

  - [Beginning Auto
    Layout](http://www.raywenderlich.com/20881/beginning-auto-layout-part-1-of-2 "Beginning Auto Layout")
  - [Customizing
    UIKit](http://mobile.tutsplus.com/tutorials/iphone/ios-sdk-uikit-theme-customization/ "Customizing UIKit")
  - Big Nerd Ranch Chapter 24
  - Big Nerd Ranch Chapter 6
  - Big Nerd Ranch Chapter 7
  - Big Nerd Ranch Chapter 9
  - Big Nerd Ranch Chapter 10
  - Big Nerd Ranch Chapter 11

Advanced 
---------

  - Big Nerd Ranch Chapter 19
  - Big Nerd Ranch Chapter 20
  - Big Nerd Ranch Chapter 26
  - Big Nerd Ranch Chapter 13
  - Big Nerd Ranch Chapter 15


Hardware
========
The iPhone/iPad have a pretty cool set of hardware. Let your creativity flow
with the different hardware features. This is completely different then what
you've done on a computer.

Beginner
--------

  - BNR Chapter 12
  - [Using Core Motion to Access Gyro and Accelerometer](http://nscookbook.com/2013/03/ios-programming-recipe-19-using-core-motion-to-access-gyro-and-accelerometer/ "iOS Programming Recipe 19: Using Core Motion to Access Gyro and Accelerometer")


Core Animation
==============
Core Animation allows you to access to graphics card to some awesome animations
and transformations without sacrificing speed. The graphics card was designed
to do this and it does a great job. With that great power comes great
responsibility though. iPhone and iPad users expect fluid animations.
Thankfully, many standard animations you are used to seeing are actually built
into the iOS SDK and are super easy to integrate.

Beginner
--------

  - [UIView Transition
    Effects](http://i.ndigo.com.br/2012/05/ios-uiview-transition-effects/ "UI
    Transition Effects")
  - BNR Chapter 22
  - BNR Chapter 23

Advanced
--------

  - [Graphics And Animation on
    iOS](http://shop.oreilly.com/product/0636920020356.do "Graphics and
    Animation on iOS")

