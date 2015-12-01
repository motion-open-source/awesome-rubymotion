
# Awesome RubyMotion

A categorized community-driven collection of awesome RubyMotion example apps, libraries, tools, frameworks, software and resources.

Sharing, suggestions and contributions are always welcome! Please take a look at the [contribution guidelines and quality standard](https://github.com/motion-open-source/awesome-rubymotion/blob/master/CONTRIBUTING.md) first.

[RubyMotion](http://www.rubymotion.com) is a Commercial product created by [HipByte](http://www.hipbyte.com).

Thanks to Clay Allsopp who created the Motion Toolbox list.
Thanks to all [contributors](https://github.com/motion-open-source/awesome-rubymotion/graphs/contributors), you're awesome and wouldn't be possible without you!

  - [Templates](#templates)
  - [Libraries and Wrappers](#libraries-and-wrappers)
    - [General](#general)
    - [Models](#models)
    - [Views](#views)
    - [Testing](#testing)
    - [Project Management](#project-management)
    - [Specific](#specific)
    - [Service API Wrappers](#service-api-wrappers)
    - [Software API Wrappers](#software-api-wrappers)
    - [Encryption](#encryption)
  - [Apps](#apps)
    - [Example Android Apps](#example-android-apps)
    - [Example iOS Apps](#example-ios-apps)
    - [Example OSX Apps](#example-osx-apps)
    - [Example tvOS Apps](#example-tvos-apps)
  - [Tutorials](#tutorials)
  - [Resources](#resources)
- [Other Awesome Lists](#other-awesome-lists)

## Templates

* [MotionTemplate](https://github.com/IconoclastLabs/MotionTemplate) - A clean RubyMotion project for quickly templating a styled application.
* [promotion-template](https://github.com/jamonholmgren/promotion-template) - Utlize the bells and whistles of ProMotion to hit the ground running.
* [rubymotion_generators](https://github.com/andyw8/rubymotion_generators) - Provides boilerplate code templates for RubyMotion

## Libraries and Wrappers

### Frameworks and Utility Bundles
* [BubbleWrap](http://rubymotion.github.io/BubbleWrap) - A collection of (tested) helpers and wrappers used to wrap CocoaTouch code and provide more Ruby like APIs.
* [Sugarcube](https://github.com/rubymotion/sugarcube) - These extensions hope to make development in RubyMotion more enjoyable by tacking 'UI' methods onto the base classes (String, Fixnum, Numeric). With sugarcube, you can create a color from an integer or symbol, or create a UIFont or UIImage from a string.
* [MotionPrime](http://prime.droidlabs.pro) - MotionPrime is yet another framework written on RubyMotion for creating really fast iOS applications.
* [RubyMotionQuery - RMQ](http://infinitered.com/rmq) - UI Library for RubyMotion. Fast, non-polluting, & chaining; it’s like jQuery for RubyMotion + stylesheets, animations, events, and more.
* [Elevate](https://github.com/mattgreen/elevate) - Stop scattering your domain logic across your view controller. Consolidate it to a single conceptual unit with Elevate.
* [ProMotion](https://github.com/infinitered/ProMotion) - A full featured RubyMotion framework that makes iPhone development less like Objective-C and more like Ruby, designed to get up and running fast.
* [RedPotion](https://github.com/infinitered/redpotion) - RedPotion combines RMQ, ProMotion, CDQ, AFMotion, and more for the perfect mix to develop in RubyMotion fast.
* [BluePotion](https://github.com/infinitered/bluepotion) - BluePotion is the Android version of RedPotion. (ALPHA)
* [motion-support](https://github.com/rubymotion/motion-support) - A port of ActiveSupport to RubyMotion
* [motion-speech](https://github.com/macfanatic/motion-speech) - Easy text-to-speech wrapper for AVSpeechSynthesizer in iOS 7.
* [motion-hybrid](https://github.com/balvig/motion-hybrid) - RubyMotion framework for easily making hybrid webview-centric iOS apps
* [motion-pool](https://github.com/wooandoo/motion-pool) - A pool for RubyMotion.
* [weak_attr_accessor](https://github.com/hboon/weak_attr_accessor) - Adds weak_attr_accessor that wraps objects with WeakRef, for RubyMotion
* [motion-bitmask](https://github.com/buffpojken/motion-bitmask) - A simple implementation of generic bitmasks for RubyMotion.

### Models
* [MotionModel](https://github.com/sxross/MotionModel) - Simple Model, Validation, and Input Mixins for RubyMotion.
* [NanoStoreInMotion](https://github.com/siuying/NanoStoreInMotion) - Wrapper for NanoStore, a lightweight schema-less key-value document database based on sqlite.
* [MotionDataWrapper](https://github.com/macfanatic/motion_data_wrapper) - Intuitive querying and persistence of CoreData models, using Xcode to define entities, validations, relationships and migrations.
* [Core Data Query - CDQ](https://github.com/infinitered/cdq) - Easy-to-set-up library for using Core Data without Xcode
* [motion-bindable](https://github.com/nathankot/motion-bindable) - Create two-way bindings between your models and view objects (or any other object.)
* [Turnkey](https://github.com/seldomatt/TurnKey) - Utility for saving custom objects to NSUserDefaults using NSKeyedArchiver and NSKeyedUnarchiver
* [yapper](https://github.com/kareemk/yapper) - ORM for YapDatabase which is schemaless, very fast (thanks to YapDatabase's architecture), has chainable criteria, one-many relationships, on-the-fly reindexing and is thread-safe.
* [couchmotion](https://github.com/jannishuebl/couchmotion) - API for using Couchbase(CouchDB) a schemaless database with Rubymotion for Android and iOS

### Views
* [IB](https://github.com/rubymotion/ib) - RubyMotion Interface Builder support, including outlets and actions.
* [Formotion](https://github.com/clayallsopp/formotion) - Painless, productive views on iOS.
* [Teacup](https://github.com/colinta/teacup) - A community-driven DSL for creating user interfaces on the iPhone.
* [Geomotion](https://github.com/clayallsopp/geomotion) - Better iOS Geometry with RubyMotion.
* [Walt](https://github.com/clayallsopp/Walt) - Frictionless, hash-based iOS animations.
* [AccordionView](https://github.com/toamitkumar/AccordionView) - Create and add Accordions to your UIViews.
* [motion-layout](https://github.com/qrush/motion-layout) - A nice way to use Auto Layout in your RubyMotion app.
* [motion-stylez](https://github.com/FluffyJack/motion-stylez) - RubyMotion stylesheet library based off RMQ
* [better_toolbar](https://github.com/FluffyJack/better_toolbars) - A better way to work with toolbars
* [motion-form](https://github.com/dblandin/motion-form) - RubyMotion forms made easy
* [MIMInputToolbar](https://github.com/FluffyJack/MIMInputToolbar) - Input accessory view for your UITextFields and UITextViews.
* [motion-wizard](https://github.com/ijpiantanida/motion-wizard) - A gem to create wizard like view controllers in iOS
* [MotionKit](https://github.com/motion-kit/motion-kit) - The RubyMotion layout and styling gem.
* [MenuMotion](https://github.com/codelation/menu-motion) - A RubyMotion wrapper for creating OS X menus
* [EverydayMenu](https://github.com/henderea/everyday-menu) - An easy way to define menu items and visually lay out menus for your OSX apps.
* [motion-imager](https://github.com/OTGApps/motion-imager) - An interactive iOS image viewer that does it all: double tap to zoom, flick to dismiss, et cetera.
* [purplish-layout](http://hboon.com/purplish-layout/) - A RubyMotion wrapper for Auto Layout on iOS and OS X
* [ProMotion-form](https://github.com/infinitered/ProMotion-form) - ProMotion::FormScreen - forms the ProMotion way!
* [Ion_in_Motion](https://github.com/Brian-Egan/ion_in_motion) - Ridiculously easy use of IonIcons in UILabels, UIButtons, UIImages and more. IonIcons: http://ionicons.com/
* [Moticons](https://github.com/andrewhavens/moticons) - The easiest way to add icons to your RubyMotion app.
* [Motion Swipe](https://github.com/dam13n/motion-swipe) - Tinder-like swipe gem.
* [Motion Floating Action Button](https://github.com/dam13n/motion-floating-action-button) - Material design floating action button.

### Testing
* [MotionFixtures](https://github.com/farcaller/motion-fixtures) - Simple support for test fixtures.
* [WebStub](https://github.com/nathankot/webstub) - Easily stub out HTTP responses in RubyMotion specs.
* [motion-stump](https://github.com/siuying/motion-stump) - Stubbing and mocking for RubyMotion.
* [motion-frank](https://github.com/cyrusinnovation/motion-frank) - A gem to use integrate frank-cucumber into RubyMotion projects.
* [motion-crescentia](https://github.com/Shirk/motion-crescentia) - RubyMotion wrapper for the Calabash BDD framework.
* [motion_print](https://github.com/OTGApps/motion_print) - A RubyMotion friendly console logger and debugging tool. Use it to output pretty formatted objects to the REPL.
* [awesome_print_motion](https://github.com/michaeldv/awesome_print_motion) - A port of the awesome_print gem to RubyMotion.
* [motion-colorize](https://github.com/clayallsopp/motion-colorize) - Add some color to your RubyMotion output.
* [motion-facon](https://github.com/chuyeow/facon) - A port of Facon mocking library to RubyMotion.
* [guard-motion](https://github.com/mordaroso/guard-motion) - Guard::Motion automatically run your RubyMotion specs (much like autotest)
* [motion-instabug](https://github.com/bmichotte/motion-instabug) - motion-instabug allows RubyMotion projects to easily embed the Instabug SDK and be submitted to the Instabug platform.

### Project Management
* [motion-schemes](https://github.com/siuying/motion-schemes) - Expand RubyMotion build system to support building multiple apps from one project.
* [motion-config-vars](https://github.com/jamescallmebrent/motion-config-vars) - Heroku-style environment configuration for RubyMotion.
* [MotionBundler](https://github.com/archan937/motion-bundler) - Require and mock Ruby gems (including their dependencies) within RubyMotion applications.
* [motion-xray](https://github.com/colinta/motion-xray) - An iOS Inspector that runs inside your app, so you can debug and analyze from your device in real-world situations.
* [motion-sparkle](https://github.com/webcracy/motion-sparkle) - motion-sparkle makes it easy to use Sparkle with your RubyMotion projects
* [motion-env](https://github.comclayallsopp/motion-env) - Sync ENV variables between Rakefile and RubyMotion
* [motion-screenshots](https://github.com/clayallsopp/motion-screenshots) - Automatic screenshots for your RubyMotion apps
* [motion-launchimages](https://github.com/brendanjcaffrey/motion-launchimages) - Automate taking your RubyMotion launch images
* [motion-my_env](https://github.com/ainame/motion-my_env) - Simple environment variable solution for RubyMotion
* [motion-reveal](https://github.com/diogoandre/motion-reveal) - Easy way to add the Reveal framework to your Rubymotion project
* [motion-maven](https://github.com/HipByte/motion-maven) - motion-maven lets you automatically manage 3rd-party Java dependencies in RubyMotion for Android projects using Maven

### Specific
* [AFMotion](https://github.com/clayallsopp/afmotion) - A RubyMotion wrapper for AFNetworking.
* [Motion-Plot](https://github.com/toamitkumar/motion-plot) - A RubyMotion wrapper for CorePlot.
* [ParseModel](https://github.com/adelevie/ParseModel) - An Active Record pattern for your Parse models.
* [motion-awesome](https://github.com/derailed/motion-awesome) - DSL to easily create buttons and labels using the wonderful font-awesome library.
* [Motion Parse](https://github.com/tkadauke/motion-parse) - Thin wrapper around the Parse SDK for RubyMotion.
* [Parsistence](https://github.com/infinitered/Parsistence) - A Parse.com wrapper similar to persistence.js.
* [Twittermotion](https://github.com/clayallsopp/twittermotion) - RubyMotion wrapper for the iOS Twitter API.
* [motion-state-machine](https://github.com/opyh/motion-state-machine) - A Grand Central-aware, simple syntax for state machines.
* [motion-ocr](https://github.com/ferdev/motion-ocr) - A RubyMotion wrapper for the OCR engine Tesseract.
* [motion-addressbook](https://github.com/alexrothenberg/motion-addressbook) - A RubyMotion wrapper around the iOS & OSX Address Book frameworks.
* [motionscan](https://github.com/jjaffeux/Motionscan) - A RubyMotion wrapper around the image recognition SDK of Moodstocks.com.
* [MapKitWrapper](https://github.com/weibel/MapKitWrapper) - Make dealing with MapKit less painful for RubyMotion.
* [can_i](https://github.com/macfanatic/can_i) - A RubyMotion wrapper providing a simple DSL for role authorization, similar to the CanCan gem.
* [motion-inappmail](https://github.com/Swatto/motion-inappmail) - A RubyMotion wrapper to use the email composer in your app.
* [MotionPanel](https://github.com/tombroomfield/motion_panel) - A native RubyMotion wrapper around the Mixpanel API.
* [Joybox](https://github.com/rubymotion/Joybox) - Cocos2D & Box2D Wrapper for RubyMotion.
* [Helu](https://github.com/ivanacostarubio/helu) - A RubyMotion wrapper for the Store Kit Framework
* [motion-acknowledgements](https://github.com/OTGApps/motion-acknowledgements) - This gem makes it easy to include the CocoaPods acknowledgements file in your application.
* [motion-settings-bundle](https://github.com/qrush/motion-settings-bundle) - Create a Settings.bundle for your RubyMotion app
* [Motion-Social](https://github.com/ivanacostarubio/motion-social) - Wrapper around the Social Framework
* [motion-net-service](https://github.com/fearoffish/motion-net-service) - A RubyMotion wrapper providing a simple DSL for the Bonjour (NSNetService) zero configuration network protocol.
* [motion-firebase](https://github.com/colinta/motion-firebase) - A RubyMotion wrapper for the Firebase SDK.
* [simple_si](https://github.com/forrestgrant/simple_si) - A RubyMotion wrapper for SIAlertView
* [motion-accessibility](https://github.com/austinseraphin/motion-accessibility) - Making accessibility accessible. RubyMotion Wrappers around the UIAccessibility protocols. Easily interact with Apple's impressive array of assistive technologies, including VoiceOver.
* [motion-blitz](https://github.com/dblandin/motion-blitz) - RubyMotion wrapper for SVProgressHUD
* [motion-objection](https://github.com/atomicobject/motion-objection) - RubyMotion wrapper for Objection
* [RackMotion](https://github.com/drewbug/RackMotion) - Intercept and alter HTTP requests and responses in RubyMotion
* [StatusBar](https://github.com/holgersindbaek/status_bar) - Notifications for the statusbar.
* [motion-csv](https://github.com/OTGApps/motion-csv) - A RubyMotion friendly CSV parser gem.
* [motion-takeoff](https://github.com/OTGApps/motion-takeoff) - A gem for scheduling stuff. You can use motion-takeoff to display messages at certain launch counts and schedule local notifications.
* [motion-launchpad](https://github.com/macfanatic/motion-launchpad) - A gem providing a DSL allowing you to schedule events on specific launches of your application.  'motion-takeoff' only supplies displaying an alert, this gem executes any code block.
* [Vendor](https://github.com/holgersindbaek/Vendor) - A RubyMotion StoreKit Wrapper that allows you to buy, restore and get product info on your in app purchases and subscriptions.
* [Motion-Wiretap](https://github.com/colinta/motion-wiretap) - A wrapper for KVO, gestures, UIControl events, and procs. Okay okay it's pretty much ReactiveCocoa in RubyMotion.
* [motion-dynamic-type](https://github.com/FluffyJack/motion-dynamic-type) - Simplifying even further iOS 7's Dynamic Type
* [meteor-motion](https://github.com/whitesmith/meteor-motion) - A wrapper for Meteor DDP with support for Motion Model
* [motion.h](https://github.com/kastiglione/motion.h) - Expose iOS and OS X system libraries in RubyMotion.
* [motion-sqlite3](https://github.com/mattgreen/motion-sqlite3) - A minimal wrapper over the SQLite 3 C API for RubyMotion
* [motion-egg](https://github.com/GantMan/motion-egg) - Add an Easter egg to your app
* [motion-distance](https://github.com/willrax/motion-distance) - Easy distance tracking for RubyMotion projects.
* [motion-giphy](https://github.com/willrax/motion-giphy) - A nice wrapper around the http://giphy.com API.
* [motion-capture](https://github.com/dblandin/motion-capture) - An AVFoundation wrapper to support custom camera controllers.
* [MotionPaddle](https://github.com/henderea/motion-paddle) - A RubyMotion gem for the Paddle framework
* [ProMotion-iap](https://github.com/infinitered/ProMotion-iap) - ProMotion-iap is in-app purchase notification support for the popular RubyMotion gem ProMotion.
* [ProMotion-menu](https://github.com/infinitered/ProMotion-menu) - RubyMotion gem allowing you to easily setup a facebook or Path style hidden slide menu easily with the ProMotion gem.
* [ProMotion-push](https://github.com/infinitered/ProMotion-push) - Push notification support for ProMotion.
* [ProMotion-map](https://github.com/infinitered/ProMotion-map) - ProMotion::MapScreen gem. Extracted from ProMotion core.
* [apex](https://github.com/infinitered/apex) - Apex is a RubyMotion web framework for OS X. It uses GCDWebServer under the hood and provides a Sinatra-like router and DSL.
* [Toaster](https://github.com/jamonholmgren/toaster) - RubyMotion-android 'Toast' gem. Makes working with Android toasts really easy!
* [Indoctrinator](https://github.com/ryanlntn/indoctrinator) - Indoctrinator is a RubyMotion gem that provides a Path style tutorial view for iOS applications.
* [Crittercism](https://github.com/andrewhavens/crittercism) - Easily add crash reporting to your RubyMotion app with Crittercism.

### Service API Wrappers
* [motion-phrase](https://github.com/phrase/motion-phrase) - Connect your RubyMotion project with <a href="https://phraseapp.com" target="_blank">PhraseApp</a> for easy app internationalization. Translatable strings are exported while browsing the app and then managable through the PhraseApp translation editor.
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

### Software API Wrappers
* [motion-keychain](https://github.com/IconoclastLabs/motion-keychain) - The motion-keychain gem is a simple wrapper for Keychain on iOS and OS X. Makes using Keychain APIs as easy as NSUserDefaults.
* [Medic](https://github.com/ryanlntn/medic) - Is HealthKit's verbose and convoluted API driving you mad? Quick! You need a medic!
* [MotionPanel](https://github.com/tombroomfield/motion_panel) - A native RubyMotion wrapper around the Mixpanel API.
* [motion-firebase](https://github.com/colinta/motion-firebase) - A RubyMotion wrapper for the Firebase SDK.
* [motion-sqlite3](https://github.com/mattgreen/motion-sqlite3) - A minimal wrapper over the SQLite 3 C API for RubyMotion

### Encryption
* [rm-digest](https://github.com/tmeinlschmidt/rm-digest) - MD5 and SHA1 digest for RubyMotion (gem)

## Apps

### Example Android Apps
* [Android RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/android) - A collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.
* [rubymotion-android-cookbook](https://github.com/IconoclastLabs/rubymotion-android-cookbook) - Awesome rm cookbook examples for android

### Example iOS Apps
* [IOS RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/ios) - A collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.

### Example OSX Apps

* [OSX RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/osx) - A collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.
* [mctv-mac-osx](https://github.com/Motioncasts/mctv-mac-osx) - Demo Pomodoro Technique Timer App
* [motion-osx-ib](https://github.com/MarkVillacampa/motion-osx-ib) - This is an example on how to use the ib gem in a OSX RubyMotion 2.0 application.
* [motion-treeview-coredata](https://github.com/mipmip/motion-treeview-coredata) - A port of the example from Connecting NSOutlineView to Core Data in 10.6 Part 1: Ordered Trees to RubyMotion.
* [rm-osx-kartta](https://github.com/masal/rm-osx-kartta) - RubyMotion / OSX map viewer for Finnish topographical maps.

### Example tvOS Apps

* [tvOS RubyMotionSamples](https://github.com/HipByte/RubyMotionSamples/tree/master/tvos) - A collection of RubyMotion applications for code samples by HipByte the creators of RubyMotion.

## Tutorials
* [Let's Write a RubyMotion App: Part 1](http://code.tutsplus.com/tutorials/lets-write-a-rubymotion-app-part-1--cms-20612) - In this tutorial, you’ll build a painting application from scratch.

## Resources

Where to learn about RubyMotion and discover new RubyMotion libraries, projects and trends.

* [RubyMotion Official Website](http://www.rubymotion.com) - RubyMotion Official Website.
* [Motion in Motion](https://motioninmotion.tv) - A paid RubyMotion screencast with an occasional free episode for the masses to enjoy.
* [Motion Casts](http://motioncasts.com) - Learn to create native iOS applications using Ruby
* [Motion Toolbox](http://motion-toolbox.com) - A collection of RubyMotion libraries and wrappers
* [App catalog](http://www.rubymotion.com/references/app-catalog/) - There are lots of RubyMotion apps in production.

# Other Awesome Lists

Other amazingly awesome lists can be found in the [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) list.
