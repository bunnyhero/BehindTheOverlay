# BehindTheOverlay Extension

[Chrome Extension](https://chrome.google.com/webstore/detail/behindtheoverlay/ljipkdpcjbmhkdjjmbbaggebcednbbme)

[Firefox extension](https://addons.mozilla.org/en-us/firefox/addon/behind_the_overlay/) (still in process of validation, may take a few days)

**One button to close any overlay on any website**  follow [Behind_Overlay](https://twitter.com/Behind_Overlay) for updates

## News

13 Jun | The works on Safari extension has already begun.

11 Jun | Firefox extension is available now ! Been a few days since I was seeking how to do it ;)

10 Jun | Assign a keyboard shortcut, [see how](https://twitter.com/Behind_Overlay/status/476250479706398722).

## In development..

* Add default shortcut as Cmd+shift+X for MacOS. And ctrl+alt+X for windows and linux ?
* Make an overlay permanently hidden for a website.


## What's it all about?

Some websites will use an overlay to mask its content with a transparent background to force you to read a message before you can see the actual content.

I find this very annoying as every site will have a different way to close that overlay popup.

This extension solves this problem by offering **you one button to close any overlay** on any website you may ever encounter.

## Extension in action

![Image](http://nicolaenmv.github.io/BehindTheOverlay/use_example_1.gif)

## Does it work everywhere ?

The extension should work on all sites that have overlays. I created a list of some of the websites that the extension is know to work: [WORKS_ON.md](WORKS_ON.md).

## Features

* Requires no special permissions.
* Extremely lightweight, relies on little known ``document.elementFromPoint`` browser's function to find elements that are in front with the highest z-index.
* Non-intrusive. The extension activates only when you click its button, thereby it has no impact on navigation performance when you don't use the extension. Doesn't inject tons of CSS rules as AdBlock extension is doing for example.
* Supports hiding of multiple DOM overlay elements.
* Enables overflow auto of the body when overlay script hides it to disable the scroll of the page.


## Feedbacks
If you have any suggestion or comment, please create an issue here or send me a tweet to [NicolaeNMV](https://twitter.com/NicolaeNMV). Any feedback is highly appreciated.

## Licence
Licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).
