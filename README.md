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
````
{
		"themeCookie": "purple",
		"themeName": "Purple Cloud",
		"tagName": "Purple Tag",
		"selectClass": "theme-purple",
		"colorLight": "#ab47bc",
		"colorDark": "#7b1fa2",
		"background": "https://s3.amazonaws.com/files.enjin.com/851662/Theme_Backgrounds_Optimised/Theme-Purple-min.jpg"
	}
  ````
