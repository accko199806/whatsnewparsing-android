# whatsnewparsing-android
![AppScreen](https://github.com/accko199806/whatsnewparsing-android/blob/master/AppScreen.gif)
###### An example of parsing [VR Fantasy](https://play.google.com/store/apps/details?id=com.Chibig.VRFantasy).

After updating your app, you'll need to let users know *what's new*. This app is parsing the what's new of Google Play Store and display it as text.

## Setup
This app uses the [jsoup library](https://jsoup.org) for parsing.
### Gradle
Edit `root/app/build.gradle` like below
```java
// jsoup HTML parser library @ https://jsoup.org/
compile 'org.jsoup:jsoup:1.11.2'
```
### Maven
If you use [Maven](http://maven.apache.org/) to manage the dependencies in your Java project, you do not need to download; just place the following into your POM's <dependencies> section:
```java
<dependency>
  <!-- jsoup HTML parser library @ https://jsoup.org/ -->
  <groupId>org.jsoup</groupId>
  <artifactId>jsoup</artifactId>
  <version>1.11.2</version>
</dependency>
```

## License
```
Copyright 2018 akoiapp

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```