[![RaiMan's Stuff](https://raw.github.com/RaiMan/SikuliX-2014-Docs/master/src/main/resources/docs/source/RaiManStuff64.png)](http://sikulix.com) SikuliX
============

**What is SikuliX**<br>SikuliX automates anything you see on the screen of your desktop computer 
running Windows, Mac or some Linux/Unix. It uses image recognition powered by OpenCV to identify 
GUI components and can act on them with mouse and keyboard actions.
This is handy in cases when there is no easy access to a GUI's internals or 
the source code of the application or web page you want to act on. [More details](http://sikulix.com)

<hr>

**Latest stable version is 2.0.0**

[Here you can read about the changes/enhancements](https://sikulix-2014.readthedocs.io/en/latest/news.html)

[**Get SikuliX ready to use**](https://raiman.github.io/SikuliX1) 

For use in Java Maven projects the dependency coordinates are:
```
<dependency>
  <groupId>com.sikulix</groupId>
  <artifactId>sikulixapi</artifactId>
  <version>1.2.0</version>
</dependency>
```
<hr>

**You need at least Java 8, but it works on Java 9 up to latest (currently 12)**

**Windows:** Works out of the box ([for exceptions look here](https://github.com/RaiMan/SikuliX1/wiki/Windows:-Problems-with-libraries-OpenCV-or-Tesseract))

**Mac:** you have to make the prerequisites for Tesseract ready ([for HowTo look here](https://github.com/RaiMan/SikuliX1/wiki/macOS-Linux:-Support-libraries-for-Tess4J-Tesseract-4-OCR)).

**Linux:** you have to make the prerequisites OpenCV and Tesseract ready ([for HowTo look here](https://sikulix-2014.readthedocs.io/en/latest/newslinux.html#version-1-1-4-special-for-linux-people)).

<hr>

**Current developement version is 2.1.0** (nightly builds / sikulixapi snapshots):<br>
[![Build Status](https://travis-ci.org/RaiMan/SikuliX1.svg?branch=master)](https://travis-ci.org/RaiMan/SikuliX1)

[Here you can read more about the changes/enhancements](https://sikulix-2014.readthedocs.io/en/latest/news.html)

[**Get the nightly builds ready to use**](https://raiman.github.io/SikuliX1/downloads.html) 

**Get the sikulixapi SNAPSHOT on OSSRH**<br>
The repository URL:<br>
```
<repositories>
  <repository>
    <id>sonatype-ossrh</id>
    <url>https://oss.sonatype.org/content/repositories/snapshots/</url>
  </repository>
</repositories>
```
The dependency coordinates are:
```
<dependency>
  <groupId>com.sikulix</groupId>
  <artifactId>sikulixapi</artifactId>
  <version>1.3.0-SNAPSHOT</version>
</dependency>
```
<hr>

**Developement environment**

 - Java 12 (OpenJDK release)
 - Windows 10 latest
 - Mac 10.14 latest
 - Ubuntu 18.04 in WSL on Windows 10

<hr>

#### Contributions are welcome and appreciated
 - for `bugreports and requests for features or enhancements` use the issue tracker here
 - for `smaller bugfixes and/or feature enhancements` you should create a pull request against the target branch (master in most cases)
 - for `more complex revisions and/or enhancements` you should ask for a developement branch together with a short description of your ideas
 
 **Please respect the following rules and guidelines when contributing**
  - Start with smaller fixes. E.g. choose an issue from the issue tracker and try to fix it. Or fix issues you encounter while using SikuliX.
  - Only fix cosmetic stuff if it's related to an issue you want to fix.
  - Before you change stuff like dependencies / overall code style and so on, talk with the maintainer beforehand.<br>Sometimes there is a a reason that things are as they are (... and sometimes not :-)).
  - Try to accept the individual coding styles of the acting contributors, even if some of the stuff might be sub-optimal in your eyes.<br>But feel free to talk about your ideas and the reasons behind.

 
