# BarcodeGenerator.new2Of5I()

|                      | &nbsp;
| -------------------- | ---------------------------------------------------------------
| __Type__             | [function](http://docs.coronalabs.com/api/type/Function.html)
| __Library__          | [BarcodeGenerator.*](README.md)


## Overview

This function is to create a 2 of 5 Interleaved barcode


## Syntax

	BarcodeGenerator.new2Of5I( group, codeStr, width, height )

##### group <small>(required)</small>
_[Group](http://docs.coronalabs.com/api/type/)._ Destination group for the barcode

##### codeStr <small>(required)</small>
_[String](http://docs.coronalabs.com/api/type/)._ Code for the barcode

##### width <small>(required)</small>
_[Constant](http://docs.coronalabs.com/api/type/)._ Width of the barcode

##### height <small>(required)</small>
_[Constant](http://docs.coronalabs.com/api/type/)._ Height of the barcode

## Examples

``````lua
local sceneGroup = self.view
local barcode = BarcodeGenerator.new2Of5I(sceneGroup, "2599874562", 200, 100)
barcode.x = display.actualContentWidth / 2
barcode.y = display.actualContentHeight / 2
``````
