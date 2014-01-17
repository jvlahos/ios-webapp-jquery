## iOS Web App Boilerplate

The following is a boilerplate of necessary components for designing iOS web applications. It assumes that you're interested in making the user add your web application to their homescreen from Mobile Safari before utilizing the application. Thus, it does a variety of device detection when the page loads and adds classes to the `<body>` tag for you to be able to contextually show and hide content based upon the device. In this version, we use jQuery for the device detection.

When viewing on iOS, you'll also notice that I added a basic animating arrow to point to the "Share" button area. For iPhone, it's in the bottom address bar. For iPad, it's in the top address bar.

#### Device Detection, `<body>` Classes

**Desktop or Mobile**
+ Desktop `.is-desktop`
+ Mobile (Phone/Tablet)  `.is-mobile`

**iOS Devices**
+ iPhone `.is-iphone`
+ iPhone 5 `.is-phone-5`
+ iPad `.is-ipad`

**iOS Browsers**
+ iOS Safari `.is-ios-safari`
+ iOS Chrome `.is-ios-chrome`
+ iOS Standalone (Webapp) `.is-ios-standalone`

**Otherwise...**
+ Other `.is-not-idevice`