---
layout: page
title: "index"
date: 2013-08-30 12:07
comments: false
sharing: false
footer: true
---

Overview
========

### NOW UPDATED FOR IOS 7 AND XCODE 5

This list comes from keeping track of what has been useful and not useful from
the past few years of learning iOS on my own. I'm compiling this to be a sort
of reference guide for the students in my upcoming class at [The Flatiron School](http://flatironschool.com/iOScurriculum.html "Flatiron School iOS Curriculum").

This is meant to get you up to speed with development from no prior iOS
experience. None of this covers the basics of computing/development though. 

Students learn in a plethora of ways. If you are an auditory learner there is 
also a ton of great video content from
[Stanford](https://itunes.apple.com/us/course/coding-together-developing/id593208016
"Stanford iTunes U Link") but the progression is pretty obvious so I didn't create a guide for
that. I HIGHLY recommend the Stanford class.

There is an infinite amount of stuff to learn on iOS. This is a list of what
I've found to be the most important for almost every app out there. A secondary
goal of this prework is to limit the scope of learning before you get started.
There really is nothing better than just writing a ton of code. Hopefully this
list of resources can get you to writing code quickly.

Structure
---------

This guide is separated out into the different big topics of iOS development.
I am including advanced topics here mostly for completeness and for reference
down the line. 

If you currently know very little, start with the beginner section and do
all the topics. This should get you up to speed with iOS development and really
I would just start writing code! Don't start looking into the advanced topics
until you find a topic you *need* to learn.

The Advanced and Reference/Library sections are for you to use once your feel
comfortable with your skills. I really recommend completing all the beginner 
materials before moving on to the advanced resources though. Once you look into
developing apps that require the topics you can return here and find out more
information and hopefully some links to start your research with.

Also, each section contains a description of an example app you should be able
to make. Feel free to try and make the app with the skills you have. If you
have issues with making the app, raise an issue. Hopefully someone will help
you out :)

Last, the Learning Objectives are what I expect you to understand after reading
the beginner materials. Remember the advanced materials are just for deep dives
into topics!

###Flatiron School Students

Flatiron School Students, your job is to *go through each section, in order,
following just the beginner items*. The *ADVANCED SECTION* at the end is if you
are really interested and want to keep learning, but isn't required. Don't
worry about the reference or library items. These are all things we will
discuss and use in class. Just the beginner items shouldn't take you more that
40 hours. If you already have prior knowledge feel free to skip sections you
feel comfortable with. Don't worry about the app that I list in each section.
If you have time then go ahead and try and develop the todo list app, but it
isn't required. 

Setup
-----

I tried to use as many free resources as possible but ultimately you have to
spend some money. You'll need to purchase [Learning iOS Development: A Hands-on
Guide to the Fundamentals of iOS Programming](http://www.amazon.com/Learning-iOS-Development-Hands--Fundamentals/dp/0321862961/ref=sr_1_1?ie=UTF8&qid=1387385220&sr=8-1&keywords=learning+ios+development)
 for a few of the items in this guide. It's an incredible book and it has been
updated for iOS 7/Xcode 5.

Thoughts
--------

###Breadth of Familiarity
This list of resources will not make you an expert by any means. The goal for
this guide is breadth of knowledge over depth in any one topic. If you are
particularly interested in a topic, feel free to check out the advanced
resources and reference material. 

The best way to learn this stuff is still to just write a ton of code. In
addition to checking out the advanced material on a certain topic, coding up
the example apps is a great way to get a deeper understanding.

###Minimum Viable Knowledge
Learning the topics in the order given allows you to start writing apps as soon
as possible. That's the fun stuff, so I didn't want you to have to read for
hours before getting your hands dirty. The goal is layers of quality. After the
first section you will be able to write simple apps. Every new topic you learn
will give you real skills to enhance your app. This means that if you are
struggling with one topic it may be prudent to stay in that one topic and learn
more. If you find other resources that helped you learn please raise and issue
and I'll include it.

Getting Help
------------

If you are confused on a topic, I doubt you're alone. 

Thankfully, there are a few resources available to you.
The easiest is using the [iOS section on
StackOverflow](http://stackoverflow.com/questions/tagged/ios "StackOverflow iOS
tagged homepage"). If the question is about a certain resource here, or about
this guide in general please please please raise an issue on github. I'll look
into it and hopefully give you a solution that everyone can use.

Contributing
------------

It's pretty simple. Raise a github issue or fork and submit a pull request with
your requested changes.


Command Line and Git
====================

Before starting all of this, you *need* to be familiar with the command line
and git. The command line is the way you'll interact with your computer as a
developer. Yes, it's a bit different but don't worry, I promise you'll
understand it soon! Git is a system for version control. Check out the links
below for more information. 

Check out Web Developement Prework on the [Command Line](http://prework.flatironschool.com/#command-line)
and [Git](http://prework.flatironschool.com/#git)


Objective-C
===========
Objective-C is the language of iOS and it is most likely pretty different than
what you've done before. To get started you just need a bit of knowledge of
Objective-C, but to really master iOS development you need to get a solid
understanding of the language. The best Rails developers are also the best Ruby
developers. The same is true in the Objective-C/iOS world.

###App
Try and write a todo list app with just `NSLog` results

###Learning Objectives
  - Message passing with Objective-C
  - Comfort with the syntax of Objective-C
  - Understanding basic Objects. Instance variables, Methods, The `super`
    keyword, etc.
  - Working with Data Types

Beginner
--------
  - [Intro to Objective-C](http://rypress.com/tutorials/objective-c/introduction.html)
  - [Try Objective-C on Code School](http://tryobjectivec.codeschool.com/)
  - Chapter 2 in Learning iOS Development

Advanced
---------
  - Programming in Objective-C (5th Edition)
    - Yup it's an entire book on Objective-C. It's a great reference book and
      will make you an expert in Objective-C.
  - [Programming With
    Objective-C](http://developer.apple.com/library/mac/#documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html
    "Programming With Objective-C")

Basic iOS
=========

This will get you going to write a super simple app. It's not going to look
pretty, but it'll work.  

###App
Super simple ToDo list app. It should have a table with todos in it.

###Learning Objectives
  - Understand how to design interactions with Storyboards
  - Building interfaces with Interface Builder
  - Declaring and Synthesizing properties
  - Understand methods in Objective-C
  - Understand basics of ARC and memory management
  - Familiarity with debugging - you'll get better at this with practice


Beginner
--------

  - [Try iOS on Code School](https://www.codeschool.com/courses/try-ios)
    - Great Introduction to iOS and the view infrastructure
  - Chapter 3 in Learning iOS Development
  - [Working with NSUserDefaults](http://mobile.tutsplus.com/tutorials/iphone/nsuserdefaults_iphone-sdk/)

Advanced
---------
  - Chapter 13 in Learning iOS Development


Object Oriented Principles
=============

The iOS ecosystem relies heavily on a few Object Oriented principles. The
beginner items covers the stuff that is somewhat unique to iOS. Going further
you will see these patterns *everywhere*. 

###App
This is mostly a theory section. Just make sure you fully understand the
concepts.

###Learning Objectives
  - Understand the Delegate pattern
  - Understand the protocol pattern

Beginner
--------

  - [iOS Design Patterns:
    Delegation](http://blog.teamtreehouse.com/ios-design-patterns-delegation-part-2-2 - Learn the Delegation Pattern. This is used all over the place in iOS.
        For example Core Location, TableViews, MapKit, etc.
    "iOS Design Patters: Delegations")
  - [Intro to
    Protocols](http://iosdevelopertips.com/cocoa/introduction-to-protocols.html "Intro to Protocols")
      - Learn Protocols. These are the things in between the < and > >. Yet
        again, they are everywhere

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

Using Common UI Tools
=====================

iOS comes with a bunch of common UI objects that get you going quickly. As you
learn about things such as `UINavigationController` and `UITableView` you'll
realize that nearly *every* app utilizes modifications on these simple UI
controls. Let's learn these!

### App
Implement your ToDo List app as a UITableView and tapping on each itme should
go to a detail view in the nav controller

### Learning Objectives
  - Understand what pushing a ViewController means
  - Working with `UITableViewDataSource` methods
  - Working with UITableviews Dynamically and Statically

Beginner
--------

  - Chapter 7 of Learning iOS Development
  - Chapter 8 of Learning iOS Development

Advanced
--------

  - Chapter 10 of Learning iOS Development
  - Chapter 11 of Learning iOS Development
  - [Beginning UICollectionView in iOS 6](http://www.raywenderlich.com/22324/beginning-uicollectionview-in-ios-6-part-12)
    - Still based of of iOS 6 but *very* relevant


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

###App
Add the ability to tag a todo with where it should be completed. Like Buy
groceries at the grocery store.

###Learning Objectives
  - Use the delegate pattern to receive updates from Core Location
  - Drop pins on a MapKit View
  - Basic MapKit customizatiosn such as switching between satellite and map
    view.
  - Handle the different events of Core Location such as major change, best
    accuracy change, etc.

Beginner
--------

  - [iOS 6 Core Location Tutorial](http://www.devfright.com/ios-6-core-location-tutorial/)
    - There was a big change in `CoreLocation` from iOS 5-> iOS 6. This is an
      updated tutorial
  - [Intro to MapKit in iOS 6](http://www.raywenderlich.com/21365/introduction-to-mapkit-in-ios-6-tutorial)


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

###App
Implement your ideas from the design section. You may have to pare down your
ideas a bit.

###Learning Objectives
  - Be able to style the color/size of major UITableView, UINavigationView and
    UITabBar
  - Understand how Views interact with View Controllers
  - Understand the View lifecycle

Beginner
--------

  - [Beginning Auto
    Layout](http://www.raywenderlich.com/20881/beginning-auto-layout-part-1-of-2 "Beginning Auto Layout")
      - Auto Layout is how you can lay out UI elements with differing screen
        sizes. This guide walks you through that.
  - [Customizing
    UIKit](http://mobile.tutsplus.com/tutorials/iphone/ios-sdk-uikit-theme-customization/ "Customizing UIKit")
      - Some common UIKit customziations and how to do them.
  - [Customizing Nav Bar and Status Bar in iOS 7](http://www.appcoda.com/customize-navigation-status-bar-ios-7/)

Advanced 
---------

  - Chapter 6 in Learning iOS Development

Mobile Design
=============
Different screen size and interactions require different thoughts on design.
Below are two fantastic resources, but there is always more. 

###App
Do some mockups with paper and pencil on how you cauld enhance the interface.
In the next section you'll actually code them. 

###Learning Objectives
  - Familiarity with the "Apple way" of designing mobile apps.
  - Differences between web design and mobile design
Beginner
--------

  - [Apple Human Interface
    Guidelines](http://developer.apple.com/library/ios/#documentation/UserExperience/Conceptual/MobileHIG/Introduction/Introduction.html "Apple Human Interface Guidelines")
      - Apple posts their guidelines on good mobile design. You should follow
        these somewhat closely as it provides a consistant UI from app to app
  - [Starter's Guide to iOS
    Design](http://taybenlor.com/2013/05/21/designing-for-ios.html "Starter's
    Guide to iOS Design")
      - Absolutely incredible guide on how to think about mobile design.


ADVANCED TOPICS
===============

Below are a bunch of advanced topics that you should learn about but aren't
required for Flatiron School Students.

Integrating with APIs and Social Media
=====================
Nothing exists in a vacuum. Apps are expected to share effortlessly and backup
to the cloud. The beginner section has some of the super simple stuff and is
all you really need to get started. The [Helios](http://helios.io/ "Helios Home
Page") tutorial shows you how to create a *super simple* server side backend
for your iOS app. This is really the absolute simplest possible solution to
  syncing your app with the internet

I'm purposefully exposing you to the native iOS SDK networking stack before
AFNetworking and the other libraries. It's *very* hard to debug problems with
the libraries if you don't understand the underlying technologies.

Also this has an intermediate section just because this topic is so massive.
Still stick to the beginner information at first though.

###App
Add server side syncing to your ToDo list app. Also try and share todos on
Twitter/facebook

###Learning Objectives
  - Ability to set up and use Helios
  - Understand SLComposeViewController

Intermediate
------------
  - [Mattt Thompson: Build an iOS App in 20 Minutes with Rails and
    AFIncrementalStore](https://www.youtube.com/watch?v=8wrFn6flYdQ "Youtube
    Video of a Mattt Thompson Talk on using Helios")
      - Video from a recent conference where Mattt Thompson walks you through
        developing a simple ToDo app with a server side backedn
  - [Integrate Twitter and Facebook Sharing in Your
    App](http://www.appcoda.com/ios-programming-101-integrate-twitter-and-facebook-sharing-in-ios-6/
    "Integrate Twitter and Facebook Sharing in Your App")
      - These are built in to iOS. This tutorial allows you to share your
        content really quickly to Facebook and Twitter
  - [Subclassing
    UIActivity](http://blog.goosoftware.co.uk/2013/05/04/subclassing-uiactivity/ "Subclassing UIActivity Video")
  - [Building an iOS app with AFIncrementalStore and Core Data Buildpack](https://devcenter.heroku.com/articles/ios-core-data-buildpack-app "Heroku Article on Core Data Buildpack") - This is the howto for Helios
  - [Getting Started with the Facebook
    SDK](https://developers.facebook.com/docs/tutorials/ios-sdk-tutorial/show-friends/
    "Getting Started with the facebok SDK")
  - [Sharing Providers for UIActivity](http://uiactivities.com/ "UIActivities
    Home Page")]

Advanced
--------

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

Core Data
=========

Core Data is a persistent data store. It is not a database. This is seriously
one of the most confusing technologies in the iOS ecosystem, but it is
something *you must learn*. In the integrating with APIs section you'll learn
even more about Core Data and how to save both locally and sync up to the
cloud. Think about all of the apps you use. Most of them can be boiled to down
to displaying some data that is synced to a service.

###App
Try and save your ToDos locally using CoreData. 

###Learning Objectives
  - Understand how read and write data from the NSManagedObjectContext
  - Persistant CoreData to the device using sqlite3
  - Work with CoreData with TableViews
  - Autogenerate, and extend CoreData Model files
    16 is great for this.

Advanced
--------
  - Chapter 9 of Learning iOS Development
  - [Pro Core Data for
    iOS](http://www.amazon.com/Pro-Core-Data-Second-Edition/dp/1430236566/ref=pd_sim_b_26 "Pro Core Data For iOS")
    - Told you it was a big topic.
  - [Core Data Tutorial for iOS: Getting
    Started](http://www.raywenderlich.com/934/core-data-tutorial-for-ios-getting-started "Core Data Tutorial for iOS: Getting Started")
    - Practical example on how make a Core Data app. Make sure you read all three parts. The NSFetchedResultsController part
      is super important and how you connect Core Data to UITableViews.

Libraries
---------

  - [MagicalRecord](https://github.com/magicalpanda/MagicalRecord "Magical
    Record GitHub Page")
    - Library that automates a lot of the common CoreData stuff and implements
      some best practices.


Reference
---------

  - [Core Data Quickie](http://borkware.com/quickies/one?topic=Core%20Data
    "Core Data Quickies")


Hardware
========
The iPhone/iPad have a pretty cool set of hardware. Let your creativity flow
with the different hardware features. This is completely different then what
you've done on a computer.

###App
Add the ability to add pictures to your app.

###Learning Objectives
  - Use the camera
  - Change hardware behavior based on hardware availability
  - Use the accelerometer and gyro

Advanced
--------

  - [Using Core Motion to Access Gyro and Accelerometer](http://nscookbook.com/2013/03/ios-programming-recipe-19-using-core-motion-to-access-gyro-and-accelerometer/ "iOS Programming Recipe 19: Using Core Motion to Access Gyro and Accelerometer")


Core Animation
==============
Core Animation allows you to access to graphics card to some awesome animations
and transformations without sacrificing speed. The graphics card was designed
to do this and it does a great job. With that great power comes great
responsibility though. iPhone and iPad users expect fluid animations.
Thankfully, many standard animations you are used to seeing are actually built
into the iOS SDK and are super easy to integrate.

###App
Add in some custom animations. Maybe have a cool strike out animation when you
mark a task as done.

###Learning Objectives
  - Understand how the contexts and layers of core animation work
  - Know when to use the correct transitions for different interactions.

Advanced
--------

  - [Graphics And Animation on
    iOS](http://shop.oreilly.com/product/0636920020356.do "Graphics and
    Animation on iOS")
  - [UIView Transition
    Effects](http://i.ndigo.com.br/2012/05/ios-uiview-transition-effects/ "UI
    Transition Effects")
      - Learn the different ways you can transition form view to view and the
        reasons why you choose those transitions.

Xcode
=====
Xcode is what you develop iOS apps in. A craftsman knows his/her tools. Make
sure you know yours. This is mostly for reference. No learning objectives or
app progression here, just some great tips!

Advanced
--------

  - [14 Essential Xcode Tips and
    Tricks](http://mobileorchard.com/14-essential-xcode-tips-tricks-and-resources-for-iphone-devs/)
    - After you've used Xcode for a while, here are some extra tips I find
        useful
  - [XVim](https://github.com/JugglerShu/XVim "XVim") 
    - I use vim on the command line. If you're like me, this will make your life
      so. much. better
  - Chapter 14 in Learning iOS Development
