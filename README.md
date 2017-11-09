# Barcode Generator : Plugin API Docs

|                      | &nbsp;
| -------------------- | ---------------------------------------------------------------
| __Corona Store__     | [BarcodeGenerator](http://store.coronalabs.com/plugin/BarcodeGenerator)

## Overview

The BarcodeGenerator plugin can be used in your [Corona](https://coronalabs.com/products/corona-sdk/) project. It enables you to create 2of5I or 3of9I barcode.


## Syntax

	local BarcodeGenerator = require "plugin.BarcodeGenerator"

### Functions

##### [BarcodeGenerator.new2Of5I()](new2Of5I.md)

##### [BarcodeGenerator.new3Of9I()](new3Of9I.md)


## Project Configuration

### Corona Store Activation

In order to use this plugin, you must activate the plugin at the [Corona Store](http://store.coronalabs.com/plugin/BarcodeGenerator).


### SDK

When you build using the Corona Simulator, the server automatically takes care of integrating the plugin into your project.

All you need to do is add an entry into a `plugins` table of your `build.settings`. The following is an example of a minimal `build.settings` file:

``````
settings =
{
	plugins =
	{
		-- key is the name passed to Lua's 'require()'
		["plugin.BarcodeGenerator"] =
		{
			-- required
			publisherId = "com.keetiz",
		},
	},
}
``````

### Enterprise

If you have activated this plugin, you can download this plugin from the corresponding plugin page in the [Corona Store](http://store.coronalabs.com/plugin/BarcodeGenerator).



### Support

More support is available from the KEETIZ team:

* [E-mail](mailto:bancel@keetiz.com)
* [Plugin Publisher](https://www.keetiz.com)


## Compatibility

| Platform                     | Supported
| ---------------------------- | ----------------------------
| iOS                          | Yes
| Android                      | Yes
| Android (GameStick)          | Yes
| Android (Kindle)             | Yes
| Android (NOOK)               | Yes
| Android (Ouya)               | Yes
| Mac App                      | Yes
| Win32 App                    | Yes
| Windows Phone 8              | Yes
| Corona Simulator (Mac)       | Yes
| Corona Simulator (Win)       | Yes
