# iOS-learning
This is the repository where I track my iOS-development learning progress

# Useful resources

## Markdown
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Markdown Guide](https://www.markdownguide.org/basic-syntax/)

## Tutorials
* [Hacking with Swift](https://www.hackingwithswift.com)
* [Swift Book](https://swiftbook.ru)

## Articles
### Grand Central Dispatch
* [GCD Tutorial (RU)](https://medium.com/@SwiftBook.ru/туториал-по-grand-central-dispatch-для-swift-часть-1-2-993768ad4947)

## Medium
* [UIAlertController](https://medium.com/swift-india/uialertcontroller-in-swift-22f3c5b1dd68)
* [Core Data](https://medium.com/better-programming/a-light-intro-to-core-data-part-un-e344f9d1528)

## Advices
* [What does it take to become an iOS Developer](https://medium.com/devslopes-blog/what-does-it-take-to-become-an-ios-developer-fd8150942de1)

## December

### December 30
Digging deep into Optionals on Hacking with Swift (Day 12): [here](https://www.hackingwithswift.com/100/12)

Learned about:
* Declaring variables with ? !
* Unwrapping optionals with **let** and **guard let**
* Force unwrapping using !
* Implicitly unwrapped optionals
* Nil coalescing (??)
* Optional chaining (a?.b?.c())
* Optional try (try? and try!)
* Failable Initializer (init?())
* Typecasting (as? and as!)

### December 31

* Repeat optionals

Digged deep into Closures on Hacking with Swift (Days 6, 7): [here](https://www.hackingwithswift.com/100/6) and [here](https://www.hackingwithswift.com/100/7)

Learned about:
* Why does Swift need closures?
* Basic closure syntax
* Passing closures as parameters in functions
* Trailing closure syntax
* Passing closures with parameters to function
* Implementing reduce() function (using +, * operators as closures)
* Shorthand names (including $0, $1, ...)
* Returning closures from functions
* Capturing values

Resources:
* [Closure syntax in Swift](http://goshdarnclosuresyntax.com)

### January 1

**Storm Viewer** Project on Hacking with Swift, part 1 (Day 16): [here](https://www.hackingwithswift.com/100/16)

### January 2

**Storm Viewer** Project on Hacking with Swift, part 2(Day 17): [here](https://www.hackingwithswift.com/100/17)

Learned about:
* Every view controller have optional properties **storyboard?** that contains the storyboard they were loaded from or nil and **navigationController?** that contains the navigation controller they are inside if it exists, or nil otherwise
* Instantiating view Controller:
```swift
if let vc = storyboard?.instantiateViewController(withIdentifier: "ID") as? MyViewController {
  // do something
  navigationController?.pushViewController(vc, animated: true)
}
```
* UIImageView Content Mode property:
  * Scale to Fill
  * Aspect Fit
  * Aspect Fill

* ViewController Lifecycle:
  * viewDidLoad() - layout has been loaded
  * viewWillAppear() - view is about to be shown
  * viewDidAppear() - view has been shown
  * viewWillDisappear() - view is about to go away
  * viewDidDisappear() - view has gone away
  
 **Guess the Flag** Project on Hacking with Swift (Days 19-21): [here](https://www.hackingwithswift.com/read/2/overview)
 **Social Media** Project on Hacking with Swift (Day 22): [here](https://www.hackingwithswift.com/read/3/overview)
 
 Learned about **UIActivityViewController**
 
 ### January 3
 
 **Flag Viewer** Milestone Project on Hacking with Swift (Day 23): [here](https://www.hackingwithswift.com/100/23)
 
 **Easy Browser** Project on Hacking with Swift (Days 24-26): [here](https://www.hackingwithswift.com/read/4/overview)
 
 What I started learning (needs to be digged deeper):
 * WKWebView
 * UIToolBar
 * URL & URLRequest
 * UIProgressView
 * KVO
 
 ### January 4
 
 **Word Scramble** Project on Hacking with Swift (Days 27-29): [here](https://www.hackingwithswift.com/read/5/overview)
 
  What I started learning (needs to be digged deeper):
  * Capture lists (strong, weak and unowned capturing)
  * Strong reference cycles
  * NSRange
  * UITextChecker
  * Adding UIBarButtonItems to navigation bar
  
  ### January 6
  
  **Auto Layout** Project on Hacking with Swift (Days 30-31): [here](https://www.hackingwithswift.com/read/6/overview)
  
  What I started learning (needs to be digged deeper):
  * Equal heights, Aspect Ratio contraints
  * VFL (Visual Formatting Language)
  * Anchors
  
  **Level Up in Auto Layout** course on Udemy: [here](https://www.udemy.com/course/level-up-in-auto-layout/)
  
  Lessons 1-8:
  * Anchors, how they work
  * SafeAreaGuides
  * DefaultMarginGuides
  * ReadableContentGuides

### January 7

**Level Up in Auto Layout**
Lessons 9-21:
* UILayoutGuide
* Intrinsic Content Size
* Content Hugging & Compression Resistance
* UILayoutPriority

### January 9
Started working with StackView programmatically

### January 10

Milestone Project on Hacking with Swift (Day 32): [here](https://www.hackingwithswift.com/100/32)

### January 11

 **Whitehouse Petitions** Project on Hacking with Swift (Days 33-35): [here](https://www.hackingwithswift.com/read/7/overview)
 * Codable protocol
 * UITabBarController
 
 ### January 12
 
  **Swift Words** Project on Hacking with Swift (Days 36-38): [here](https://www.hackingwithswift.com/read/8/overview)
  * Auto Layout (programmatically)
  * Property observers (didSet() and willSet())
  * Adding targets to buttons (addTarget())
  * Useful methods: enumerated(), joined(), replacingOccurrences(), trimmingCharacters()
  
  ### January 13
  
  Getting familiar with GCD (difficult to understand):
  * [Link 1](https://www.raywenderlich.com/5370-grand-central-dispatch-tutorial-for-swift-4-part-1-2)
  * [Link 2](https://m.habr.com/ru/post/320152/)
 

  Key words:
  * Types of Queues: main (serial), global (concurrent), custom
  * QoS classes: user-interactive, user-initiative, utility, background, default
  * Types of tasks: synchronous, asynchronous
