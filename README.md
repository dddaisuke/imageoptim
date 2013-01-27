[![endorse](http://api.coderwall.com/dddaisuke/endorsecount.png)](http://coderwall.com/dddaisuke)

### > [Download binary here!](https://github.com/dddaisuke/download/raw/master/ImageOptim.tar.bz2) <

imageoptim
==========

![screenshot](https://raw.github.com/dddaisuke/imageoptim/master/screenshot/window.png)

This project fork from [Google Code](http://code.google.com/p/imageoptim/source/browse/trunk).

ImageOptim optimizes images — so they take up less disk space and load faster — by finding best compression parameters and by removing unnecessary comments and [color profiles](http://imageoptim.com/color-profiles.html). It handles PNG, JPEG and GIF animations.

ImageOptim seamlessly integrates various optimisation tools: [PNGOUT](http://www.advsys.net/ken/util/pngout.htm), [AdvPNG](http://advancemame.sourceforge.net/doc-advpng.html, [Pngcrush](http://pmt.sourceforge.net/pngcrush/), extended [OptiPNG](http://optipng.sourceforge.net/), [JpegOptim](http://www.kokkonen.net/tjko/projects.html), jpegrescan, jpegtran, and [Gifsicle](http://www.lcdf.org/gifsicle/).

It's excellent for publishing images on the web (easily shrinks images “Saved for Web” in Photoshop) and also useful for making Mac and iPhone/[iPad](http://imageoptim.com/ipad.html) applications smaller (see [Xcode warning](http://imageoptim.com/xcode.html)).

###How to use it
Simply drag'n'drop images or folders into the window! You can also drop files on ImageOptim's Dock icon or launch it from shell scripts with: open -a ImageOptim.app *.png.

If you install [this system service](http://imageoptim.com/ImageOptim-workflow.zip) you can run ImageOptim from Finder's context menu.

###More about PNG
My article “[PNG that works](http://calendar.perfplanet.com/2010/png-that-works/)” explains why ImageOptim removes gamma information and how to get even smaller PNG files with transparency that works in ancient versions of IE.

###Open Source
ImageOptim is free, open-source software under terms of the [GPL v2 or later](http://www.gnu.org/licenses/gpl-2.0.txt). Your contributions are welcome! Please grab the source code and [improve it](http://code.google.com/p/imageoptim/issues/list)! Feel free to contact me for assistance.

PNGOUT is bundled with permission of [Ardfry Imaging, LLC](http://www.ardfry.com/) and is not covered by the GPL.

###Frequent answers
Photoshop munges optimized PNGs!
ImageOptim converts images to [PNG8+alpha](http://pngmini.com/) format when that is possible without loss of quality. That's the most efficient way to store alpha channel.

Photoshop CS5 and older have a bug which causes such images to be loaded incorrectly. The bug is fixed in Photoshop CS6.

To undo optimisations and get the big fat, old-Photoshop-compatible PNG back, open PNG in Preview.app and save it again (“Export” in Lion).

Alternatively, switch to Fireworks or only optimize copies/final versions of images.

Will ImageOptim be in the App Store?
Unfortunately not. ImageOptim is given on terms that basically say “you can do whatever you want except taking away this freedom from others”. Apple [does not allow such permissive terms](http://www.fsf.org/blogs/licensing/more-about-the-app-store-gpl-enforcement). Apple requires all App Store users to accept legal restrictions in the iTunes EULA and puts DRM (copy protection) on all App Store apps.

You can get ImageOptim here, DRM-free. You can share it, modify it, use it in any country in the world, even sell it, as long as you don't forbid anybody else from doing the same.
