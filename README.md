# iOS app for elegant rendering of mobile-friendly websites
An elegant iOS app for rendering websites efficiently with JS callback implementation and fancy loading screen.

An experiment to get used with auto-constraints, Swift and back and forth callbacks between WKWebView (after initially using an UIWebView) and JS.

With audio play based on JS calls to save bandwidth the files are in the app.


# Main features
  * Framework in place to execute JS on the site from the app and call functions in the app from within the website
  * Elegant loading screen, with animated logo, fading in and out as pages load
  * Swipe to the right for BACK and to the left for FORWARD
  * Works in all orientations thanks to auto-constraints + the website being nicely mobile compatible

# How to use
Simply change the URL in ViewController.swift and update the icons and logos in the Assets manager. For more complex behaviour, take a quick look at Test/index.html and at the code in the ViewController to quickly setup JS communication between the app and the website and send anything from Geolocation data to user input.

## Prepare your website
Make sure your website is mobile responsive & lets browser know it.

```
<meta name="viewport" content="width=device-width, initial-scale=0.7, maximum-scale=0.8, minimum-scale=0.9, user-scalable=no">
```

# Small test
  To test the JS callbacks between the app and a site, the Test/index.html file can be uploaded to a host and accessed.

# Need an Android version?
https://github.com/nenuadrian/android-website-elegant-rendering

# GNU GENERAL PUBLIC LICENSE
The GNU GPL is the most widely used free software license and has a strong copyleft requirement. When distributing derived works, the source code of the work must be made available under the same license.

