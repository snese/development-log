# 目前正在使用的 Xcode Plugins 

## Plugins Overview
 - [Alcatraz](#alcatraz)
 - [Backlight](#backlight)
 - [BBUDebuggerTuckAway](#bbudebuggertuckaway)
 - [BBUUtilitiesTuckAway](#bbuutilitiestuckaway)
 - [CocoaPods](#cocoapods)
 - [FuzzyAutocompletePlugin](#fuzzyautocompleteplugin)
 - [GitDiff](#gitdiff)
 - [OMColorSense](#omcolorsense)
 - [SCXcodeSwitchExpander](#scxcodeswitchexpander)
 - [VVDocumenter-Xcode](#vvdocumenter-xcode)
 - [KSImageNamed](#ksimagenamed)
 - [Lin](#lin)
 - [XToDo](#xtodo)

### [Alcatraz](http://alcatraz.io/)
Xcode Package Manager.
#### Install
Paste this into your terminal:
```bash
curl -fsSL https://raw.githubusercontent.com/supermarin/Alcatraz/deploy/Scripts/install.sh | sh
```
Alcatraz is available for OSX 10.9+ and Xcode 5+ only.
#### Uninstall
Delete the plugin:
```
rm -rf ~/Library/Application\ Support/Developer/Shared/Xcode/Plug-ins/Alcatraz.xcplugin
```
Remove all cached data:
```
rm -rf ~/Library/Application\ Support/Alcatraz
```
### [Backlight](https://github.com/limejelly/Backlight-for-XCode)
Highlights the current editing line in Xcode
![image](https://raw.githubusercontent.com/limejelly/Backlight-for-XCode/master/screenshot.png)

### [BBUDebuggerTuckAway](https://github.com/neonichu/BBUDebuggerTuckAway)
Xcode plugin for auto-hiding the debugger once you start typing in the source code editor.
![](https://github.com/neonichu/BBUDebuggerTuckAway/blob/master/plugin.gif)

### [BBUUtilitiesTuckAway](https://github.com/neonichu/BBUUtilitiesTuckAway)
Xcode plugin for auto-hiding the utilities area once you start typing in the source code editor.

### [CocoaPods](https://github.com/kattrali/cocoapods-xcode-plugin)
Manage your dependencies, with minimal command line hack-fu
![image](https://github.com/kattrali/cocoadocs-xcode-plugin/raw/master/menu.png)

### [FuzzyAutocompletePlugin](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin)
This is a Xcode 5+ plugin that patches the autocomplete filter to work the same way the **Open Quickly** works. It performs very well, and the fuzzy matching actually uses Xcode's own `IDEOpenQuicklyPattern`.
![image](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin/blob/master/demo.gif)

### [GitDiff](https://github.com/johnno1962/GitDiff)
With thanks to the genius who suggested this plugin, GitDiff displays deltas against a git repo in the Xcode
source editor once you've saved the file. To use, copy this repo to your machine, build it and restart Xcode.
Differences should then be highlighted in orange for lines that have been modified and blue for new code.
A red line indicates code has been removed. Hover over deleted/modified line number to see original source.
![image](http://injectionforxcode.johnholdsworth.com/gitdiff2.png)

### [OMColorSense](https://github.com/omz/ColorSense-for-Xcode)
ColorSense is an Xcode plugin that makes working with `UIColor` (and `NSColor`) more visual.

### [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander)
SCXcodeSwitchExpander is a small Xcode plugin that expands switch statements by inserting missing cases.
![image](https://dl.dropboxusercontent.com/u/12748201/SCXcodeSwitchExpander/SCXcodeSwitchExpander1.gif)

### [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode)
Writing document is so important for developing, but it is really painful with Xcode. Think about how much time you are wasting in pressing '*' or '/', and typing the parameters again and again. Now, you can find the method (or any code) you want to document to, and type in `///`, the document will be generated for you and all params and return will be extracted into a Javadoc style, which is compatible with [appledoc](https://github.com/tomaz/appledoc), [Doxygen](http://www.stack.nl/~dimitri/doxygen/) and [HeaderDoc](https://developer.apple.com/library/mac/documentation/DeveloperTools/Conceptual/HeaderDoc/intro/intro.html). You can just fill the inline placeholder tokens to finish your document.
![image](https://raw.github.com/onevcat/VVDocumenter-Xcode/master/ScreenShot.gif)

### [KSImageNamed](https://github.com/ksuther/KSImageNamed-Xcode)
See the actual image while typing [UIImage imageNamed:].
![image](https://raw.github.com/ksuther/KSImageNamed-Xcode/master/screenshot.gif)

### [Lin](https://github.com/questbeat/Lin-Xcode5)
Lin is a open source plug-in for **Xcode 5**.  
It lets you search/manage localizations without opening the .strings files.
![image](https://raw.github.com/questbeat/Lin-Xcode5/master/screenshots/01.png)

### [XToDo](https://github.com/trawor/XToDo)
to collect and list the `TODO`,`FIXME`,`???`,`!!!`
![image](https://github.com/trawor/XToDo/blob/master/screenshots/1.png)
![image](https://github.com/trawor/XToDo/blob/master/screenshots/2.png)

## Reference
 - [The best Xcode plugins](http://iosdevtips.co/post/82232620790/best-xcode-plugins), 4/10/2014
 - [10 Xcode Plugins for iOS Development](http://code.tutsplus.com/tutorials/10-xcode-plugins-for-ios-development--cms-21899), 8/11/2014
 - [Xcode Plugin Listing – Quality Xcode Plugins](https://maniacdev.com/xcode-plugins), 1/14/2015
