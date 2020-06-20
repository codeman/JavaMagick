# JavaMagick project
JavaMagick is a Java interface to [ImageMagick](https://imagemagick.org/). It implements the most common image manipulation methods in a user friendly manner. It uses a JNI interface between Java and the [MagickWand API](https://imagemagick.org/script/magick-wand.php).

### Current Version
The project was created using ImageMagick version 7.0.10-19 (16 bit) but it should in theory work with previous and future versions (as long as the MagickWand API methods that it uses don't change).

### Binary distribution
I wrote the JNI dll in C using Visual Studio 10 on a Windows platform. I created a 32 bit and a 64 bit dll. I have also created binaries for Linux (Ubuntu) and a Mac (Catalina). You can find everything in the downloads section.
