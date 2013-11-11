tabindex
=======================

Plugin for TinyMCE 4.x that set a tabindex= on the iframe for tabbing to/from TinyMCE

## Installation and Configuration

Copy the `tabindex` folder in src to the plugins directory of your TinyMCE installation.

Include the tabindex plugin in your TinyMCE configuration by adding it to the end of the list of plugins.

```js
plugins: '... tabindex'
```

The tabindex plugin uses a single configration setting called "tabindex" that should be passed with other settings to the tinymce.init() function.

```js
tabindex: number or 'element'
```

where

```
number is a value for the tabindex (e.g. 4) or -1 for no tabindex
'element' copies the tabindex= attribute of the element replaced by TinyMCE
```

'element' is the default value.

See the [TinyMCE Documentation](http://www.tinymce.com/wiki.php/Configuration:plugins) for more info about plugins.
