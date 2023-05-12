# The Unofficial Economist App
This unofficial Economist app collects all the articles data of [Economist](https://economist.com) starting from January 2023. The app is used for my own use and the app is shown below.

![](https://github.com/HuangRunHua/economist-database/raw/main/cover.png)

## Why Develop

The reason why this software was developed is that the official Economist App has been removed from the App Store in China, and I cannot subscribe directly on the website (VISA is required). At the same time, with an interesting mentality, I planned to make an app similar to Apple News+, so I developed this app. 

The data acquisition of The Economist magazine is realized by `Python`, and the software is written by `Swift` language + `SwiftUI` framework.

## Content

This app is designed in the reference of `Apple News+` and the contents here are divided in to two parts:

- The Economist Espresso (Daily News Brief)
- The Economist Weekly Issue

## How to Use

If you want to use the app, you must have **an iPhone with system iOS 16.0+**, **contact me (provide your email) and I will give you TestFlight link**. 

The Espresso part will update automatically **multiple times a day**, and the way to refresh is to restart the app.

**I will update the weekly issue every Friday or Saturday**. If you find the magazine in the app is not updated, please exit the app in the background and reopen it.

> WARNING
>
> 1. Noted that the content in this app should be used under a foreign agent network environment (VPN) if you live in China mainland and people living in Hong Kong (China), Macau (China) and Taiwan (China) do not need to use proxy network.
> 2. The Content of Espresso is parsed directly through the web page of [the world in brief](https://www.economist.com/the-world-in-brief) and I have to confess the the content of Espresso parsing may fail if The Economist's web page architecture changes.

## Last But Not Least

This software is currently adapted to the iPhone and the iPad, noted that the Macs are not yet compatible (it can be used on the Mac, because I use the SwiftUI framework, but the UI may not be well adapted). Whether it will be adapted to Macs is to be determined later, because I usually use iPhone or iPad to read The Economist.
