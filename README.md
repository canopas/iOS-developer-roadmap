<h1 align="center">iOS Developer Roadmap 2022</h1>

![alt text](https://github.com/canopas/iOS-developer-roadmap/blob/main/assets/road-map.png)

iOS Developer Roadmap 2022 is a learning path to understand iOS development.

## What is iOS App Development?
iOS is Apple’s mobile operating system (OS) that runs on hardware including iPhone, iPad and iPod Touch. An iOS application is programmed in languages such as [Swift](https://gavinw.me/swift-macos/) and [Objective-C](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html) and then deployed to the App Store for users to download.

# Table of contents
* [Sprint 1](https://github.com/canopas/iOS-developer-roadmap#sprint-1)
* [Sprint 2](https://github.com/canopas/iOS-developer-roadmap#sprint-2)
* [Sprint 3](https://github.com/canopas/iOS-developer-roadmap#sprint-3)
* [Sprint 4](https://github.com/canopas/iOS-developer-roadmap#sprint-4)
* [Sprint 5](https://github.com/canopas/iOS-developer-roadmap#sprint-5)
* [Sprint 6](https://github.com/canopas/iOS-developer-roadmap#sprint-6)

#### Let's start with basic learning

## Sprint 1

### Swift Basics
* Introduction to [Swift programming](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html) including all OOPs concepts.
* Learn [basics of Swift](https://www.udacity.com/course/swift-for-beginners--ud1022) with core principles.
* Basic introduction to [Swift Playgrounds](https://www.appcoda.com/learnswift/playgrounds.html).

#### Practicle 1.1
* Do all [practicles](https://github.com/canopas/iOS-developer-roadmap/blob/main/Practical-1.1.md) using playground.

### XCode
* [Basic introduction](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16250858#overview)
* [Introduction to interface](https://codewithchris.com/xcode-tutorial).

### Version control system

#### Practicle 1.2
* Create repository of practicle 1.1 on Gitlab

#### References
* Introduction to version control: [What Is Version Control?](https://tutorials.codebar.io/version-control/introduction/tutorial.html)
* How to use git
    -  [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123)
    -  [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/10929402#overview)
    -  [When to commit in version control](https://softwareengineering.stackexchange.com/questions/74764/how-often-should-i-do-you-make-commits)
    -  [Understanding Git Version Control and Learn How to Use It in Xcode](https://medium.com/appcoda-tutorials/understanding-git-version-control-and-learn-how-to-use-it-in-xcode-1bb29c10fc2d)  or  [with terminal](https://medium.com/the-sd-coders/using-git-version-control-with-terminal-and-xcode-aabeae21f17e)

## Sprint 2
* [How to use apple Documentation](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16252724#overview)
* [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/guidelines/overview)
* [iOS App Life Cycle](https://medium.com/@neroxiao/ios-app-life-cycle-ec1b31cee9dc)
* [UIViewController](https://developer.apple.com/documentation/uikit/uiviewcontroller) and its [life cycle](https://medium.com/good-morning-swift/ios-view-controller-life-cycle-2a0f02e74ff5)

#### AutoLayout
* [Overview about AutoLayout](https://www.udemy.com/join/login-popup/?next=/course/ios-13-app-development-bootcamp/learn/lecture/16252628#overview)
* [How to use constraints and apply them to making iOS apps using AutoLayout](https://www.raywenderlich.com/811496-auto-layout-tutorial-in-ios-getting-started).

#### Practicle 2.0
* Create given [reaponsive UI](https://github.com/canopas/iOS-developer-roadmap/blob/main/assets/Practical-2.0.png) using autoLayout.
    - You can use alternative images.

## Sprint 3
* [iOS Network API and JSON](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16253648#overview)
    - Elegant HTTP Networking in Swift: [Alamofire](https://github.com/Alamofire/Alamofire)
 
* [UIScrollView Tutorial: Getting Started](https://www.raywenderlich.com/159481/uiscrollview-tutorial-getting-started)
    - [A Beginner’s Guide to UIScrollView](https://www.appcoda.com/uiscrollview-introduction/)
    - [How to use scroll view in Interface Builder / Storyboard](https://fluffy.es/scrollview-storyboard-xcode-11/)

* [UITableView](https://developer.apple.com/documentation/uikit/uitableview)
    - [UITableview with custom cells](https://www.ralfebert.de/ios-examples/uikit/uitableviewcontroller/custom-cells/)
    - [Self-sizing Table View Cells](https://www.raywenderlich.com/129059/self-sizing-table-view-cells)
    - [Delete Row From Tableview](https://www.hackingwithswift.com/example-code/uikit/how-to-swipe-to-delete-uitableviewcells)
    - [Add Search bar in tableview](https://www.raywenderlich.com/472-uisearchcontroller-tutorial-getting-started)

* [Storyboard Segue: Pass data between view controllers](https://www.raywenderlich.com/5055364-ios-storyboards-getting-started)

* [UITabBarController](https://developer.apple.com/documentation/uikit/uitabbarcontroller)
    - [Tab Bar Controller Guide](https://guides.codepath.com/ios/Tab-Bar-Controller-Guide)
    - [Starting an iOS Tab Bar App with UITabBarViewController](https://codewithchris.com/ios-tab-bar-app/)
    - [UITabBarController Programmatically](https://unicornmobile.medium.com/uitabbarcontroller-programmatically-316b89b5b21b)

#### Practical 3.0
* Create an app of Git Users.
* Create app with 2 tab:

    A. All Users [display list of all Users]

    B. Profile [display email,avatar, name of current logged in user]
* Provide a login facility when the user first installs the app & after show Tabbar home screen [ all users ].
* Check for authentication of user from: https://api.github.com/users
* Use gitHub doc : https://developer.github.com/v3/users/#get-the-authenticated-user
* Display data in table view from below API. - on All Users screen
    - https://api.github.com/users
* Display user avatar(image), name into TableViewCell. 
* On Cell click user information should be displayed with Name, avatar , followers, following  on another screen.
* Take a batch size of 30 & put a loader at bottom of the screen while loading data.

* Note:
    - Use [Alamofire](https://github.com/Alamofire/Alamofire) for API call.
    - Use [Kingfisher](https://github.com/onevcat/Kingfisher) to load image from URL.

## Sprint 4
* [UICollectionView](https://developer.apple.com/documentation/uikit/uicollectionview)
    - [UICollectionViewDelegate](https://developer.apple.com/documentation/uikit/uicollectionviewdelegate)
    - [UICollectionViewFlowLayout](https://developer.apple.com/documentation/uikit/uicollectionviewflowlayout)
    - [UICollectionView Tutorial: Getting Started](https://www.raywenderlich.com/9334-uicollectionview-tutorial-getting-started)
    - [UICollectionView Tutorial: Headers, Selection and Reordering](https://www.raywenderlich.com/9477-uicollectionview-tutorial-reusable-views-selection-and-reordering#toc-anchor-001)
    - [Modern Collection Views with Compositional Layouts](https://www.raywenderlich.com/5436806-modern-collection-views-with-compositional-layouts) :- [Getting Started with UICollectionViewCompositionalLayout](https://lickability.com/blog/getting-started-with-uicollectionviewcompositionallayout/)

* [UIStackView](https://www.raywenderlich.com/160646/uistackview-tutorial-introducing-stack-views-2)
* [UIGestureRecognizer](https://www.raywenderlich.com/6747815-uigesturerecognizer-tutorial-getting-started)

* Database
    - [UserDefault](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/10929418#overview)
    - [CoreData](https://medium.com/@ankurvekariya/core-data-crud-with-swift-4-2-for-beginners-40efe4e7d1cc)
    - [SQLite](https://github.com/stephencelis/SQLite.swift)
    - [Realm](https://www.raywenderlich.com/9220-realm-tutorial-getting-started)
 
* [CocoaPods](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16813258#overview)
* [Swift Package Manager](https://www.swift.org/package-manager)

#### Practical 4.0 - Photo Gallery
- Create 1 screen app using collectionView.
- Create collectionView with 2 sections.
- Display Images from Github API.
- Last cell should have + sign to load more Images in particular section.
- Store images into database, & it should be accessible offline.
- Also provide Delete[multiple selection] & move facility in gallery & it should also delete & move in database. 

* Just for reference: [100 Days of Swift](https://www.hackingwithswift.com/100)

## Sprint 5
#### [RxSwift](https://github.com/ReactiveX/RxSwift) and RxCocoa
* Rx-Swift is a reactive programming library in iOS app development. It is a multi-platform standard, its difficult-to-handle asynchronous code in Swift, that becomes much easier in Rx-Swift. RxSwift makes it easy to develop dynamic applications that respond to changes in data and respond to user events. Ultimately, it solves the issues related to asynchronous development.

#### [SwiftUI](https://developer.apple.com/tutorials/SwiftUI)
* [Introducing SwiftUI](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16254084#overview)

#### Practical 5.1
* Design [this screen](https://github.com/canopas/iOS-developer-roadmap/blob/main/assets/Practical-5.1.gif) using SwiftUI. It should be responsive and should support all iOS and iPad devices.

#### [Combine](https://developer.apple.com/documentation/combine)
* [Intro to SwiftUI Combine and Data](https://designcode.io/swiftui-combine-intro)
* [Getting started with the Combine framework in Swift](https://www.avanderlee.com/swift/combine)

#### Practical 5.2
* Create simple TODO app with CRUD operation with SQLite using SwiftUI and Combine.
    - Home screen should have list of task with add new task fab button.
    - On the click of task it should be redirect to task status screen where it can be edit.
    - On the cell swipe it shows delete option and on it's click that particular task should delete.
    - Add option to active and inactive task.

## Sprint 6

* [Combine Asynchronous Code](https://developer.apple.com/documentation/combine/using-combine-for-your-app-s-asynchronous-code)
* [async/await in SwiftUI](https://peterfriese.dev/posts/swiftui-concurrency-essentials-part1)
* [Networking with Combine and SwiftUI](https://peterfriese.dev/posts/swiftui-combine-networking-gettingstarted)
* [Detail knowledge about combine](https://heckj.github.io/swiftui-notes)

#### Practical 6.0
* Retrieve and display simple users list from web API to iOS List(SwiftUI). Display name, email and city in list.

* API Info:
    - Type: GET
    - Path: http://jsonplaceholder.typicode.com/users. 

* Notes:
    - App should support all iPhone and iPad
    - Project should be under version control system(use git)
    - Use [Alamofire](https://github.com/Alamofire/Alamofire) for API call
    - Cell first show name only and it expand on tap or button like down arrow and show email and city

* Features:	
     - Delete user on long press.
     - Add SwipeToRefresh functionality 
     - Store users in the database using CoreData. Refresh them in the database when SwipeToRefresh is triggered.
     - Implement Add user functionality with three text box of name, email and city
     - On the user item select event show it’s details in the new screen (Controller).
     - Implement swiping functionality using UICollectionView. On the user detail screen we should be able to move the next/previous user with a horizontal swipe.

* Just for reference: [100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui)

## Learning a few useful libraries

* Checkout [this article](https://medium.com/canopas/1-min-guide-to-ios-development-best-practices-in-2022-e3f1d009cfa1) for useful libraries and best practices.
* [UIPilot: The missing typesafe SwiftUI navigation library](https://github.com/canopas/UIPilot)
* [Cool animations implemented with SwiftUI](https://github.com/canopas/Swiftui-animations-examples)

## Extra Practicals

* [GitUser Store](https://docs.google.com/document/d/1krxgL5VxzRNGcTHhdSPMf-HwFYYc0Hbn9I6YWMkeGKk)
* [UniversityRoom](https://docs.google.com/document/d/1g-45sRokWTVewusxk5K-JyQAktMKr2JLKoCtErEm_3Y)
