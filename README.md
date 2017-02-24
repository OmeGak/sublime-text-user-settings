Sublime Text - User settings
==============================
My user settings and packages for Sublime Text.

## Features
The awesome [SoDaReloaded Theme](https://github.com/Miw0/sodareloaded-theme) and [Monokai Extended](https://github.com/jonschlinkert/sublime-monokai-extended) color scheme.

Sensible set of preferences in [Preferences.sublime-settings](Preferences.sublime-settings-sample), mainly for handling indentation, trailing whitespaces and tweaking several other small features. Go check the file for an extensive listing of features. It's commented and easy to read!

Development packages:
* [DocBlockr](https://github.com/spadgos/sublime-jsdocs): Simplifies writing DocBlock comments.
* [Emmet](http://emmet.io/): The essential toolkit for web-developers.
* [SublimeCodeIntel](https://github.com/Kronuz/SublimeCodeIntel): Full-featured code intelligence and smart autocomplete engine.
* [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3): Interactive code linting framework for Sublime Text 3.
* [SublimeLinter-flake8](https://github.com/SublimeLinter/SublimeLinter-flake8): Linter for Python, using flake8.
* [SublimeLinter-contrib-eslint](https://github.com/roadhump/SublimeLinter-eslint): This linter plugin for SublimeLinter provides an interface to ESLint.
* [SublimeLinter-contrib-sass-lint](https://github.com/skovhus/SublimeLinter-contrib-sass-lint): SublimeLinter plugin for Sass/SCSS syntax, using sass-lint (node.js).

Interface packages:
* [BracketHighlighter](https://github.com/facelessuser/BracketHighlighter): Bracket and tag highlighter for Sublime Text.
* [BufferScroll](https://github.com/titoBouzout/BufferScroll): Enables typewritter scrolling.
* [Git](https://github.com/kemayo/sublime-text-git): Plugin for some git integration.
* [GitGutter](https://github.com/jisaacks/GitGutter): A Sublime Text 2/3 plugin to see git diff in gutter .
* [GitHub Tools](https://github.com/temochka/sublime-text-2-github-tools): A set of handy tools to use Sublime Text 2+ with Github.
* [Keymaps](https://github.com/MiroHibler/sublime-keymaps): Find a keymap for... and show all enabled keymaps in a Cheat Sheet.
* [SideBarEnhancements](https://github.com/titoBouzout/SideBarEnhancements): Enhancements to Sublime Text sidebar. Files and folders.

Language packages:
* [AngularJS](https://github.com/angular-ui/AngularJS-sublime-package): AngularJS code completion, snippets, go to definition, quick panel search, and more.
* [CMake](https://github.com/zyxar/Sublime-CMakeLists): Syntax highlighting for CMake files.
* [LESS](https://github.com/danro/LESS-sublime): LESS syntax highlighting for Sublime Text.
* [JavaScriptNext](https://github.com/Benvie/JavaScriptNext.tmLanguage): ES6 syntax highlighting.
* [Jinja2](https://github.com/mitsuhiko/jinja2-tmbundle): Synxtax highlighting for Jinja2 templates.
* [Mako](https://github.com/marconi/mako-tmbundle): Syntax highlighting for Mako templates.
* [Puppet](https://github.com/russCloak/SublimePuppet): Puppet (puppetlabs.com) highlighting, snippets and completion for Sublime Text 2.
* [SASS](https://github.com/P233/Syntax-highlighting-for-Sass): A new syntax highlighting package for both SCSS and Sass.

Writing packages:
* [Dictionaries](https://github.com/titoBouzout/Dictionaries): Hunspell UTF8 dictionaries for Sublime Text. [Spell check]
* [AutoWrap](https://github.com/randy3k/AutoWrap): Auto (Hard) Wrap for Sublime Text 2/3
* [LaTeXTools](https://github.com/SublimeText/LaTeXTools)*: LaTeX plugin.
* [MarkdownEditing](https://github.com/ttscoff/MarkdownEditing): The humble beginnings of a better Markdown editing.
* [Markdown Preview](https://github.com/revolunet/sublimetext-markdown-preview): Markdown preview plugin.
* [Pandoc](https://github.com/jgm/pandoc)*: Universal markup converter.
* [PastePDF](https://github.com/compleatang/sublimetext-pastepdf): Paste PDF text block to Sublime after stripping new lines.

Misc tools:
* [Less2Css](https://github.com/timdouglas/sublime-less2css): Sublime Text Plugin to compile less files to css on save.
* [PlainTasks](https://github.com/aziz/PlainTasks): An opinionated todo-list plugin for Sublime Text editor (version 2 and 3).

(*) _These packages have dependencies that won't be installed. Check the link for further instructions._

## Install
Install [PackageControl](http://wbond.net/sublime_packages/package_control) for it to automatically download the other packages later on.

Go to your Packages directory:
* OS X: `cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/`
* Linux: `cd ~/.config/sublime-text-3/Packages`

Backup your current `User` package:

```
mv User/ User-old/
```

Clone the repository as your `User` package:

```
git clone https://github.com/OmeGak/sublime-text-user-settings.git User
```

Restart Sublime Text and you should be good to go. It won't harm keeping an eye on the console output (`` Ctrl+` ``) to check if there is any problem.

## Update
Go to your `User` package directory and just pull from the repository:

```
git pull
```

Once again, restart Sublime Text and check for errors on the console output (`` Ctrl+` ``).

## Extra
Some tips:
* Configure [Dropbox sync](http://opensourcehacker.com/2012/05/24/sync-and-back-up-sublime-text-settings-and-plug-ins-using-dropbox-on-linux-and-osx/).
* Integrate this repo in your favorite *.dotfiles* framework. This is [mine](https://github.com/OmeGak/dotfiles).

## Warning
Remember that these are my personal settings and packages, so be wary of any unwanted features that can be added or removed without notice. If you find them useful, it's probably better to fork the repository and modify it to best fit your needs.
