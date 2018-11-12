Unbox and Alamofire in Swift 3
===

**Project dependencies and setup**
* Xcode 8
* Swift 3
* ————
* Alamofire (HTTP networking lib)
* Unbox (Swift JSON decoder)
* UnboxedAlamofire (Custom Response Serializer for Unbox)
* AlamofireImage (Image response serializer for Alamofire)
* SnapKit (Swift Autolayout DSL)
* —————
* Git `git clone git@github.com:salsysd/swift-for.git`
* Cocoapods (1.5) - `pod install`

---

### Protocol Oriented Programming in Swift Code Example

This basic example came from a coding exercise I did while back i
The reason I made this exercise a public repo is to provide an example of using [Unbox](https://github.com/JohnSundell/Unbox) with [Alamofire](https://github.com/serejahh/UnboxedAlamofire) in Swift 3! Plus I had fun doing it!

I think this is a very simple/clean solution to a very common task iOS developers face regularly.
The **serialization** is handled very nicely as _property types_ are automatically **decoded**. All mismatched values are gracefully handled through a **single exception type**, making error handling super simple!
This prevents all your models saturated with **optional properties**, in which you later have to unwrap, guard or add more LOC at some point.

And best of all its a light weight solution that you can use with your protocol oriented swift apps!

---
#### ** Caveat

_This code base no longer properly works, as the 3rd party API I was using at the time has since made their API private!_

