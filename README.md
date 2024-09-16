通用 Android 音乐播放器示例（Universal Android Music Player Sample
=====================================
此示例的目标是展示如何实现一个可跨多种外形尺寸运行的音频媒体应用，

并在 Android 手机、平板电脑、Android Auto、Android Wear、Android TV、Google Cast 设备和 Google Assistant 上提供一致的用户体验。

要开始使用 UAMP，请阅读完整指南。

The goal of this sample is to show how to implement an audio media app that works
across multiple form factors and provides a consistent user experience
on Android phones, tablets, Android Auto, Android Wear, Android TV, Google Cast devices,
and with the Google Assistant. 

To get started with UAMP please read the [full guide](docs/FullGuide.md).

![Screenshot showing UAMP's UI for browsing albums and songs](docs/images/1-browse-albums-screenshot.png "Browse albums screenshot")
![Screenshot showing UAMP's UI for playing a song](docs/images/2-play-song-screenshot.png "Play song screenshot")

先决条件（Pre-requisites
--------------

- Android Studio 3.x

入门（Getting Started
---------------

此示例使用 Gradle 构建系统。要构建此项目，请使用“gradlew build”命令或使用 Android Studio 中的“导入项目”。

This sample uses the Gradle build system. 

To build this project, use the "gradlew build" command or use "Import Project" in Android Studio.

支持（Support
-------

- 查看常见问题解答页面（Check out the [FAQs page](docs/FAQs.md)
- 堆栈溢出：（Stack Overflow: http://stackoverflow.com/questions/tagged/android

如果您发现此示例中有错误，请 提交问题（If you've found an error in this sample, please
[file an issue](https://github.com/android/UAMP/issues)

鼓励提供补丁，您可以通过分叉此项目并通过 GitHub 提交拉取请求来提交补丁。请参阅CONTRIBUTING.md了解更多详细信息。

（Patches are encouraged and may be submitted by forking this project and
submitting a pull request through GitHub. Please see [CONTRIBUTING.md](CONTRIBUTING.md) for more
details.

音频（Audio
-----

音乐由自由音乐档案馆提供。（Music provided by the [Free Music Archive](http://freemusicarchive.org/).

- 由 《京都连线》唤醒。（ [Wake Up](http://freemusicarchive.org/music/The_Kyoto_Connection/Wake_Up_1957/) by
[The Kyoto Connection](http://freemusicarchive.org/music/The_Kyoto_Connection/).

录音由Ambisonic Sound Library提供。（Recordings provided by the [Ambisonic Sound Library](https://library.soundfield.com/).

- [Pre Game Marching Band](https://library.soundfield.com/track/163) by Watson Wu
- [Chickens on a Farm](https://library.soundfield.com/track/129) by Watson Wu
- [Rural Market Busker](https://library.soundfield.com/track/55) by Stephan Schutze
- [Steamtrain Interior](https://library.soundfield.com/track/65) by Stephan Schutze
- [Rural Road Car Pass](https://library.soundfield.com/track/57) by Stephan Schutze
- [10 Feet from Shore](https://library.soundfield.com/track/114) by Watson Wu

License
-------
版权所有 2017 Google Inc.

根据一份或多份贡献者许可协议授权给 Apache 软件基金会 (ASF)。有关版权所有权的更多信息，

请参阅随本作品分发的 NOTICE 文件。ASF 根据 Apache 许可证 2.0 版（“许可证”）向您授权此文件；您不得使用此文件，除非遵守许可证。您可以在以下位置获取许可证的副本

http://www.apache.org/licenses/LICENSE-2.0

除非适用法律要求或书面同意，否则根据许可证分发的软件将按“原样”分发，不附带任何明示或暗示的保证或条件。请参阅许可证，了解许可证下特定语言的权限和限制。

Copyright 2017 Google Inc.

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
