# razorpay-pod

[![Version](https://img.shields.io/cocoapods/v/razorpay-pod.svg?style=flat)](http://cocoapods.org/pods/razorpay-pod)
[![License](https://img.shields.io/cocoapods/l/razorpay-pod.svg?style=flat)](http://cocoapods.org/pods/razorpay-pod)
[![Platform](https://img.shields.io/cocoapods/p/razorpay-pod.svg?style=flat)](http://cocoapods.org/pods/razorpay-pod)

This repository implements pod for Razorpay's iOS Framework.

## Usage

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Installation | Docs

### Note:
If your integrating this on Objective-C please replace the line
```
#import <Razorpay/Razorpay.h>
```
with 
```
# import <Razorpay/Razorpay-Swift.h> in your viewcontroller.m file
```

razorpay-pod is available through [CocoaPods]. To install
it, simply add the following line to your Podfile

For version 1.1.4 (Framework Compiled in Swift version 5.1, Use it if you are using Xcode version 11 and above)

```ruby
pod 'razorpay-pod'
```

### Note:
for Swift 5, use : - 

```ruby
pod 'razorpay-pod', '1.1.1'
```

Refer to the documentation from [here](https://razorpay.com/docs/payment-gateway/ios-integration/standard/) 

## Contributing

See the [CONTRIBUTING] document.
Thank you, [contributors]!

## License

razorpay-pod  is free software, and may be redistributed
under the terms specified in the [LICENSE] file.

We :heart: open source software!
See [our other supported plugins / SDKs]
or [contact us](mailto:integrations@razorpay.com?subject=Help with iOS Integration using CocoaPods) to help you with integrations.

  [CocoaPods]: http://cocoapods.org
  [razorpay.com/mobile]: https://razorpay.com/mobile
  [CONTRIBUTING]: CONTRIBUTING.md
  [contributors]: https://github.com/razorpay/razorpay-pod/graphs/contributors
  [LICENSE]: /LICENSE
  [our other supported plugins / SDKs]: https://razorpay.com/integrations "List of our supported integrations"
