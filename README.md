# Static Space plugin for CKEditor 4

This plugin attaches the toolbar panel to one of the editor's corners. The toolbar hides when the editor loses focus.

By default this plugin is used with **inline editing** and replaces Floating Space plugin. In order to use this plugin with **standard editor** (iframe or div) you should change `config.staticSpacePriority`.

### Configuration

* `config.staticSpacePositionY` - vertical position of the toolbar. 

  Allowed values: `'top'`, `'bottom'`. 

  Defaults to: `'top'`.
* `config.staticSpacePositionX` - horizontal position of the toolbar. 

  Allowed values: `'left'`, `'right'`. 

  Defaults to: `'left'`.
* `config.staticSpacePriority` - plugin load priority. For `CKEDITOR.replace` mode (iframe or div) the value should be <= 9. 

  Defaults to: 19.
  
### Known issues

The editable element should have 100% width of it's parent element.

### License

Licensed under the GPL, LGPL and MPL licenses, at your choice.

For full details about the license, please check the LICENSE.md file.
