# In-app browser framebreaker demo

If you open a link in TikTok's or Instagram's apps, they don't open using the
native browser, but using the respective social network's built-in browser.
This causes serious privacy concerns for once, but according to
stackoverflow, also interferes with basic functions such as printing the
website.

For more information see [Adrian Holovaty's
blogpost](https://www.holovaty.com/writing/framebust-native-apps/) or [Felix
Krause](https://krausefx.com/blog/ios-privacy-instagram-and-facebook-can-track-anything-you-do-on-any-website-in-their-in-app-browser).

[See demo here.](https://untitaker.github.io/in-app-browser-framebreaker)

I cobbled together some stackoverflow answers and github gists I found on the
internet out of personal curiosity (see `index.html` sourcecode for
references). The result: A lot of the advice found online is outdated, and
since none of this is any sort of standard, the URL schemes tried are a moving
target.

This works as of 2020 with TikTok's and Instagram's in-app browsers.
