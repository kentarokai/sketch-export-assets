# sketch-export-assets

Export assets for Android, iOS, Windows Phone in Sketch.

Also check [GeertWille's new sketch plugin] to export assets for iOS directly from Sketch into Xcodes assets catalog.

[GeertWille's new sketch plugin]:https://github.com/GeertWille/sketch-to-xcode-assets-catalog

## Installation

The actual location of your Sketch plugins directory will vary. To open it just click on the `Reveal Plugins Folder` under the `Plugins` menu in sketch.

Run following command after going to the sketch plugins folder:

`git clone git@github.com:kentarokai/sketch-export-assets.git`

OR

Use [Sketch Toolbox]

Once you have checked out the plugin repository into the relevant directory, you'll find the plugin functions under the Plugins menu in Sketch.

## Assumptions

~~The plugin assumes you design your layouts in mdpi, which means 1px = 1dp~~

From now on this is configurable!

## Shortcuts

* iOS Export: ctrl + alt + shift + 1
* Android Export: ctrl + alt + shift + 2
* Windows Export: ctrl + alt + shift + 3

## Adding Padding to slices
From now on you can manually decide how big you want your exported asset to be. Just include a slicelayer in the group of that asset and it will not use the size of the group but the size of that slicelayer...

## Credits
This plugin is based on [zmaltalker's] project [sketch-android-assets]. I needed to export my assets to multiple platforms that's why I extended his project to cover other platforms.


[sketch-android-assets]:https://github.com/zmalltalker/sketch-android-assets
[zmaltalker's]:https://github.com/zmalltalker
[Sketch Toolbox]:http://sketchtoolbox.com
