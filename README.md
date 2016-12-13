# Endless Sky Plugin Share

### About
ES Plugin Share is a plugin sharing website for [Endless Sky](http://endless-sky.github.io/)

// Note: I changed my name to CodeDraken so replace it with any links that are evan153. Eventually this should be moved or an offical one should be created on the main Endless Sky website.
Website: https://codedraken.github.io/ES-Mod-Share/

### Installing plugins
Generally, installing a plugin is as simple as dropping it into the Endless Sky `plugin` folder for your operating system, specified here: https://github.com/endless-sky/endless-sky/wiki/CreatingPlugins.
However, some plugins may have issues with other ones, so be sure to read each plugin's description before installation, and **back up your saves**.

### Submitting a plugin to the website
1. Go to the `plugins` folder and add your own plugin folder (eg. `/mods/mypluginfolder`). Inside, add a `metadata.json` file (eg. `/mods/mypluginfolder/metadata.json`). The easiest way is to copy the [the example plugin](https://github.com/evan153/ES-Mod-Share/tree/gh-pages/mods/mod-example-title).

2. Images may be either externally linked or hosted by the site.
    - If you are using a local image (included in the website's source, not hosted elsewhere), prepend `local:` before the image name to tell the website that it's not a hyperlink.
        - eg. `local:banner.png`, `local:thumbnail.jpg`
    - The **thumbnail** is a small image that represents your plugin in the list. 
    - The **banner** is larger and shown when your plugin is being viewed by the user.

Finally, make a pull request!

Note: The data format for the plugin data is YAML, but it is processed to json, which is why it has the json file extension.

All plugin data is available in json format at https://evan153.github.io/ES-Mod-Share/mods-json.html.
