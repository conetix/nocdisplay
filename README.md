NOC Display
==========

A simple Android application which displays a full-screen browser based on a JSON call. This is for use within a Network Operations Centre, which is documented [here](http://www.conetix.com.au/blog/conetix-network-operations-centre-build-part-1) and [here](http://www.conetix.com.au/blog/conetix-network-operations-centre-build-part-2).


** Note: ** This shouldn't be considered a complete project which is ready to compile. Please feel free to fork and modify to suit your own needs.

## Incomplete Parts

* URL call to the remote server is hardcoded in NOCDisplay.java (search for ELASTICSEARCHSERVER)
* No time based rotation. This relies on the webpage itself to refresh the screen.
* Although it hasn't been a problem, the error and exception handling probably aren't perfect.

This code is released under the MIT license.

## Build Environment

This has been written using Android Studio 2.2 under a Linux environment with the Android SDK version 24 and targeted against version 13 and higher.
