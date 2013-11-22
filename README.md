## Installation

**OS X**

```
$ ssh-keygen -t rsa -C "fitztrev@gmail.com"

$ sudo xcodebuild -license
$ xcode-select --install

$ ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
$ brew install git zsh

$ git clone git@github.com:fitztrev/trevdev.git ~/trevdev
$ cd ~/trevdev
$ make install mac
```

*Configuring iTerm2:*

1. Install `Monaco for Powerline` font
2. Set iTerm2 preferences URL on the General tab to the location of the `iterm2` folder
3. Restart iTerm2

**Ubuntu**

```
$ sudo apt-get install -y build-essential git vim zsh
$ git clone https://github.com/fitztrev/trevdev.git ~/trevdev
$ cd ~/trevdev
$ make install linux
```

## Updating

```
$ make
```

## Apps

List of the applications that I keep installed.

### App Store
* App2Dmg
* CopyClip
* Go2Shell
* Lingo IRC
* LittleIpsum
* Xcode

### 3rd Party
* [Alfred](http://www.alfredapp.com/)
* Android Studio
* CodeKit
* CoRD
* Chrome
* Firefox
* [Flux](http://justgetflux.com/)
* iTerm2
* LICEcap - For recording GIFs
* Mou
* MySQL Workbench
* Reggy
* Scrup
* [Sequel Pro](http://www.sequelpro.com/)
* [Shuttle](http://fitztrev.github.io/shuttle/)
* Skype
* [Slate](https://github.com/jigish/slate)
* Spotify
* Vagrant
* VirtualBox

### Chrome Extensions
* Adblock Plus
* Dev Docs
* Ghostery
* Hover Zoom
* JSONView
* LastPass
* LiveReload
* OneTab
* PageSpeed Insights
* PHP Docs-to-go
* Postman (Packaged app)
* Reddit-Style Comments for Hacker News
* Speed Tracer
* Web Developer

### Firefox Add-ons
* Auto Reload
* ColorZilla
* Firebug
* Firepicker
* JSONView
* LastPass
* [Page Speed](https://developers.google.com/speed/docs/insights/using_firefox)
* Selenium IDE
* Skip Cert Error
* Web Developer Toolbar
