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
* 

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
  
![](https://i.stack.imgur.com/gzXIl.png)

* ViewController Lifecycle:
  * viewDidLoad() - layout has been loaded
  * viewWillAppear() - view is about to be shown
  * viewDidAppear() - view has been shown
  * viewWillDisappear() - view is about to go away
  * viewDidDisappear() - view has gone away
  
 **Guess the Flag** Project on Hacking with Swift (Days 19-21): [here](https://www.hackingwithswift.com/read/2/overview)
