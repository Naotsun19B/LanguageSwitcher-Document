# LanguageSwitcher

![Plugin](https://github.com/Naotsun19B/LanguageSwitcher-Document/assets/51815450/3f38268d-30ed-4f2f-a2f4-e269f056a2b8)

<!--ts-->
* [Description](#Description)
* [Requirement](#Requirement)
* [Installation](#Installation)
* [Features And Usages](#features-and-usages)
* [Settings](#Settings)
* [Author](#Author)
* [History](#History)
<!--te-->

## Description

This plugin adds a function that allows you to quickly change language and region settings such as editor language, locale, and preview game language from the status bar and shortcut keys.  

## Requirement

Target version : UE5.0 ～ 5.4    
Target platform : Windows, Mac, Linux  

## Installation

Install from the [marketplace](https://www.unrealengine.com/marketplace/en-US/product/5e10055a95f34b609c7afe072a5379ab).  
If the feature is not available after installing the plugin, it is possible that the plugin has not been enabled, so please check if the plugin is enabled from Edit > Plugins.

## Features And Usages

![Usage](https://github.com/Naotsun19B/LanguageSwitcher-Document/assets/51815450/580528b1-5762-412b-bcd0-a7015cfaf9ad)

A button (default shortcut key is `Ctrl + L`) that calls the function set in the editor environment setting and a combo button that can perform detailed operations are added to the status bar.  
From the combo button you can operate properties that can be set in Editor Preferences > Region & Language.    
You can assign shortcut keys to all functions in the combo button menu.  

## Settings

![KeyboardShortcuts](https://github.com/Naotsun19B/LanguageSwitcher-Document/assets/51815450/fb5ba448-2d07-4e76-b19d-1748eef83fab)

The shortcut keys introduced in "Functions And Usage" can be changed from the keyboard shortcuts in the editor preferences.  

![Settings](https://github.com/Naotsun19B/LanguageSwitcher-Document/assets/51815450/989f2088-9326-4861-a607-01622b1aa339)

| **Item**                             | **Description**                                                                                                                                              |
|--------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Status Bar Button Method             | Kind of action when the button displayed at the top of the status bar is pressed.                                                                            |
| Editor Languages                     | The list of editor language to switch to. Switching is done in order from the top, with the last language in the list switching to the first language.       |
| Editor Locales                       | The list of editor locale to switch to. Switching is done in order from the top, with the last language in the list switching to the first language.         |
| Preview Game Languages               | The list of preview game language to switch to. Switching is done in order from the top, with the last language in the list switching to the first language. |
| Notify Current Culture When Switched | Whether to notify the changed language when the editor language, editor locale, or game review language is changed.                                          |
| Notification Expire Duration         | The time for which the notification will be displayed.                                                                                                       |
## Author

[Naotsun](https://twitter.com/Naotsun_UE)

## History

- (2024/04/24) v1.2   
  Added support for UE5.4  

- (2023/09/09) v1.1   
  Added the ability to change the time zone display settings from the status bar    
  Added support for UE5.3  

- (2023/08/28) v1.0   
  Publish plugin
