# 🎉 Welcome to POWr Twitter Feed for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrtwitterfeed',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrtwitterfeed', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrtwitterfeed/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Twitter Feed CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrtwitterfeed/powrtwitterfeed.zip)
2. Unzip the downloaded plugin  `powrtwitterfeed.zip`  and put the resulting `powrtwitterfeed` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrtwitterfeed

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrtwitterfeed';



## How to create and edit POWr Twitter Feed:

After the POWr Twitter Feed for CKEditor plugin is installed, it's easy to create and update Twitter Feed!

1. Easily add a Twitter Feed within the CKEditor by clicking the `Insert Twitter Feed` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Twitter Feed will then appear within the Editor. Click `Edit Twitter Feed` to open the POWr Editor and create and update your Twitter Feed.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
