# Awesome RubyMotion

A categorized community-driven collection of awesome RubyMotion example apps, libraries, tools, frameworks, software and resources.

Sharing, suggestions and contributions are always welcome! Please take a look at the [contribution guidelines and quality standard](https://github.com/motion-open-source/awesome-rubymotion/blob/master/CONTRIBUTING.md) first.

[RubyMotion](http://www.rubymotion.com) is a Commercial product created by [HipByte](http://www.hipbyte.com).

Thanks to Clay Allsopp who created the Motion Toolbox list.
Thanks to all [contributors](https://github.com/motion-open-source/awesome-rubymotion/graphs/contributors), you're awesome and wouldn't be possible without you!

- [Awesome RubyMotion](#awesome-rubymotion)
  - [Libraries, Frameworks and Wrappers](#libraries-frameworks-and-wrappers)
    - [Android](#android)
    - [Apple API Wrappers](#apple-api-wrappers)
    - [Authorization](#authorization)
    - [Data Protocols](#data-protocols)
    - [Database](#database)
    - [Development Utilities](#development-utilities)
      - [Project Management](#project-management)
      - [Dependencies Management](#dependencies-management)
      - [Screenshots](#screenshots)
      - [Debugging & Error Reporting](#debugging-&-error-reporting)
      - [Testing](#testing)
      - [Updates](#updates)
    - [Device support](#device-support)
    - [Encryption](#encryption)
    - [Frameworks](#frameworks)
      - [ProMotion](#promotion)
    - [Game Development](#game-development)
    - [Graphical User Interface](#graphical-user-interface)
      - [GUI Frameworks](#gui-frameworks)
      - [Autolayout](#autolayout)
      - [Input](#input)
      - [iOS](#ios)
      - [Forms](#forms)
      - [Menu's & Toolbars](#menus-&-toolbars)
      - [Icons](#icons)
      - [Hybrid](#hybrid)
      - [Element Wrappers](#element-wrappers)
    - [Graphic Libraries](#graphic-libraries)
    - [Models & CoreData](#models-&-coredata)
    - [Networking](#networking)
    - [SaaS API Wrappers](#saas-api-wrappers)
      - [Parse.com](#parsecom)
    - [Scheduling](#scheduling)
    - [Software Design Patterns](#software-design-patterns)
    - [Templates](#templates)
    - [Utility Bundles](#utility-bundles)
  - [Apps](#apps)
    - [Example Android Apps](#example-android-apps)
    - [Example iOS Apps](#example-ios-apps)
    - [Example OSX Apps](#example-osx-apps)
    - [Example tvOS Apps](#example-tvos-apps)
    - [Open Source OS X Apps](#open-source-os-x-apps)
    - [Open Source iOS Apps](#open-source-ios-apps)
    - [Propriety OS X Apps](#propriety-os-x-apps)
    - [Propriety iOS Apps](#propriety-ios-apps)
  - [Books](#books)
  - [Tutorials](#tutorials)
    - [iOS Tutorials](#ios-tutorials)
    - [OS X Tutorials](#os-x-tutorials)
    - [Tutorial Screencasts](#tutorial-screencasts)
  - [Resources](#resources)
- [Other Awesome Lists](#other-awesome-lists)

## Libraries, Frameworks and Wrappers

### Android

Because Android support is quite new we're keeping the libraries together in this section.

* [BluePotion](https://github.com/infinitered/bluepotion) - BluePotion is the Android version of RedPotion. (ALPHA)
* [Toaster](https://github.com/jamonholmgren/toaster) - RubyMotion-android 'Toast' gem. Makes working with Android toasts really easy!
* [motion-maven](https://github.com/HipByte/motion-maven) - motion-maven lets you automatically manage 3rd-party Java dependencies in RubyMotion for Android projects using Maven

### Apple API Wrappers
* [motion.h](https://github.com/kastiglione/motion.h) - Expose iOS and OS X system libraries in RubyMotion.
* [MapKitWrapper](https://github.com/weibel/MapKitWrapper) - Make dealing with MapKit less painful for RubyMotion.
* [Medic](https://github.com/ryanlntn/medic) - Is HealthKit's verbose and convoluted API driving you mad? Quick! You need a medic!
* [motion-accessibility](https://github.com/austinseraphin/motion-accessibility) - Making accessibility accessible. RubyMotion Wrappers around the UIAccessibility protocols. Easily interact with Apple's impressive array of assistive technologies, including VoiceOver.
* [Vendor](https://github.com/holgersindbaek/Vendor) - A RubyMotion StoreKit Wrapper that allows you to buy, restore and get product info on your in app purchases and subscriptions.
* [motion-addressbook](https://github.com/alexrothenberg/motion-addressbook) - A RubyMotion wrapper around the iOS & OSX Address Book frameworks.
* [Helu](https://github.com/ivanacostarubio/helu) - A RubyMotion wrapper for the Store Kit Framework
* [motion-speech](https://github.com/macfanatic/motion-speech) - Easy text-to-speech wrapper for AVSpeechSynthesizer in iOS 7.
* [motion-keychain](https://github.com/IconoclastLabs/motion-keychain) - The motion-keychain gem is a simple wrapper for Keychain on iOS and OS X. Makes using Keychain APIs as easy as NSUserDefaults.
* [motion-settings-bundle](https://github.com/qrush/motion-settings-bundle) - Create a Settings.bundle for your RubyMotion app
* [Motion-Social](https://github.com/ivanacostarubio/motion-social) - Wrapper around the Social Framework

### Authorization
* [can_i](https://github.com/macfanatic/can_i) - A RubyMotion wrapper providing a simple DSL for role authorization, similar to the CanCan gem.

### Data Protocols
* [motion-csv](https://github.com/OTGApps/motion-csv) - A RubyMotion friendly CSV parser gem.
* [meteor-motion](https://github.com/whitesmith/meteor-motion) - A wrapper for Meteor DDP with support for Motion Model

### Database
* [motion-firebase](https://github.com/colinta/motion-firebase) - A RubyMotion wrapper for the Firebase SDK.
* [yapper](https://github.com/kareemk/yapper) - ORM for YapDatabase which is schemaless, very fast (thanks to YapDatabase's architecture), has chainable criteria, one-many relationships, on-the-fly reindexing and is thread-safe.
* [couchmotion](https://github.com/jannishuebl/couchmotion) - API for using Couchbase(CouchDB) a schemaless database with Rubymotion for Android and iOS
* [motion-sqlite3](https://github.com/mattgreen/motion-sqlite3) - A minimal wrapper over the SQLite 3 C API for RubyMotion

### Development Utilities


#### Project Management
* [motion-schemes](https://github.com/siuying/motion-schemes) - Expand RubyMotion build system to support building multiple apps from one project.
* [motion-config-vars](https://github.com/jamescallmebrent/motion-config-vars) - Heroku-style environment configuration for RubyMotion.
* [motion-env](https://github.comclayallsopp/motion-env) - Sync ENV variables between Rakefile and RubyMotion
* [motion-my_env](https://github.com/ainame/motion-my_env) - Simple environment variable solution for RubyMotion

#### Dependencies Management
* [MotionBundler](https://github.com/archan937/motion-bundler) - Require and mock Ruby gems (including their dependencies) within RubyMotion applications.
* [motion-acknowledgements](https://github.com/OTGApps/motion-acknowledgements) - This gem makes it easy to include the CocoaPods acknowledgements file in your application.

#### Screenshots
* [motion-screenshots](https://github.com/clayallsopp/motion-screenshots) - Automatic screenshots for your RubyMotion apps
* [motion-launchimages](https://github.com/brendanjcaffrey/motion-launchimages) - Automate taking your RubyMotion launch images

#### Debugging & Error Reporting
* [motion-reveal](https://github.com/diogoandre/motion-reveal) - Easy way to add the Reveal framework to your Rubymotion project
* [Crittercism](https://github.com/andrewhavens/crittercism) - Easily add crash reporting to your RubyMotion app with Crittercism.
* [motion_print](https://github.com/OTGApps/motion_print) - A RubyMotion friendly console logger and debugging tool. Use it to output pretty formatted objects to the REPL.
* [awesome_print_motion](https://github.com/michaeldv/awesome_print_motion) - A port of the awesome_print gem to RubyMotion.
* [motion-colorize](https://github.com/clayallsopp/motion-colorize) - Add some color to your RubyMotion output.
* [motion-xray](https://github.com/colinta/motion-xray) - An iOS Inspector that runs inside your app, so you can debug and analyze from your device in real-world situations.

#### Testing
* [MotionFixtures](https://github.com/farcaller/motion-fixtures) - Simple support for test fixtures.
* [WebStub](https://github.com/nathankot/webstub) - Easily stub out HTTP responses in RubyMotion specs.
* [motion-stump](https://github.com/siuying/motion-stump) - Stubbing and mocking for RubyMotion.
* [motion-frank](https://github.com/cyrusinnovation/motion-frank) - A gem to use integrate frank-cucumber into RubyMotion projects.
* [motion-crescentia](https://github.com/Shirk/motion-crescentia) - RubyMotion wrapper for the Calabash BDD framework.
* [motion-facon](https://github.com/chuyeow/facon) - A port of Facon mocking library to RubyMotion.
* [guard-motion](https://github.com/mordaroso/guard-motion) - Guard::Motion automatically run your RubyMotion specs (much like autotest)
* [motion-instabug](https://github.com/bmichotte/motion-instabug) - motion-instabug allows RubyMotion projects to easily embed the Instabug SDK and be submitted to the Instabug platform.

#### Updates
* [motion-sparkle](https://github.com/webcracy/motion-sparkle) - motion-sparkle makes it easy to use Sparkle with your RubyMotion projects

### Device support
* [motion-distance](https://github.com/willrax/motion-distance) - Easy distance tracking for RubyMotion projects.
* [motion-capture](https://github.com/dblandin/motion-capture) - An AVFoundation wrapper to support custom camera controllers.

### Encryption
* [motion-bitmask](https://github.com/buffpojken/motion-bitmask) - A simple implementation of generic bitmasks for RubyMotion.
* [rm-digest](https://github.com/tmeinlschmidt/rm-digest) - MD5 and SHA1 digest for RubyMotion (gem)

### Frameworks
* [BubbleWrap](http://rubymotion.github.io/BubbleWrap) - A collection of (tested) helpers and wrappers used to wrap CocoaTouch code and provide more Ruby like APIs.
* [Sugarcube](https://github.com/rubymotion/sugarcube) - These extensions hope to make development in RubyMotion more enjoyable by tacking 'UI' methods onto the base classes (String, Fixnum, Numeric). With sugarcube, you can create a color from an integer or symbol, or create a UIFont or UIImage from a string.
* [MotionPrime](http://prime.droidlabs.pro) - MotionPrime is yet another framework written on RubyMotion for creating really fast iOS applications.
* [RubyMotionQuery - RMQ](http://infinitered.com/rmq) - UI Library for RubyMotion. Fast, non-polluting, & chaining; it’s like jQuery for RubyMotion + stylesheets, animations, events, and more.
* [Elevate](https://github.com/mattgreen/elevate) - Stop scattering your domain logic across your view controller. Consolidate it to a single conceptual unit with Elevate.
* [RedPotion](https://github.com/infinitered/redpotion) - RedPotion combines RMQ, ProMotion, CDQ, AFMotion, and more for the perfect mix to develop in RubyMotion fast.
* [BluePotion](https://github.com/infinitered/bluepotion) - BluePotion is the Android version of RedPotion. (ALPHA)
* [motion-support](https://github.com/rubymotion/motion-support) - A port of ActiveSupport to RubyMotion

#### ProMotion

There are a lot of ProMotion libraries. Seperate Section.

* [ProMotion](https://github.com/infinitered/ProMotion) - A full featured RubyMotion framework that makes iPhone development less like Objective-C and more like Ruby, designed to get up and running fast.
* [ProMotion-XLForm](https://github.com/bmichotte/ProMotion-XLForm) - ProMotion-XLForm is a ProMotion plugin for XLForm
* [ProMotion-form](https://github.com/infinitered/ProMotion-form) - ProMotion::FormScreen - forms the ProMotion way!
* [ProMotion-iap](https://github.com/infinitered/ProMotion-iap) - ProMotion-iap is in-app purchase notification support for the popular RubyMotion gem ProMotion.
* [ProMotion-menu](https://github.com/infinitered/ProMotion-menu) - RubyMotion gem allowing you to easily setup a facebook or Path style hidden slide menu easily with the ProMotion gem.
* [ProMotion-push](https://github.com/infinitered/ProMotion-push) - Push notification support for ProMotion.
* [ProMotion-map](https://github.com/infinitered/ProMotion-map) - ProMotion::MapScreen gem. Extracted from ProMotion core.

### Game Development
* [Joybox](https://github.com/rubymotion/Joybox) - Cocos2D & Box2D Wrapper for RubyMotion.

### Graphical User Interface

#### GUI Frameworks
* [IB](https://github.com/rubymotion/ib) - RubyMotion Interface Builder support, including outlets and actions.
* [Teacup](https://github.com/colinta/teacup) - A community-driven DSL for creating user interfaces on the iPhone.
* [MotionKit](https://github.com/motion-kit/motion-kit) - The RubyMotion layout and styling gem.
* [motion-stylez](https://github.com/FluffyJack/motion-stylez) - RubyMotion stylesheet library based off RMQ

#### Autolayout
* [purplish-layout](http://hboon.com/purplish-layout/) - A RubyMotion wrapper for Auto Layout on iOS and OS X
* [motion-layout](https://github.com/qrush/motion-layout) - A nice way to use Auto Layout in your RubyMotion app.

#### Input
* [MIMInputToolbar](https://github.com/FluffyJack/MIMInputToolbar) - Input accessory view for your UITextFields and UITextViews.
* [Motion-Wiretap](https://github.com/colinta/motion-wiretap) - A wrapper for KVO, gestures, UIControl events, and procs. Okay okay it's pretty much ReactiveCocoa in RubyMotion.

#### iOS
* [Geomotion](https://github.com/clayallsopp/geomotion) - Better iOS Geometry with RubyMotion.
* [Walt](https://github.com/clayallsopp/Walt) - Frictionless, hash-based iOS animations.
* [AccordionView](https://github.com/toamitkumar/AccordionView) - Create and add Accordions to your UIViews.
* [motion-wizard](https://github.com/ijpiantanida/motion-wizard) - A gem to create wizard like view controllers in iOS
* [motion-imager](https://github.com/OTGApps/motion-imager) - An interactive iOS image viewer that does it all: double tap to zoom, flick to dismiss, et cetera.
* [Motion Swipe](https://github.com/dam13n/motion-swipe) - Tinder-like swipe gem.
* [motion-dynamic-type](https://github.com/FluffyJack/motion-dynamic-type) - Simplifying even further iOS 7's Dynamic Type
* [Indoctrinator](https://github.com/ryanlntn/indoctrinator) - Indoctrinator is a RubyMotion gem that provides a Path style tutorial view for iOS applications.
* [motion-egg](https://github.com/GantMan/motion-egg) - Add an Easter egg to your app

#### Forms
* [Formotion](https://github.com/clayallsopp/formotion) - Painless, productive views on iOS.
* [motion-form](https://github.com/dblandin/motion-form) - RubyMotion forms made easy

#### Menu's & Toolbars
* [MenuMotion](https://github.com/codelation/menu-motion) - A RubyMotion wrapper for creating OS X menus
* [better_toolbar](https://github.com/FluffyJack/better_toolbars) - A better way to work with toolbars
* [EverydayMenu](https://github.com/henderea/everyday-menu) - An easy way to define menu items and visually lay out menus for your OSX apps.
* [StatusBar](https://github.com/holgersindbaek/status_bar) - Notifications for the statusbar.

#### Icons
* [Ion_in_Motion](https://github.com/Brian-Egan/ion_in_motion) - Ridiculously easy use of IonIcons in UILabels, UIButtons, UIImages and more. IonIcons: http://ionicons.com/
* [Moticons](https://github.com/andrewhavens/moticons) - The easiest way to add icons to your RubyMotion app.

#### Hybrid
* [Motion Floating Action Button](https://github.com/dam13n/motion-floating-action-button) - Material design floating action button.
* [motion-awesome](https://github.com/derailed/motion-awesome) - DSL to easily create buttons and labels using the wonderful font-awesome library.
* [motion-hybrid](https://github.com/balvig/motion-hybrid) - RubyMotion framework for easily making hybrid webview-centric iOS apps

#### Element Wrappers
* [simple_si](https://github.com/forrestgrant/simple_si) - A RubyMotion wrapper for SIAlertView
* [motion-blitz](https://github.com/dblandin/motion-blitz) - RubyMotion wrapper for SVProgressHUD

### Graphic Libraries
* [Motion-Plot](https://github.com/toamitkumar/motion-plot) - A RubyMotion wrapper for CorePlot.
* [motion-ocr](https://github.com/ferdev/motion-ocr) - A RubyMotion wrapper for the OCR engine Tesseract.

### Models & CoreData
* [MotionModel](https://github.com/sxross/MotionModel) - Simple Model, Validation, and Input Mixins for RubyMotion.
* [NanoStoreInMotion](https://github.com/siuying/NanoStoreInMotion) - Wrapper for NanoStore, a lightweight schema-less key-value document database based on sqlite.
* [MotionDataWrapper](https://github.com/macfanatic/motion_data_wrapper) - Intuitive querying and persistence of CoreData models, using Xcode to define entities, validations, relationships and migrations.
* [Core Data Query - CDQ](https://github.com/infinitered/cdq) - Easy-to-set-up library for using Core Data without Xcode
* [motion-bindable](https://github.com/nathankot/motion-bindable) - Create two-way bindings between your models and view objects (or any other object.)
* [Turnkey](https://github.com/seldomatt/TurnKey) - Utility for saving custom objects to NSUserDefaults using NSKeyedArchiver and NSKeyedUnarchiver

### Networking
* [RackMotion](https://github.com/drewbug/RackMotion) - Intercept and alter HTTP requests and responses in RubyMotion
* [motion-net-service](https://github.com/fearoffish/motion-net-service) - A RubyMotion wrapper providing a simple DSL for the Bonjour (NSNetService) zero configuration network protocol.
* [apex](https://github.com/infinitered/apex) - Apex is a RubyMotion web framework for OS X. It uses GCDWebServer under the hood and provides a Sinatra-like router and DSL.
* [AFMotion](https://github.com/clayallsopp/afmotion) - A RubyMotion wrapper for AFNetworking.

### SaaS API Wrappers
* [motionscan](https://github.com/jjaffeux/Motionscan) - A RubyMotion wrapper around the image recognition SDK of Moodstocks.com.
* [motion-phrase](https://github.com/phrase/motion-phrase) - Connect your RubyMotion project with PhraseApp for easy app internationalization. Translatable strings are exported while browsing the app and then managable through the PhraseApp translation editor.
* [purple-monkey](https://github.com/hboon/purple-monkey) - Barebones wrapper for working with MailChimp on iOS/OS X using RubyMotion
* [motion-tickspot](https://github.com/codelation/motion-tickspot) - A RubyMotion wrapper for the http://tickspot.com API that works on iOS and OS X.
* [motion-aws](https://github.com/jamonholmgren/motion-aws) - Provides iOS and OSX connectivity to AWS services.
* [motion-ocean](https://github.com/brianpattison/motion-ocean) - A RubyMotion wrapper for the http://digitalocean.com API v2.0
* [sox](https://github.com/brilliantfantastic/sox) - A RubyMotion wrapper for the Freshbooks API
* [Twittermotion](https://github.com/clayallsopp/twittermotion) - RubyMotion wrapper for the iOS Twitter API.
* [under-os-image](https://github.com/under-os/under-os-image) - The new simplified images processing API for the http://under-os.com/ project
* [motion-giphy](https://github.com/willrax/motion-giphy) - A nice wrapper around the http://giphy.com API.
* [motion-installr](https://github.com/FluffyJack/motion-installr) - Ad-hoc deployment using the amazing Installr service! https://www.installrapp.com/
* [under-os-image](https://github.com/under-os/under-os-image) - The new simplified images processing API for the http://under-os.com/ project
* [MotionPanel](https://github.com/tombroomfield/motion_panel) - A native RubyMotion wrapper around the Mixpanel API.
* [MotionPaddle](https://github.com/henderea/motion-paddle) - A RubyMotion gem for the Paddle framework
* [Algolia Offline Search](https://github.com/algolia/motion-algolia-search) - Simple integration of Algolia Offline Search SDK (http://www.algolia.com/) in your RubyMotion application.

#### Parse.com
* [Motion Parse](https://github.com/tkadauke/motion-parse) - Thin wrapper around the Parse SDK for RubyMotion.
* [ParseModel](https://github.com/adelevie/ParseModel) - An Active Record pattern for your Parse models.
* [Parsistence](https://github.com/infinitered/Parsistence) - A Parse.com wrapper similar to persistence.js.

### Scheduling
* [motion-launchpad](https://github.com/macfanatic/motion-launchpad) - A gem providing a DSL allowing you to schedule events on specific launches of your application.  'motion-takeoff' only supplies displaying an alert, this gem executes any code block.
* [motion-takeoff](https://github.com/OTGApps/motion-takeoff) - A gem for scheduling stuff. You can use motion-takeoff to display messages at certain launch counts and schedule local notifications.


### Software Design Patterns

* [motion-pool](https://github.com/wooandoo/motion-pool) - A pool for RubyMotion.
* [motion-state-machine](https://github.com/opyh/motion-state-machine) - A Grand Central-aware, simple syntax for state machines.
* [motion-objection](https://github.com/atomicobject/motion-objection) - RubyMotion wrapper for Objection
* [weak_attr_accessor](https://github.com/hboon/weak_attr_accessor) - Adds weak_attr_accessor that wraps objects with WeakRef, for RubyMotion

### Templates

App project templates

* [MotionTemplate](https://github.com/IconoclastLabs/MotionTemplate) - A clean RubyMotion project for quickly templating a styled application.
* [promotion-template](https://github.com/jamonholmgren/promotion-template) - Utlize the bells and whistles of ProMotion to hit the ground running.
* [rubymotion_generators](https://github.com/andyw8/rubymotion_generators) - Provides boilerplate code templates for RubyMotion

### Utility Bundles

## Apps

### Example Android Apps
* [Android RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/android) - A collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.
* [rubymotion-android-cookbook](https://github.com/IconoclastLabs/rubymotion-android-cookbook) - Awesome rm cookbook examples for android

### Example iOS Apps
* [IOS RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/ios) - A collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.
* [Custom Table View Cell with IB and RM](https://github.com/hackedunit/custom-cell) - Custom Table View Cell using Interface Builder with RubyMotion
* [MotionKit iOS Samples](https://github.com/motion-kit/motion-kit/tree/master/samples/ios) - iOS Example Apps made with MotionKit

### Example OSX Apps

* [OSX RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/osx) - A collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.
* [mctv-mac-osx](https://github.com/Motioncasts/mctv-mac-osx) - Demo Pomodoro Technique Timer App
* [motion-osx-ib](https://github.com/MarkVillacampa/motion-osx-ib) - This is an example on how to use the ib gem in a OSX RubyMotion 2.0 application.
* [motion-treeview-coredata](https://github.com/mipmip/motion-treeview-coredata) - A port of the example from Connecting NSOutlineView to Core Data in 10.6 Part 1: Ordered Trees to RubyMotion.
* [rm-osx-kartta](https://github.com/masal/rm-osx-kartta) - RubyMotion / OSX map viewer for Finnish topographical maps.
* [MotionKit OSX Samples](https://github.com/motion-kit/motion-kit/tree/master/samples/osx) - OSX Example Apps made with MotionKit

### Example tvOS Apps

* [tvOS RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/tvos) - A collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.

### Open Source OS X Apps

### Open Source iOS Apps

* [buku-live-ios-rubymotion](https://github.com/mswezey/buku-live-ios-rubymotion) - iOS app built in rubymotion for music festival RFID activation

### Propriety OS X Apps
### Propriety iOS Apps

## Books
* [RubyMotion, iOS Development with Ruby](http://www.allitebooks.com/rubymotion/) - Author: Clay Allsopp (free download)
* [Building Mac OS X apps with RubyMotion](http://kickcode.com/building-mac-os-x-apps-with-rubymotion/) - Author: Elliott Draper
* [Instant RubyMotion App Development](https://www.packtpub.com/application-development/instant-rubymotion-app-development) - Author: Gant Laborde
* [RubyMotion iOS Development Essentials](https://www.packtpub.com/application-development/rubymotion-ios-development-essentials) - Author: Abhishek Nalwaya, Akshat Paul

## Tutorials

### iOS Tutorials

* [Tubymotion Tutorial](http://rubymotion-tutorial.com) - Make iOS Apps With Ruby
* [Fabric & RubyMotion Tutorial](https://medium.com/@sammybauch/making-fabric-play-nice-with-rubymotion-48a593ac22d4#.uxe9mmczw) - Making Fabric Play Nice with RubyMotion
* [Facebook iOS SDK](http://gavinmorrice.com/blog/posts/30-how-to-use-the-facebook-ios-sdk-in-your-rubymotion-project) - How To Use the Facebook iOS SDK In Your RubyMotion project

### OS X Tutorials

* [Let's Write a RubyMotion App: Part 1](http://code.tutsplus.com/tutorials/lets-write-a-rubymotion-app-part-1--cms-20612) - In this tutorial, you’ll build a painting application from scratch.
* [Custom Table View Cell with IB and RM](http://blog.nuventure.in/2014/12/19/custom-table-view-cell-using-interface-builder-with-rubymotion/) - Custom Table View Cell using Interface Builder with RubyMotion.

Chapters from the book Building Mac OS X apps with RubyMotion

* [Working with NSTableView](http://kickcode.com/blog/2015/08/18/working-with-nstableview.html) - Working with NSTableView
* [Dragging and dropping](http://kickcode.com/blog/2015/05/20/dragging-and-dropping-into-a-rubymotion-mac-os-x-app.html) - Dragging and dropping into your RubyMotion Mac OS X app
* [Capturing video and audio](http://kickcode.com/blog/2015/05/06/capturing-video-and-audio-on-mac-os-x-with-rubymotion.html) - Capturing video and audio on Mac OS X with RubyMotion
* [Previewing video and audio when capturing](http://kickcode.com/blog/2015/05/07/previewing-video-and-audio-when-capturing-on-mac-os-x-with-rubymotion.html) - Previewing video and audio when capturing on Mac OS X with RubyMotion
* [User specified custom key combination for a global hotkey](http://kickcode.com/blog/2015/05/13/custom-user-hotkey-combo.html) - User specified custom key combination for a global hotkey

### Tutorial Screencasts

* [Motion in Motion](https://motioninmotion.tv) - A paid RubyMotion screencast with an occasional free episode for the masses to enjoy.
* [Motion Casts](http://motioncasts.com) - Learn to create native iOS applications using Ruby
* [iOS Development with RubyMotion](https://www.youtube.com/playlist?list=PLid95FTT3ehjnlpwXbM0a_pcPW0eiXtky) - YouTube Channel from Kingsley Ijomah
* [RubyMotion Primer](https://pragmaticstudio.com/screencasts/rubymotion) - Wishing you could create iOS apps using Ruby?

## Resources

Where to learn about RubyMotion and discover new RubyMotion libraries, projects and trends.

* [Motion Toolbox](http://motion-toolbox.com) - A collection of RubyMotion libraries and wrappers
* [RubyMotion Official Website](http://www.rubymotion.com) - RubyMotion Official Website.
* [App catalog](http://www.rubymotion.com/references/app-catalog/) - There are lots of RubyMotion apps in production.

# Other Awesome Lists

Other amazingly awesome lists can be found in the [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) list.
