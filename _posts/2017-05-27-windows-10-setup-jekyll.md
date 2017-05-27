---
layout: post
categories: Tool
title: Windows 10 setup jekyll
date: 2017-05-12 22:42:00 +0800
description: windows 10 setup jekyll
keywords: Tool, Windows 10, Jekyll
---

## 1. Install a package manager for Windows called [Chocolatey](https://chocolatey.org/install)
1. Install a package manager for Windows called [Chocolatey](https://chocolatey.org/install)
>@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

##2. Install Ruby via Chocolatey: `choco install ruby -y`
>choco install ruby -y

##3. Reopen a command prompt and install Jekyll: `gem install jekyll bundler`
>gem install jekyll

转载请注明出处，本文采用 [CC4.0](http://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh) 协议授权
