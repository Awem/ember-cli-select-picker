# Ember-cli-select-picker [![npm version](http://img.shields.io/npm/v/ember-cli-select-picker.svg)](https://npmjs.org/package/ember-cli-select-picker) [![build status](http://img.shields.io/travis/sukima/ember-cli-select-picker.svg)](https://travis-ci.org/sukima/ember-cli-select-picker)

<img align="right" src="https://sukima.github.io/ember-cli-select-picker/dist/screen-shot.png" />

This is a reinvention of the select view. It is designed to offer a [Bootstrap][1] style and function. It is highly inspired from the jQuery plugin [bootstrap-select][2] but designed for Ember-CLI apps specifically. It supports single and multiple select. It adds select all/none, and search filtering for multiple selections.

See the [demo][] for examples, usage, and code snippits.

[1]: http://getbootstrap.com/
[2]: http://silviomoreto.github.io/bootstrap-select/

## Installation

* `ember install ember-cli-select-picker`

## Using

In your templates simply replace the usual `{{view "select"}}` with `{{select-picker}}`. This addon is implemented as a component since the core Ember team is deprecating views. It is down-grades (read: backwards compatible) to mobile by keeping a select view in sync under the hood.

More options and examples are available on the [demo][] site.

```handlebars
{{select-picker value=myModel.myAttr
                content=mySelectContents
                optionGroupPath="group"
                optionLabelPath="content.label"
                optionValuePath="content.value"}}
```

## Running Tests

* `npm test` - Test with Ember release, beta, and canary
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).

[demo]: https://sukima.github.io/ember-cli-select-picker/
