# /userstyles

A collection of home-made UserStyle CSS files, to be used with Stylus or other mechanism. UserStyles are used to modify the appearance (what you see) of a select few websites which I frequently use and would rather have a different design.

Use with the **Stylus** browser addon (for [Firefox](https://addons.mozilla.org/el/firefox/addon/styl-us/), for [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)). Be cautious of similar-named addons as they’re often used to collect data without your consent. For an intoduction on how to use and experiment with Stylus (no need to be a programmer) see [“Redesign Your Favorite Websites — Stylus Extension for FireFox or Chrome”](https://medium.com/@coffmans/redesign-your-favorite-websites-stylus-extension-for-firefox-or-chrome-c5d5ae68e288).

These UserStyles may update automatically to accomodate for improvements and breaking changes, but they are primarily intented for my personal use, hence I am reluctant to changes that do not serve my use cases. You may use the [Issue page](https://github.com/Arty2/userstyles/issues) to report any unintented behaviour (bugs) or breaks (usually when the website implements a major change) that you come accross.


## Index

Click on “Install this style” to preview the CSS code and install directy if you already have Stylus enabled. All styles support automatic updates.

- Global styles
    + [Hide dickbars](#hide-dickbars) — Hides [“dickbars”](https://daringfireball.net/linked/2011/03/06/dickbar), i.e. annoying CTAs and floating bars in several websites. Currently: facebook.com, instragram.com, twitter.com, newyorker.com.
    + [Thin scrollbars](#thin-scrollbars) — Applies thin scrollbars to all windows and elements. The colors are configurable. ([Firefox only](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-width#Browser_compatibility))
- UserChrome.css
    + [tabs_to_bottom.userchrome.css](#tabs-to-bottom-userchrome-css) — Moves the tab and URL bar to the bottom of the window.
- airtable.com
    + [airtable.com dark theme](#airtablecom-dark-theme) — Dark theme for airtable.com. Beta quality, beware of 🐛.
    + [airtable.com neat kanban](#airtablecom-neat-kanban) — Modifies the display of Airtable’s Kanban view to make better use of available space and simplify the cards UI.


* * *


## Global styles

Global or single-purpose styles that apply to multiple domains.

### Hide dickbars

Hides [“dickbars”](https://daringfireball.net/linked/2011/03/06/dickbar), i.e. annoying CTAs and floating bars in several websites.  Currently: facebook.com, instragram.com, twitter.com, newyorker.com, nytimes.com, wired.com, artforum.com.

📦 [Install this style](https://raw.githubusercontent.com/Arty2/userstyles/master/_hide-dickbars.user.css)

### Thin scrollbars

Applies thin scrollbars to all windows and elements. The colors are configurable. ([Firefox only](https://developer.mozilla.org/en-US/docs/Web/CSS/scrollbar-width#Browser_compatibility))

📦 [Install this style](https://raw.githubusercontent.com/Arty2/userstyles/master/_thin-scrollbars.user.css)


## UserChrome.css

Styles to modify the User Interface of Mozilla Firefox through [UserChrome.css](http://kb.mozillazine.org/index.php?title=UserChrome.css). Their installation is [not as easy](https://www.howtogeek.com/334716/how-to-customize-firefoxs-user-interface-with-userchrome.css/), and this feature is disabled by default.

1. On Windows, navigate to `%APPDATA%\Mozilla\Firefox\Profiles` (you can copy/paste this) or locate the exact directory by visiting `about:profiles`.
2. Create a folder named `chrome` then create a file named userChrome.css inside it and paste this code.
3. If userChrome.css doesn’t seem to work, open `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets=true`.

### tabs_to_bottom.userchrome.css

Moves the tab and URL bar to the bottom of the window. It’s where browser tabs should be by default in Windows, if proximity to the taskbar matters.

💾 [See the code](https://raw.githubusercontent.com/Arty2/userstyles/master/tabs_to_bottom.userchrome.css)

![tabs to bottom for Firefox](./screenshots/tabs-to-bottom-userchrome.png)


## airtable.com

### airtable.com dark theme

Dark theme for airtable.com. Beta quality, beware of 🐛.

📦 [Install this style](https://raw.githubusercontent.com/Arty2/userstyles/master/airtable-com_dark-theme.user.css)

### airtable.com neat kanban

Modifies the display of Airtable’s Kanban view to make better use of available space and simplify the cards UI. It also modifies a collaborator field with the *configurable* title “Action of”, if it exists.

📦 [Install this style](https://raw.githubusercontent.com/Arty2/userstyles/master/airtable-com_neat-kanban.user.css)

![airtable.com neat kanban](./screenshots/airtable-com_neat-kanban.gif)


* * *

© 2020 [Heracles Papatheodorou](https://heracl.es) a.k.a [@Arty2](https://www.twitter.com/Arty2), MIT Licence