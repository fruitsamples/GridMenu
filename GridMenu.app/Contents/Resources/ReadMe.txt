GridMenu


"GridMenu" is a Cocoa sample application that demonstrates how to implement a "grid-like" menu from a NSPopupButton using NSMatrix, NSCollectionView and NSTrackingArea as the contents. This is done by embedding a custom NSView inside a NSMenuItem; the two custom views being NSMatrix and NSCollectionView and the tracking area view which hosts multiple NSTrackingAreas.

In using NSCollectionView it uses the new implementation introduced in 10.6.  Starting with 10.6 NSCollectionViewItem is a subclass of NSViewController.  This sample shows how to use the new implementation at the same time be compatible with 10.5.x.


Sample Requirements
The supplied Xcode project was created using Xcode v3.2 with Mac OS X 10.6, running under Mac OS X 10.5.x or later.


Changes from Previous Versions
n/a


Feedback and Bug Reports
Please send all feedback about this sample by connecting to the Contact ADC page.
Please submit any bug reports about this sample to the Bug Reporting page.


Developer Technical Support
The Apple Developer Connection Developer Technical Support (DTS) team is made up of highly qualified engineers with development expertise in key Apple technologies. Whether you need direct one-on-one support troubleshooting issues, hands-on assistance to accelerate a project, or helpful guidance to the right documentation and sample code, Apple engineers are ready to help you.  Refer to the Apple Developer Technical Support page.

Copyright (C) 2010 Apple Inc. All rights reserved.