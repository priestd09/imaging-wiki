# OSS Imaging Libraries

List of all open-source imaging libraries and their strengths and weaknesses.

We're looking for a cross-platform library suitable for on-demand, server-side image processing. It should have the following attributes:

* Free-threaded (No shared graphics thread)
* Multi-tenanting-enabled (Multiple instances per process)
* Fast image decoding, encoding, and scaling
* No memory leaks whatsoever
* Low RAM use
* Fast startup times
* Fast per-image processing times
* Secure
* Permissive license

| Library | License | Language | Promising? | Comments |
| --- | --- | --- | --- | ---
| [Skia](https://code.google.com/p/skia/) | New BSD | C++ | Yes |
| [Cairo](http://cairographics.org/) | LGPL 2.1 or MPL 1.1 | Yes |
| [Libvips](http://www.vips.ecs.soton.ac.uk/index.php?title=Libvips) | LGPL | C++ | yes
| [Pixman](http://pixman.org/) | MIT  | C | Yes 
| [CImg](http://cimg.sourceforge.net/) | CeCILL-C 
| [CxImage](http://www.xdp.it/cximage.htm) | zlib | C++
| [Leptonica](https://code.google.com/p/leptonica/) | Apache | Yes
| [OpenCV](http://opencv.org/) | BSD | C++ 
| [OpenCV-Ruby](https://github.com/ruby-opencv/ruby-opencv) | BSD | 
| [DevIL](http://openil.sourceforge.net/) | LGPL
| [LibGD](http://libgd.bitbucket.org/) | [Similar to MIT](https://bitbucket.org/libgd/gd-libgd/src/a0f58c6abf7b2f2c75ad13577157763e703410ff/COPYING?at=master) | C | yes | Very fast resizing; well-written, simple C code
| [PIL](http://www.pythonware.com/products/pil/) | [Similar to MIT/BSD](http://www.pythonware.com/products/pil/license.htm)
| [Magick++](http://www.imagemagick.org/Magick++/?ImageMagick=euqj79qcd73925ive9hf8sme42) as a part of [ImageMagick](http://www.imagemagick.org/script/index.php) | Apache
| [FreeImage](http://freeimage.sourceforge.net/) | GPL 2/3 OR [FIPL](http://freeimage.sourceforge.net/freeimage-license.txt) | C
| [SDL_Image](http://www.libsdl.org/projects/SDL_image/) | [zlib license](http://en.wikipedia.org/wiki/Zlib_License) 
| [Adobe Generic Image Library](http://www.boost.org/doc/libs/1_54_0/libs/gil/doc/index.html) | [Boost Software License](http://en.wikipedia.org/wiki/Boost_Software_License) | C++ | No | Entirely C++ templates; part of Boost; no actual imaging algorithms.
| [ExactImage](http://www.exactcode.com/site/open_source/exactimage/) | GPL 2
| [ImLib2](http://docs.enlightenment.org/api/imlib2/html/) | [Unclear](http://www.linuxfromscratch.org/blfs/view/svn/general/imlib2.html)
| [Marvin](http://marvinproject.sourceforge.net/en/index.html) | LGPL | Java
| [Animal](http://sourceforge.net/projects/animal/) | GPL | C 
| [Gandalf](http://gandalf-library.sourceforge.net/) | LGPL | C
| [IM](http://www.tecgraf.puc-rio.br/im/) | MIT | C++ 
| [PIL](https://github.com/python-imaging/Pillow) | BSD-style | C/Python
| [GMIC](http://gmic.sourceforge.net/) | [CeCILL2](http://www.cecill.info/licences/Licence_CeCILL_V2-en.html) | C


[List of imaging libraries with lisp bindings](http://www.cliki.net/graphics%20library)

http://stackoverflow.com/questions/11816571/light-weight-c-image-library


## Scaling-only resources

https://code.google.com/p/imageresampler/

## Imaging/graphics libraries that don't offer significant image scaling abilities

| Library | License | Platforms | Language | 
| --- | --- | --- | ---
| [ccv](http://libccv.org/) | MIT | C++ | 
| [GDAL](http://www.gdal.org/) | MIT | ? | 

## Exisitng comparisons

http://www.vips.ecs.soton.ac.uk/index.php?title=Speed_and_Memory_Use
http://randomfoo.net/2013/02/24/performance-comparison-of-image-libraries-revisited
http://leocharre.com/articles/faster-image-resizing-in-linux/




## Windows APIs

[Windows Imaging Components](http://en.wikipedia.org/wiki/Windows_Imaging_Component)
[StrechDIBits](http://msdn.microsoft.com/en-us/library/windows/desktop/dd145121(v=vs.85).aspx) 
[DrawDIB](http://msdn.microsoft.com/en-us/library/ms704990%28VS.85%29.aspx)

## Image resizing and transformation reading

* http://msn.iecs.fcu.edu.tw/report/data/ori_paper/2005-9-29/A%20fast%20edge-oriented%20algorithm%20for%20image%20interpolation.pdf
* http://gmic.sourceforge.net/gimp.shtml
* http://en.wikipedia.org/wiki/2xSaI#2.C3.97SaI
* http://www.compuphase.com/graphic/scale.htm
* 
