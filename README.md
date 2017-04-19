# jQuery Image Resolution Checker

> Simple jQuery plugin to check Image Resolution upon input-file selection

This plugin will show an error if the selected image in an HTML Input is not in the intended resolutions.

## Basic Usage
```
$("input[type=file]").checkImageSize();
```
## Options
```
$("input[type=file]").checkImageSize({
    minWidth: 800,		// Numeric; Pixel value
    minHeight: 600,		// Numeric; Pixel value
    maxWidth: 8000,		// Numeric; Pixel value
    maxHeight: 6000,		// Numeric; Pixel value
    showError: true,		// Boolean; Whether to show error messages
    ignoreError: false		// Boolean; Whether to ignore error and let the image pass through
});
```

----
Made with Love by **Jose Philip Raja** &mdash; Founder & Creative Director of **CreaveLabs IT Solutions LLP**
http://josephilipraja.com, https://creavelabs.com
