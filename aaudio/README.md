AAudio Samples
==============
These samples demonstrate how to use AAudio API:
1. hello-aaudio sample: creates an output stream
1. echo sample: creates output and input streams, then play via loopback

[AAudio](https://android-dot-devsite.googleplex.com/ndk/guides/audio/aaudio/aaudio.html) is still in its early stage of development, this [android-ndk thread](https://groups.google.com/forum/#!topic/android-ndk/Ox7L8V5ZF5s) addresses some of the possible questions surrounding the new API.

Pre-requisites
-------------
* Android Device with recording capability
* Android O DP2 or above (Developer's Preivew) API
* An external headphone (with a microphone) plugged into Android Device
* NDK-r15 [Beta2](https://developer.android.com/ndk/downloads/index.html) and above
* [Android Studio 2.3.0+](https://developer.android.com/studio/index.html)
* [AAudio Guide](https://developer.android.com/ndk/guides/audio/aaudio/aaudio.html)

Getting Started
---------------
1. [Download Android Studio](https://developer.android.com/studio/index.html)
1. Launch Android Studio
1. Import project: File --> New --> Import Project; browse to aaudio/build.gradle; and "OK"
1. Open *File/Project Structure...*
  - Click *Download* or *Select NDK location*: make sure to use ndk-r15-beta1+
1. Click *Tools/Android/Sync Project with Gradle Files*.
1. Click *Run/Run 'app'*.

Screenshots
-----------
![screenshot](screenshot.png)

Support
-------
If you've found an error in these samples, please [file an issue](https://github.com/googlesamples/android-audio-high-performance/issues/new).

Patches are encouraged, and may be submitted by [forking this project](https://github.com/googlesamples/android-audio-high-performance/fork) and
submitting a pull request through GitHub. Please see [CONTRIBUTING.md](../CONTRIBUTING.md) for more details.

- [Stack Overflow](http://stackoverflow.com/questions/tagged/android-ndk)
- [Google+ Community](https://plus.google.com/communities/105153134372062985968)
- [Android Tools Feedback](http://tools.android.com/feedback)


License
-------
Copyright 2017 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.

Version History
---------------
1) 03/22/2017:  initial release for Android - O DP1. Directly reading & writing to audio streams
2) 05/17/2017:  updated for Android-O-DP2 release, using AAudio callback interface
