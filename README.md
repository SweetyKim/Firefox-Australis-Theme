# Photon Australis
Bringing the old Australis UI back to Firefox

![alt text](assets/images/screen-1.png "Photon Australis Dark Main Window")
<br />
<br />
<br />
![alt text](assets/images/screen-2.png "Photon Australis Dark Top Bar")
<br />
<br />
<br />
![alt text](assets/images/default-theme.png "Photon Australis Default Theme")

## Why?
I wanted to be able to use a more familiar UI for Firefox, so I branched this project off and made a few modifications.

## ⚠ Support note ⚠:
I will be updating this CSS for the latest version of Firefox for Windows 7 if you want to install it on older versions or a different OS feel free to use [Wilfredwee's Version](https://github.com/wilfredwee/photon-australis)

### How to Install:
1. Go to your Firefox browser, type `about:config` in your url bar.
1. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`
1. Type `about:profiles` in your url bar.
1. Under the profile that is in use (The message is something like `This is the profile in use and it cannot be deleted.`), click `Open Folder` on the `Root Directory` row.
1. If that folder does not have a `chrome` folder, create a folder, name it `chrome`.
1. In the `chrome` folder, create a file named `userChrome.css`
1. Determine what Firefox theme you are using:
    1. Click the icon with 3 lines on the top right corner to open the context Menu.
    1. Select `Customize`.
    1. At the bottom left of your screen, select `Themes`.
    1. Choose or determine which theme you want to use, they can either be `Dark`, `Default`, or `Light`.
1. Copy and paste the code that matches your Firefox theme: [Dark](./userChrome-dark.css), [Default](./userChrome-default.css), [Light](./userChrome-light.css) into your `userChrome.css` file that you have created.
1. Restart Firefox and you're done

## Something's Broken
I'll try to fix whatever's broken but I can't guarantee anything

## FAQ
### Nothing has changed for me
Make sure that your file extension for `userChrome.css` is correct. Most likely a problem for Windows, refer to [this issue](https://github.com/wilfredwee/photon-australis/issues/104). 
