# In-app browser framebreaker demo

If you open a link in TikTok's or Instagram's apps, they don't open using the
native browser, but using the respective social network's built-in browser.
This causes serious privacy concerns for once, but according to
stackoverflow, also interferes with basic functions such as printing the
website.

For more information see [Adrian Holovaty's
blogpost](https://www.holovaty.com/writing/framebust-native-apps/) or [Felix
Krause](https://krausefx.com/blog/ios-privacy-instagram-and-facebook-can-track-anything-you-do-on-any-website-in-their-in-app-browser).

I cobbled together some stackoverflow answers and github gists I found on the
internet out of personal curiosity (see `index.html` sourcecode for
references). A lot of advice is outdated, and so will this website for sure.

This repo provides a website with a button that breaks the website out of the
in-app browser. Tested as of 2022 with TikTok's and Instagram's in-app browser.

[See demo here.](https://untitaker.github.io/in-app-browser-framebreaker)

## TODO

* Detect in-app browsers, i.e. don't rely on button-press
