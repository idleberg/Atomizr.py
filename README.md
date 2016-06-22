# sublime-atomizr

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![Package Control](https://packagecontrol.herokuapp.com/downloads/Atomizr.svg?style=flat-square)](https://packagecontrol.io/packages/Atomizr)
[![GitHub release](https://img.shields.io/github/release/idleberg/sublime-atomizr.svg?style=flat-square)](https://github.com/idleberg/sublime-atomizr/releases)

Convert Sublime Text completions into Atom snippets, and vice versa.

This package is also available for [Atom](https://github.com/idleberg/atom-atomizr) and as an even more powerful [Ruby script](https://github.com/idleberg/atomizr).

## Installation

### Package Control

1. Make sure you already have [Package Control](https://packagecontrol.io/) installed
2. Choose *“Install Package”* from the Command Palette (<kbd>Super</kbd>+<kbd>Shift</kbd>+<kbd>p</kbd>)
3. Type *“Atomizr”* and press <kbd>Enter</kbd>
4. Repeat steps 2 and 3 to install *“Better CoffeeScript”* (recommended)

With [auto_upgrade](http://wbond.net/sublime_packages/package_control/settings/) enabled, Package Control will keep all installed packages up-to-date!

### Manual installation

Since [package dependencies](https://packagecontrol.io/docs/dependencies) are handled by Package Control, manual installation is not advised! If you still want to install from source, you probably know what you are doing so we won’t cover that here.

## Usage

The [Command Palette](http://docs.sublimetext.info/en/latest/reference/command_palette.html) currently offers the following commands, each prefixed with “Atomizr”:

* Automatic conversion
* Convert Sublime Text to Atom (completions)
* Convert Sublime Text to Atom (snippet)
* Convert Atom to Sublime Text

**Note:** Since automatic conversion is based on scope, make sure the [Better CoffeeScript](https://packagecontrol.io/packages/Better%20CoffeeScript) package is installed as well.

### Keyboard Shortcuts

*The following examples all use the Mac OS X shortcuts, for Linux or Windows use <kbd>Ctrl</kbd>+<kbd>Alt</kbd> rather than just <kbd>Ctrl</kbd>.*

Memorizing the keyboard shortcuts for conversion is easy. Just think of the <kbd>S</kbd> key for Sublime Text and the <kbd>A</kbd> key for Atom:

* Sublime Text to Atom (S to A): <kbd>Ctrl</kbd>+<kbd>S</kbd>, <kbd>Ctrl</kbd>+<kbd>A</kbd>
* Atom to Sublime Text (A to S): hold <kbd>Ctrl</kbd>+<kbd>A</kbd>, <kbd>Ctrl</kbd>+<kbd>S</kbd>

For automatic conversion, press <kbd>Ctrl</kbd>+<kbd>C</kbd> twice.

# License

This work is licensed under the [The MIT License](LICENSE).

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/sublime-atomizr) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`
