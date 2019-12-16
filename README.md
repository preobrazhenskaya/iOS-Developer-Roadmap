# iOS Developer Roadmap

<!-- **Progress: ◽◽◽◽◽◽◽◽◽  0.0001%** -->
<!-- ☑️ -->

##  Memory manadgment  

  - [X] Stack and Heap
  - [X] Value vs Reference type
  - [X] ARC
  - [ ] MRC
  - [X] Retain cycles
  - [ ] Memory leaks
  - [ ] [Autorelease pool](https://developer.apple.com/documentation/foundation/nsautoreleasepool?language=occ)
  - [ ] Shallow and deep copying
  - [X] Weak/Strong references

## Swift

- [X] Closures
- [ ] Generics
- [X] Initializers
- [X] Protocols
- [X] Struct
- [X] Enums
- [ ] Runtime
- [ ] Method dispatch

## Multithreading and concurency

* [Concurrency vs Multi-threading vs Asynchronous Programming : Explained](https://habr.com/ru/post/337528/)

- [ ] [`GCD`](https://medium.com/@alexey_nenastev/всё-о-многопоточности-в-swift-часть-1-настоящее-f0b4d5718877)
  - [ ] Semaphors
  - [ ] DispatchGroup
  - [ ] DispatchWorkItem
  - [ ] DispatchSource
- [ ] NSOperationQueue
- [ ] Race condition
- [ ] Deadlock
- [ ] Livelock
- [ ] Readers/writers problem
- [ ] [Green threads](https://ru.wikipedia.org/wiki/Green_threads)
- [ ] Runloop

## `UIKit`

- [ ] UIApplication
- [ ] UIApplication: States
- [X] [`UIViews`]()
  - [X] UITableViews
  - [X] UICollectionViews
- [ ] [`Layout`]()
  - [ ] Frame-based
  - [ ] Autolayout
- [X] Navigation
- [X] UIViewController
- [ ] UIViewController: Lifecycle

## Networking

- [ ] URLSession
- [X] Alamofire
- [ ] Rest API
- [X] Difference between `GET`, `POST`, `PUT`, `PATCH`, `DELETE`

## Foundation

- [ ] Notifications vs Delegation vs Observing
- [X] Collections
- [ ] Networking
- [ ] [`Serialization`]()
  - [ ] NSCoding
  - [X] Codable
  - [ ] JSON
  - [ ] XML

## Software Architecture

* [clean architecture 1](https://hackernoon.com/introducing-clean-swift-architecture-vip-770a639ad7bf)
* [clear architecture 2](https://clean-swift.com/clean-swift-ios-architecture/)

- [X] MVC
- [ ] MVVM
- [ ] MVP
- [ ] VIPER

## Design patterns (17/31)

- [ ] [`Creational`]()
  - [ ] Factory
  - [ ] Abstract Factory
  - [ ] Builder
  - [ ] Factory Method
  - [ ] Prototype
  - [ ] Object Pool
  - [ ] Singleton
- [ ] [`Structural`]()
  - [ ] Adapter
  - [ ] Bridge
  - [ ] Composite
  - [ ] Decorator
  - [ ] Facade
  - [ ] Flyweight
  - [ ] Proxy
- [ ] [`Behavioural`]()
  - [ ] Command
  - [ ] Chain of responsibility
  - [ ] Interpreter
  - [ ] Iterator
  - [ ] Mediator
  - [ ] Memento
  - [ ] Observer
  - [ ] State
  - [ ] Strategy
  - [ ] Visitor
- [ ] [`Other`]()
  - [ ] Anti-pattern
  - [ ] Class cluster
  - [ ] Chain of Responsibility
  - [ ] Receptionist
  - [ ] Template Method

## Design principles

- [ ] [`SOLID`]()
  - [ ] Single responsibility principle
  - [ ] Open/closed principle
  - [ ] Liskov substitution principle
  - [ ] Interface segregation principle
  - [ ] Dependency inversion principle
- [ ] Inversion of Control
- [ ] Dependency Injection
- [X] Dry (don't repeat yourself)
- [ ] KISS (keep it simple, stupid)

## Dependency management

* [article #1](https://medium.com/ios-os-x-development/cocoapods-vs-carthage-675633e89c3e)
* [article #2](https://dzone.com/articles/carthage-or-cocoapods-that-is-the-question)

- [X] Cocoapods
- [ ] Carthage
- [ ] Swift Package Manager

## Version Control System

- [X] git
- [ ] SVN

## Caching and Presistency (2/4)

- [ ] Core Data
- [X] Realm
- [ ] YAPDatabase
- [ ] SQLite

## Testing (3/5)

- [ ] Unit Tests
- [ ] Snapshot Tests
- [ ] Functional test
- [ ] TDD
- [ ] BDD

## XCode/Tools/Debbuging (7/11)

- [X] Workspace/cocoapods
- [X] Interface Builder
- [ ] Keychain
- [ ] Security Transforms API
- [X] UI Debbuging
- [X] Reveal for UI Debuggin
- [ ] Instruments: Leaks
- [ ] Instruments: Time profiler
- [ ] Instruments: Allocations
- [ ] Zombies
- [ ] Activity monitor  
- etc...

## Continuous Integration (0/3)

- [ ] Fastlane
- [ ] Jenkins
- [ ] Xcode server

## Computer Science knowledge (2/22)

- [ ] Algorithms
  - [X] Sorting
  - [X] Graph Theory -> Trees
  - [X] Strings
  - [ ] Greedy
  - [ ] Dynamic Programming
  - [ ] Bit Manipulation
  - [X] Recursion
  - [ ] Game Theory
  - [ ] NP Complete
  - [ ] Big-O notation
- [ ] [`Abstract Data Types`]()
  - [X] Stack
  - [X] Array
  - [X] List
  - [X] Map
  - [ ] Multimap
  - [X] Set
  - [ ] Multiset (Bag)
  - [X] Graph -> Tree
  - [X] Queue
  - [ ] Priority Queue
  - [ ] Double-ended priority queue
  - [ ] Double-ended queue

## Programming Paradigms (3/16)

  - [X] Protocol-Oriented
  - [X] OOP
  - [X] Functional
  - [ ] React Native
  - [ ] RxSwift
  - [ ] RxRealm, RxDataSources

## Libs, frameworks, pods, Kit's

- [ ] ObjectMapper (pod)
- [ ] Charts (pod)
- [ ] Payments and subscription
- [ ] Moya
- [ ] BLE (Bluetooth Low Energy)
- [ ] AVFoundation
- [ ] AVKit
- [ ] ARKit
- [ ] HomeKit
- [ ] MedKit
- [ ] MapKit
- [ ] YandexMap
- [ ] [`Animations`]()
  - [ ] Core Graphics
  - [ ] Core Animation
  - [ ] Transformation
- [ ] [`tvOS`]()
  - [ ] Focus interactions
  - [ ] WatchKit
- [ ] [`TDD utils`]()
  - [ ] Specta
  - [ ] Expecta
  - [ ] OCMock
- [X] PullUpController
- [X] Kingfisher

<br><br>

![Skills matrix](matrix.png)

## Контакты для связи:
* telegram: [@yanapreobrazhenskaya](https://t.me/yanapreobrazhenskaya)
* email: [yanak.preobrazhenskaya@yandex.ru](mailto:yanak.preobrazhenskaya@yandex.ru)
* github: [https://github.com/preobrazhenskaya](https://github.com/preobrazhenskaya)
