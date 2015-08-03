Description
===========
This app shows content of a word press web site.  For further information, see https://www.youtube.com/watch?v=sCnGSOaaZFo

Installation
============
	* node.js 
	* cordova using npm
	* iOS: XCode
	* Android SDK Manager (Android Studio): 
		* Android SDK Tools (latest)
		* Android SDK Build-tools (latest)
		* Android SDK Platform (latest)
		* ARM EABI v7a System Image (optional, used for emulation)
	* Ionic Plugin

Commands
========

	*  Create project: cordova create . com.myproject MyProject
	* Add Platforms: cordova platform android
	* Set 'minsdk' attribute to required number (here 10) in <project-path>/config.xml
	* Build project: cordova build android
		* copy apk file (/<project-path>/platforms/android/build/outputs/apk) to device using file transfer android app
	* alternatively Run project on emulator with command: cordova run android or using eclipse

