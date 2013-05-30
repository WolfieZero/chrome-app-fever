Fever° Chrome App
===============================================================================


Pointing Fever To Your Server
-------------------------------------------------------------------------------

In 'manifest.json' change `{{address}}` to the location of your Fever


    {
        ...
        "urls": ["http://{{address}}/"],
            "launch": {
                "web_url": "http://{{address}}"
            }
        ...
    }

Becomes...

    {
        ...
        "urls": ["http://fever.mysite.com/"],
            "launch": {
                "web_url": "http://fever.mysite.com/"
            }
        ...
    }


Adding To Chrome
-------------------------------------------------------------------------------

1. Make sure you have Developer Mode enabled, if not then go into the Chrome 
   Menu and head to **Tools > Extensions** and tick the box "Developer mode".

2. Click on "Load unpacked extension..." and navigate to this folder.

3. Click "Select" and you should have a new app in the menu