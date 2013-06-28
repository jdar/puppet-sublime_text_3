# Sublime Text 3 Beta Puppet Module for Boxen

[![Build Status](https://travis-ci.org/mozilla-boxen/puppet-sublime_text_3.png?branch=master)](https://travis-ci.org/mozilla-boxen/puppet-sublime_text_3)

Install [Sublime Text 3 Beta](http://www.sublimetext.com/3), a text-editor/IDE for Mac

## Usage

```puppet
include sublime_text_3
sublime_text_3::package { 'GitGutter':
  source => 'jisaacks/GitGutter'
}
```

## Required Puppet Modules

None.
