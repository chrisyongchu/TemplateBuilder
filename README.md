# Template Builder
[TinyMCE](https://www.tinymce.com/) is a platform independent web-based JavaScrip HTML WYSIWYG editor. In order to use this plugin, you simply need to define the plugin descriptor and provide a small snippet of javascript to configure this plugin.

To enable the Template Builder plugin, you will need to configure the TinyMCE's init() method. The following example provides the minimum javascript needed.

```javascript
tinymce.init({
  selector: 'textarea',
  plugins: 'template_builder'
});
```
![template builer](https://sanbox.org/etc/blob/master/tb/tb_toolbar_icon.png)
