Sublime Text 2 - User settings
==============================
My user settings for Sublime Text 2.

## Features
The awesome [Soda Theme](https://github.com/buymeasoda/soda-theme/).

Preferences tweaks in [Preferences.sublime-settings](/blob/master/Preferences.sublime-settings) for handling indentation and trailing whitespaces consistently. Check the file for an extensive listing of features. It's commented and easy to read.

Development packages:
* [DocBlockr](https://github.com/spadgos/sublime-jsdocs): Simplifies writing DocBlock comments.
* [Emmet](http://emmet.io/): The essential toolkit for web-developers.
* [SublimeCodeIntel](https://github.com/Kronuz/SublimeCodeIntel): Full-featured code intelligence and smart autocomplete engine.
* [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter): Inline lint highlighting.

Interface packages:
* [Git](https://github.com/kemayo/sublime-text-2-git): Plugin for some git integration.
* [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements): Enhancements to Sublime Text sidebar. Files and folders.
* [SideBarGit](https://github.com/SublimeText/SideBarGit): Add git commands to sidebar.

Writing packages:
* [LaTeXTools*](https://github.com/SublimeText/LaTeXTools): LaTeX plugin.
* [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview): Markdown preview plugin.
* [Pandoc*](https://github.com/jgm/pandoc): Universal markup converter.

(*) _These packages have dependencies that won't installed_

## Install
Install [PackageControl](http://wbond.net/sublime_packages/package_control) for it to automatically download the other packages later on.

Go to your Packages directory:
* OS X: `cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/`
* LINUX: `cd ~/.Sublime\ Text\ 2/Packages`

Backup your current `User` package:

```
mv User/ User-old/
```

Clone the repository as your `User` package:

```
git clone https://github.com/OmeGak/sublime-text-2-user-settings.git User
```

Restart Sublime Text 2 and you should be good to go. It won't harm keeping an eye on the console output (`` Ctrl+` ``) to check if there is any problem.

## Update
Go to your `User` package directory and just pull from the repository:

```
git pull
```

Once again, restart Sublime Text 2 and check for errors on the console output (`` Ctrl+` ``).

## Warning
Remember that these are my personal settings and packages, so be wary of any unwanted features that can be added or removed without notice. If you find them useful, it's probably better to fork the repository and modify it to best fit your needs.