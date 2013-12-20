# meteor-gist [![Build Status][buildstatus]][buildstatusurl]

Provides a dead simple way to get and inject public gist into dynamic meteor template.

## Usage

Put `{{{gist <user> <id>}}}` in your meteor template where:

* `<user>` - github user name of gist owner
* `<id>` - gist id

### Example

```html
<template name="example">
  <div class="gist">
  	{{{gist sergeyt 7329871}}}
  </div>
</template>
```

## TODO

* Port for nodejs and browser

[buildstatus]: https://drone.io/github.com/sergeyt/meteor-gist/status.png
[buildstatusurl]: https://drone.io/github.com/sergeyt/meteor-gist/latest
