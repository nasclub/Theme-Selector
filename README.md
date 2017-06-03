# Theme Selector
This HTML module enables logged in users to select different themes for Nasclub.

> This is not yet rolled out publically on Nasclub.
>
> `http://www.nasclub.co/admin/editmodule/index/preset/44424482`


### Change Log

#### Theme Selector v1.0.0
* Added a configuration array for easier changes all in one place.
* Reworked into a more automated system built around the configuration array.
* Removed redundant CSS.

#### Theme Overhaul (Base Module)
Base module used as a concept for variable CSS reflecting theme selection.


### Current Themes

* Default (Red)
* Purple Cloud (Purple)
* Deep Sea (Blue)
* Forest Lover (Green)
* Burnt Sunset (Orange)
* Black Sky (Grey)


### Configuration

Using JSON, we set up configuration objects within the `themeConfig` array. The system will pull data from the array and build the selector accoradingly.

#### Configuration JSON Example:
```javascript
{
	"themeCookie": "purple",
	"themeName": "Purple Cloud",
	"tagName": "Purple Tag",
	"selectClass": "theme-purple",
	"colorLight": "#ab47bc",
	"colorDark": "#7b1fa2",
	"background": "https://s3.amazonaws.com/files.enjin.com/851662/Theme_Backgrounds_Optimised/Theme-Purple-min.jpg"
}
```

`themeCookie`: Value assigned to the `currentTheme` cookie, keep the value simple but distinctive.

`themeName`: Full name of the current theme to be displayed within the theme selector modal.

`tagName`: Full name of the user tag created for that specific theme, acquired through the store.

`selectClass`: Name of the class used for building the theme selector modal, keep all class names similar, usually `theme-` followed by the `themeCookie` value.

`colorLight`: Hex colour for the lighter shade of the theme.

`colorDark`: Hex colour for the darker shade of the theme.

`background`: Url of the background image used for the theme.
