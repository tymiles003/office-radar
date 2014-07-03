
See who's in the office.  

Uses [Couchbase Mobile](http://developer.couchbase.com/mobile/) in conjunction with [Estimote](http://estimote.com/) beacons.

![screenshot](http://tleyden-misc.s3.amazonaws.com/blog_images/office_radar_twoscreens_sm.png)

## Building the project

### Build Couchbase Lite iOS

Download [Couchbase Lite iOS](https://github.com/couchbase/couchbase-lite-ios) and build it.  You should end up with a `CouchbaseLite.framework` bundle.

### Copy framework into OfficeRadar project

Copy `CouchbaseLite.framework` into the OfficeRadar project as a sibling of the `FacebookSDK.framework`

### Build

Build the OfficeRadar XCode project
