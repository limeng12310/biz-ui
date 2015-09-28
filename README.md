BizUI - A jQuery plugin for business UI components
===============

[![Code Climate][codeclimate-image]][codeclimate-url]
[![Build Status][travis-image]][travis-url]
[![NPM Version][npm-image]][npm-url]

[![NPM Stat][npm-stat-image]][npm-stat-url]

Features
--------
- Include 14 types of UI components: Button, Input, Textarea, Radio, Checkbox, Select, Dialog, Panel, Tooltip, Tab, Page, Tree, Calendar, Table.
- IE9+, Firefox, Chrome, Safari and Opera supported.
- Import other awesome components with the constant API using Adapter Pattern.

<!--<img src="http://bizdevfe.github.io/biz-ui/img/adapter.png" />-->

Usage
-----
Download the [latest version](https://github.com/bizdevfe/biz-ui/releases), or:

    npm install biz-ui

Together with jQuery, include BizUI in your page:

    <script src="jquery.js" type="text/javascript"></script>
    <script src="jquery.bizui.js" type="text/javascript"></script>

Include the CSS file:

    <link href="jquery.bizui.css" rel="stylesheet" type="text/css" />

To initialize:

    // recommended
    $('button').bizButton();
    
    // or create instance by constructor
    var button = new bizui.Button($('button'));

See [Demos](http://bizdevfe.github.io/biz-ui/quickview) and [API documentations](http://bizdevfe.github.io/biz-ui).

Build
-----
Do the code inspection, optimization or API generation here:

    $ cd tool
    $ build.sh

License
-------
Licensed under the [MIT license](http://opensource.org/licenses/MIT).

Feedback
--------
For issues or suggestions please see [biz-ui](https://github.com/bizdevfe/biz-ui) on Github. Thanks for your support!

[codeclimate-image]: https://codeclimate.com/github/bizdevfe/biz-ui/badges/gpa.svg
[codeclimate-url]: https://codeclimate.com/github/bizdevfe/biz-ui
[travis-image]: https://travis-ci.org/bizdevfe/biz-ui.svg
[travis-url]: https://travis-ci.org/bizdevfe/biz-ui
[npm-image]: http://img.shields.io/npm/v/biz-ui.svg
[npm-url]: https://npmjs.org/package/biz-ui
[npm-stat-image]: https://nodei.co/npm/biz-ui.png?downloads=true
[npm-stat-url]: https://nodei.co/npm/biz-ui
