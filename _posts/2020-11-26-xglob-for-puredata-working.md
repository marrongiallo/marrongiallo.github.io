---
layout: post
title:  "xglob tested on linux is out"
---

# XGLOB

From README file:

xglob-plugin is a "pure data" (pd) plugin. Once installed, it allows you to obtain, via the "netsend" pd object, the list of files inside a folder.

In this version of the program I can **only get the list of wav files**

The plugin starts a socket server. Due to the "vwait" statement, this plugin must be the last one in the list of pure date plugins you installed. So if you need to rename the file.

tested on linux (Ubuntu 20.10) with tcl Tk 8.6 and pd (vanilla) 0.51.1

github: [xglob](https://github.com/marrongiallo/xglob)

![xglob logo](/assets/xblog_logo.png)
