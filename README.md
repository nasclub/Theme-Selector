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

```javascript
{
	"themeCookie": "purple", // Value for the cookie, keep it simple.
	"themeName": "Purple Cloud", // Name of the theme to be displayed on the selector.
	"tagName": "Purple Tag", // Name of the user tag acquired from the store.
	"selectClass": "theme-purple", // Class name for the selector, keep it similar, theme-color.
	"colorLight": "#ab47bc", // Hex colour for the lighter tone.
	"colorDark": "#7b1fa2", // Hex colour for the darker tone.
	"background": "https://s3.amazonaws.com/files.enjin.com/851662/Theme_Backgrounds_Optimised/Theme-Purple-min.jpg" // URL for the background.
}
```
