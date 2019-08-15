# 🎉 Welcome to POWr Count Up Timer for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrcountuptimer',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrcountuptimer', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrcountuptimer/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Count Up Timer CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrcountuptimer/powrcountuptimer.zip)
2. Unzip the downloaded plugin  `powrcountuptimer.zip`  and put the resulting `powrcountuptimer` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrcountuptimer

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrcountuptimer';



## How to create and edit POWr Count Up Timer:

After the POWr Count Up Timer for CKEditor plugin is installed, it's easy to create and update Count Up Timer!

1. Easily add a Count Up Timer within the CKEditor by clicking the `Insert Count Up Timer` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Count Up Timer will then appear within the Editor. Click `Edit Count Up Timer` to open the POWr Editor and create and update your Count Up Timer.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
