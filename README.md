A logging framework for Objective-C projects. Based on Brenwill workshop's Flexible iOS Logging Framework: http://brenwill.com/2010/flexible-ios-logging/ 

#FEATURES

* Just one file - use as an alternative to NSLog
* Supports multiple log levels - Debug, Info, Warning, Error, Trace
* Performance: Logging can be compiled in our out of code with one flag. 
* Supports multiple formats - line numbers, file, etc. 

#USAGE IS SIMPLE

* Just include OCLogTemplate.h. Can be installed via CocoaPods too, for use as a transitive dependency in libraries, etc: `pod 'OCLogTemplate'`. 

```objc
LogDebug(@"Message: %@", formatArg);
```

#FULLY FLEDGED LOGGING TOOLS

* NSLogger
* CoocaLumberjack








