# firefox-customization
This repository holds my personal customization for Mozilla Firefox.
I personally like to use a sidebar-aaproach to browsing because of many tabs.
All these tabs are better represented as a tree (which is done by the Sidebery addon).
Therefore I want to hide the tab bar at the top to regain that space and make the UI less cluttered.

# 1. First off, any customization like this needs to be enabled since Firefox 69

## 1.1 Enable Loading of userChrome.css and userContent.css in Firefox:

 - Open a new tab in Mozilla Firefox.
 - Type about:config in the address bar. 
 - Confirm that you will be careful if a warning message appears for you.
 - Enter the following text in the search box: `toolkit.legacyUserProfileCustomizations.stylesheets`.
 - Set the option `toolkit.legacyUserProfileCustomizations.stylesheets` to `True`.
 
 The functionality of the external CSS files is now restored.

## 1.2 Creating / Updating userChrome.css File:

 - Open a new tab in Mozilla Firefox.
 - Type about:profiles in the address bar.
 - identify your profile.
 - open the profile (root) directory.
 - create a new folder inside this folder called `chrome` (spelled exactly like this).
 - inside that `chrome` folder you can now create / update / place a file called `userChrome.css` (again, spelled exactly like this)

# 2. With the customization functionality restored, use the `userChrome.css` from this repo 

- clone or download this repository either directly inside that new `chrome` folder or copy the `userChrome.css` file manually there.
- restart Firefox for the changes to be applied

Firefox should now be customized accordingly
