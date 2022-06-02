# NiFi Yu Mirage

![Theme preview](https://github.com/TsukaYuriko/nifi-yu-mirage/blob/master/preview.png)

This is a dark UI theme for [Apache NiFi](https://github.com/apache/nifi).  
It is heavily inspired by the [Ayu](https://github.com/ayu-theme) theme and uses a mix of the
[Ayu colors](https://github.com/ayu-theme/ayu-colors) (mainly Mirage, with some borrowed from Light and Dark).

This repository, readme as well as the theme itself are still a work in progress. Some parts of the NiFi UI are not yet fully (or at all) themed.  
Release versions are mainly intended for the purpose of gathering feedback and identifying what still needs to be done.

The theme was created for and tested against NiFi 1.15.3. Other versions may work, but some styles may not apply across all NiFi versions
due to underlying changes in the structure or naming scheme of NiFi's UI.

# Installation

- Download the [latest release](https://github.com/TsukaYuriko/nifi-yu-mirage/releases) of the theme.
- Add a userstyle extension - e.g. Stylus ([Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)) - to your browser.
- Using the extension, create a new style. Import the .css file you downloaded.
- Add a rule that specifies which sites the style should apply to. (The regex `.*/nifi/.*` should target most standard NiFi installations.)
