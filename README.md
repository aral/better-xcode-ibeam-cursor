Better Xcode ibeam cursor
=================

Better i-beam (text cursor) for Xcode for dark background / light text color themes.

### Directions:

1. Clone this repository (or fork it if you want to customize the tiff yourself!)
2. Create a backup of `/Applications/Xcode.app/Contents/SharedFrameworks/DVTKit.framework/Resources/DVTIbeamCursor.tiff`
3. Copy (`sudo cp`) the tiff to `/Applications/Xcode.app/Contents/SharedFrameworks/DVTKit.framework/Resources/DVTIbeamCursor.tiff`
4. Restart Xcode

**Note**
For newer versions of Xcode (5.1.1 for instance) the path for the cursor .tiff file is `/Applications/Xcode.app/Contents/SharedFrameworks/DVTKit.framework/Versions/A/Resources/DVTIbeamCursor.tiff`

You should now have an i-beam that is more easy to see on a dark or black background.

Before:

![Original Xcode Ibeam](https://raw.github.com/egold/better-xcode-ibeam-cursor/master/cursor-example-before.png "Original Xcode Ibeam") 

After:

![Improved Xcode Ibeam](https://raw.github.com/egold/better-xcode-ibeam-cursor/master/cursor-example-after.png "Replacement Xcode Ibeam")

### Background

I find it more enjoyable to code with the Midnight color theme in Xcode, but found myself always hunting for the cursor, especially on a large monitor. I found a pretty good [TIFF someone created](http://www.scigems.org/wordpress/?p=92), so I cleaned up a bit of the outline thickness and posted it here!
