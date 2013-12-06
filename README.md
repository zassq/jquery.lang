jquery.lang
===========

A simple plugin to display string in desired language

Usage:
------

Initial plugin:
var lang = $.lang({options});

Display your string:
lang.show(string);
// lang.show('404error');

Options:
--------

1. lang
What language you'd like to display
// default: lang: 'zh-cn'

2. lang_file
Path to your language json file
// see my demo file