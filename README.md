# Image Preloader Userscript

## Userscript for preloading images on Ponybooru.

Check the [branches](https://github.com/marktaiwan/Derpibooru-Image-Preloader/branches/all) for all supported sites.

For instructions, see the [thread on Derpibooru](https://derpibooru.org/forums/meta/topics/userscript-markers-derpibooru-image-preloader).

Requires [Violenmonkey](https://violentmonkey.github.io/)  
[Click here to install](https://github.com/marktaiwan/Derpibooru-Image-Preloader/raw/ponybooru/ponybooru-image-preload.user.js)

## Settings and features

Once installed, the script settings could be found on the [user settings page](https://ponybooru.org/settings/edit?active_tab=userscript).

![settings](https://raw.githubusercontent.com/marktaiwan/Derpibooru-Image-Preloader/ponybooru/screenshots/settings.PNG)

##### Start prefetch…

By default, the preloading will start only after the current page has finished loading all resources. This helps if you're bandwidth limited. Alternately, if you're limited by latency (i.e. how long the server took to respond to your request), you could choose to start the preloading process as soon as possible.

##### Preloaded images

*prev/next* - These are the images the site will navigate you to if you use the "Previous image" and "Next image" button.  
*description*  - Some uploaders very helpfully includes links to the next image in the description box. This is especially useful when sometimes the comics are uploaded out of order.

##### Image scaling

Pretty self explanatory, chooses whether you want to preload the scaled or full sized version of images.

##### Auto-off

Let's face it, this script serves a pretty niche purpose, have it turned on all the time when you aren't using it is a waste of bandwidth. The script automatically turns itself off after awhile. It's set to 10 minutes by default.

##### Quick toggle

On the image pages, you will find a dropdown list allowing you to turn the preloader on or off.

![quick toggle](https://raw.githubusercontent.com/marktaiwan/Derpibooru-Image-Preloader/ponybooru/screenshots/toggle%20button.PNG)
