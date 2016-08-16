Tutorial Samples
================
A set of samples to illustrate Vulkan API on Android with Android Studio		
To build on windows for tutorial02/03, copy/install ndk-r12 ( or better ) to a directory close to root dir ( c: ) to workaround command path 260 character limit issue;see totorial02/03's build.gradle for details

Other Resources:	
Additional Android Studio/NDK samples:    
- [Android Vulkan API Basic Samples](https://github.com/googlesamples/vulkan-basic-samples)
- [Google Play Game Samples](https://github.com/playgameservices/cpp-android-basic-samples)
- [Google Android NDK Samples](https://github.com/googlesamples/android-ndk)


Pre-requisites
--------------
- Android N device, API >= 24
- Android Studio 2.2 beta1 or better
- Android NDK
    * [NDK-r12](https://github.com/android-ndk/ndk/wiki), compile as is
    * SDK with the latest cmake package

Known Issues
------------
 - cmake package version taged 3.6 inside sdk does NOT work well with ndk-r13-beta1, so skip that ndk version
 
Getting Started
---------------
1. [Download Android Studio](http://tools.android.com/download/studio/canary)
1. [Download Android NDK-R12+](https://github.com/android-ndk/ndk/wiki)
1. [Download source code](http://www.github.com/googlesamples/android-vulkan-tutorials)
1. Launch Android Studio.
1. "Import Project" of the interested tutorial project to Android Studio
1. Expand "Gradle" panel inside Android Studio, right hand edge of IDE,
then "mathfu" --> "Tasks" --> "other" --> "get_mathfu".
1. Select *"app"* inside Android Studio *"Project"* pane.
1. Click *Tools/Android/Sync Project with Gradle Files*.
1. Click *Run/Run 'app'*.


Tutorial List
-------------
1. tutorial01_load_vulkan
    - create a vulkan device
1. tutorial02_prebuilt_layers
    - create a vulkan device with vulkan validation layers
1. tutorial03_traceable_layers
    - create a vulkan device with validation layers that could debug into
1. tutorial04_first_window
    - create a vulkan window with WSI 
1. tutorial05_triangle
    - draw a simple triangle with android shaderc feature


License
-------
Copyright 2016 Google, Inc.

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





