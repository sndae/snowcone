## Introduction ##

ANE been introduced with AIR 2.5 for TV,<br>
and later with AIR 3.0 supports has been added for desktop, iOS and Android.<br>
<br>
from <a href='http://www.adobe.com/devnet/air/articles/extending-air.html'>Extending Adobe AIR</a>
<pre><code>Prior to Adobe AIR 3, only Adobe could add core features to the runtime.<br>
Developers requiring new features could only wait.<br>
Now developers can extend the runtime themselves.<br>
</code></pre>

from <a href='http://help.adobe.com/en_US/air/extensions/WSb464b1207c184b14-70ccb6bd12937b4f2d6-7fff.html'>Introducing native extensions for Adobe AIR</a>
<pre><code>A native extension is a combination of:<br>
<br>
  * ActionScript classes.<br>
<br>
  * Native code. Native code is defined here as code that executes outside the runtime.<br>
    For example, code that you write in C is native code.<br>
    On some platforms, Java code is supported in extensions.<br>
    For the purpose of this documentation, this is also considered “native” code.<br>
<br>
Reasons to write a native extension include the following:<br>
<br>
  * A native code implementation provides access to device-specific features.<br>
    These device-specific features are not available in the built-in ActionScript classes,<br>
    and are not possible to implement in application-specific ActionScript classes.<br>
    The native code implementation can provide such functionality because it has access<br>
    to device-specific hardware and software.<br>
<br>
  * A native code implementation can sometimes be faster<br>
    than an implementation that uses only ActionScript.<br>
<br>
  * A native code implementation allows you to reuse existing code.<br>
</code></pre>

<h2>Features</h2>

<ul><li>Achieve deeper integration with target devices<br>
</li><li>Incorporate legacy native code in their application<br>
</li><li>Achieve maximum performance for critical code<br>
</li><li></li></ul>

<h2>Supported devices</h2>

You can create native extensions for the following devices:<br>
<br>
<ul><li><b>Android</b> devices, starting with AIR 3 and Android 2.2.<br>
</li><li><b>iOS</b> devices, starting with AIR 3 and iOS 4.0<br>
</li><li><b>iOS Simulator</b>, starting with AIR 3.3<br>
</li><li><b>Blackberry PlayBook</b>, starting with AIR 2.7<br>
</li><li><b>Windows desktop</b> devices that support AIR 3.0<br>
</li><li><b>Mac OS X desktop</b> devices that support AIR 3.0<br>
</li><li><b>AIR for TV</b> devices, starting with AIR 2.5 for TV</li></ul>

<h2>Supported device profiles</h2>

The following AIR profiles support native extensions:<br>
<br>
<ul><li><b>extendedTV</b>, starting in AIR 2.5<br>
</li><li><b>extendedDesktop</b>, starting in AIR 3.0<br>
</li><li><b>mobileDevice</b>, starting in AIR 3.0</li></ul>

<h2>Ressources</h2>

<b>links:</b>
<ul><li><a href='http://www.adobe.com/devnet/air/native-extensions-for-air.html'>Native extensions for Adobe AIR</a> (Adobe)<br>
</li><li><a href='http://help.adobe.com/en_US/air/extensions/index.html'>Developing Native Extensions</a> (Adobe Documentation)<br>
</li><li>c</li></ul>

<b>documents:</b>
<ul><li>(PDF) <a href='http://help.adobe.com/en_US/air/extensions/air_extensions.pdf'>Developing Native Extensions for Adobe AIR</a> (Adobe)<br>
</li><li>b<br>
</li><li>c</li></ul>

<b>tutorials:</b>
<ul><li><a href='http://www.adobe.com/devnet/air/articles/extending-air.html'>Extending Adobe AIR</a> by Oliver Goldman (Adobe)<br>
</li><li>Building a native extension for iOS and Android<br>
<ul><li><a href='http://www.adobe.com/devnet/air/articles/building-ane-ios-android-pt1.html'>Part 1: Getting started with volume control</a> by Nathan Weber (DigitalPrimates)<br>
</li><li><a href='http://www.adobe.com/devnet/air/articles/building-ane-ios-android-pt2.html'>Part 2: Developing the ActionScript library</a> by Nathan Weber (DigitalPrimates)<br>
</li><li><a href='http://www.adobe.com/devnet/air/articles/building-ane-ios-android-pt3.html'>Part 3: Building the iOS library</a> by Nathan Weber (DigitalPrimates)<br>
</li><li><a href='http://www.adobe.com/devnet/air/articles/building-ane-ios-android-pt4.html'>Part 4: Building the Android library</a> by Nathan Weber (DigitalPrimates)<br>
</li><li><a href='http://www.adobe.com/devnet/air/articles/building-ane-ios-android-pt5.html'>Part 5: Building the ANE file</a> by Nathan Weber (DigitalPrimates)<br>
</li></ul></li><li><a href='http://www.adobe.com/devnet/air/articles/ane-android-devices.html'>Developing and using Adobe AIR native extensions for Android devices</a> by Mark Hood (Adobe)