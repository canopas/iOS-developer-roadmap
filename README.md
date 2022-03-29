<h1 align="center">iOS Developer Roadmap 2022</h1>

![alt text](https://github.com/cp-radhika-s/Android-Roadmap/blob/main/image/og_image.png)

iOS Developer Roadmap 2022 is learning paths to understanding iOS development.

## What is iOS App Development?
iOS is Apple’s mobile operating system (OS) that runs on hardware including iPhone, iPad and iPod Touch. An iOS application is programmed in languages such as Swift and Objective-C and then deployed to the App Store for users to download.

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
* Do all [practicles](https://docs.google.com/document/d/19pIneA9SooEoco6ABiiJTluTPzakfBow/edit) using playground.

### XCode
* [Basic introduction](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16250858#overview)
* [Introduction to interface](https://codewithchris.com/xcode-tutorial).

### Version control system

#### Practicle 1.2
* Create repository of practicle 1.1 on Gitlab

#### References
* Introduction to version control: [What Is Version Control?](http://guides.beanstalkapp.com/version-control/intro-to-version-control.html)
* How to use git
    -  [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123)
    -  [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/10929402#overview)
    -  [When to commit in version control](https://softwareengineering.stackexchange.com/questions/74764/how-often-should-i-do-you-make-commits)

## Sprint 2
* [How to use apple Documentation](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16252724#overview)
* [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes)
* [iOS App Life Cycle](https://medium.com/@neroxiao/ios-app-life-cycle-ec1b31cee9dc)
* [UIViewController](https://developer.apple.com/documentation/uikit/uiviewcontroller) and its [life cycle](https://medium.com/good-morning-swift/ios-view-controller-life-cycle-2a0f02e74ff5)

#### AutoLayout
* Overview about [AutoLayout](https://www.udemy.com/join/login-popup/?next=/course/ios-13-app-development-bootcamp/learn/lecture/16252628#overview)
* [How to use constraints and apply them to making iOS apps using AutoLayout](https://www.raywenderlich.com/811496-auto-layout-tutorial-in-ios-getting-started).

#### Practicle 2.0
* Create [UI](https://docs.google.com/document/d/1ae9LMqWenP__rK4anDpj69-pVK3vVNXC/edit) using autoLayout.

## Sprint 3
* [iOS Network API and JSON](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16253648#overview)
    - Elegant HTTP Networking in Swift: [Alamofire](https://github.com/Alamofire/Alamofire)
 
* [UIScrollView](https://www.raywenderlich.com/159481/uiscrollview-tutorial-getting-started)

* [UITableView](https://developer.apple.com/documentation/uikit/uitableview)
    - [UITableview with custom cells](https://www.ralfebert.de/ios-examples/uikit/uitableviewcontroller/custom-cells/)
    - [Self-sizing Table View Cells](https://www.raywenderlich.com/129059/self-sizing-table-view-cells)
    - [Delete Row From Tableview](https://www.ioscreator.com/tutorials/delete-rows-table-view-ios-tutorial-ios12)
    - [Add Search bar in tableview](https://www.raywenderlich.com/472-uisearchcontroller-tutorial-getting-started)

* [Storyboard Segue: Pass data between view controllers](https://www.raywenderlich.com/5055364-ios-storyboards-getting-started)

* [UITabBarController](https://developer.apple.com/documentation/uikit/uitabbarcontroller)
   * Other References:
    - [Starting an iOS Tab Bar App with UITabBarViewController](https://codewithchris.com/ios-tab-bar-app/)
    - [UITabBarController Programmatically](https://unicornmobile.medium.com/uitabbarcontroller-programmatically-316b89b5b21b)

#### Practical 3.0
* Create an app of Git Users.
* Create app with 2 tab:
    A. All Users [ display list of all Users ]
    B. Profile [ display email,avatar, name of current logged in user ]
* Provide a login facility when the user first installs the app & after show Tabbar home screen [ all users ].
* Check for authentication of user from: https://api.github.com/users
* Use gitHub doc : https://developer.github.com/v3/users/#get-the-authenticated-user
* Display data in table view from below API. - on All Users screen
    - https://api.github.com/users
* Display user avatar(image), name into TableViewCell. 
* On Cell click user information should be displayed with Name, avatar , followers, following  on another screen.
* Take a batch size of 30 & put a loader at bottom of the screen while loading data.

## Sprint 4

* UICollectionview
    - [UICollectionView](https://developer.apple.com/documentation/uikit/uicollectionview)
    - [UICollectionViewDelegate](https://developer.apple.com/documentation/uikit/uicollectionviewdelegate)
    - [UICollectionViewFlowLayout](https://developer.apple.com/documentation/uikit/uicollectionviewflowlayout)
    - [CollectionView based App with custom Collection cell](https://www.raywenderlich.com/9334-uicollectionview-tutorial-getting-started)
    - [Add Header and footer in collectionview and tableview](https://www.raywenderlich.com/9477-uicollectionview-tutorial-reusable-views-selection-and-reordering#toc-anchor-001)
    - [CollectionView Compositional Layout](https://www.raywenderlich.com/5436806-modern-collection-views-with-compositional-layouts)

* [UIStackView](https://www.raywenderlich.com/160646/uistackview-tutorial-introducing-stack-views-2)
* [UIGestureRecognizer](https://www.raywenderlich.com/6747815-uigesturerecognizer-tutorial-getting-started)

* Database
    - [UserDefault](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/10929418#overview)
    - [CoreData](https://medium.com/@ankurvekariya/core-data-crud-with-swift-4-2-for-beginners-40efe4e7d1cc)
    - [SQLite](https://github.com/stephencelis/SQLite.swift)
    - [Realm](https://www.raywenderlich.com/9220-realm-tutorial-getting-started)
 
 * [CocoaPods](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/16813258#overview)

#### Practical 4.0 - Photo Gallery
- Create 1 screen app using collectionView.
- Create collectionView with 2 sections.
- Display Images from Github API.
- First cell should have + sign to load more Images in particular section.
- Store images into database, & it should be accessible offline.
- Also provide Delete[multiple selection] & move facility in gallery & it should also delete & move in database. 
