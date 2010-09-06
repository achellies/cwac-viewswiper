CWAC ViewSwiper: Let Your Users Flip Off Your Views
===================================================
`ViewFlipper` is a handy container in Android, showing one child
at a time out of an arbitrary number of children. In that sense,
it is a bit like tabs, just without, y'know, the tabs. Instead, it
is up to you to arrange to flip between one child and another.

`ViewSwiper` is a subclass of `ViewFlipper` that uses gestures.
The user can swipe their finger right-to-left to move to the
next child, or from left-to-right to move to the previous child.

This is distributed as an Android library project, following
the conventions of [the Android Parcel Project](http://andparcel.com).
You can download a ZIP file containing just the library project
(sans sample code) from the Downloads section of this GitHub
repository.

Usage
-----
Add the library project to your main project. Then, you can
reference the `com.commonsware.cwac.ViewSwiper` widget in your
layout files, as a drop-in replacement for `ViewFlipper`.

You can elect to add `android:gestureColor` and/or
`android:uncertainGestureColor` attributes, to control
the color that is "drawn" by the user's swipes. By default,
it is yellow. Set both to be transparent (`#00000000`) to
eliminate the effect.

Dependencies
------------
This depends upon the `cwac-parcel` library for accessing
project-level resources.

Version
-------
This is version v0.1.0 of this module, meaning it is brand-spankin'-new.

Demo
----
There is a `demo/` directory containing a demo project. It uses
the library project itself to access the source code and
resources of the `ViewSwiper` library.

License
-------
The code in this project is licensed under the Apache
Software License 2.0, per the terms of the included LICENSE
file.

Questions
---------
If you have questions regarding the use of this code, please
join and ask them on the [cw-android Google Group][gg]. Be sure to
indicate which CWAC module you have questions about.

Release Notes
-------------
v0.1.0: initial release

Who Made This?
--------------
<a href="http://commonsware.com">![CommonsWare](http://commonsware.com/images/logo.png)</a>

[gg]: http://groups.google.com/group/cw-android
