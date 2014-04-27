fonts-rekha
===========

Rekha Gujarati font. This font was developed as part of [Utkarsh Gujarati Operating System](http://www.utkarsh.org).

Contributors:
* Ankur Patel
* Ankit Patel
* Atit Patel
* Bhavin Shah
* Kartik Mistry
* Khushbu Shah
* Sweta Kothari

Technical Details
=================
* Glyphs count : 407

How to install fonts on Linux?
===================================
#### Linux (using package)

In Debian and derivative distributions like Ubuntu, simply use:

```
sudo apt-get install fonts-rekha
```

#### Linux (manual installation)

Place font file to ```/usr/share/fonts``` folder and run,

```
fc-cache -v
```
in terminal.


Creating Web Fonts
==================
[Sfntly] (https://code.google.com/p/sfntly/) is required for creating web fonts. Once installed, following commands can be used.

#### Creating .woff
```
java -jar /path/to/sfnttool.jar -w Rekha.ttf Rekha.woff
```

#### Creating .eot
```
java -jar /path/to/sfnttool.jar -e -x Rekha.ttf Rekha.eot
```

LICENSE
=======
GPL-2+

Copyright: 2004-2007, MagNet Technologies Pvt. Ltd. Mumbai, India.

The Rekha font is free software, licensed under the terms of the GNU General
Public License.

See [LICENSE](https://github.com/kartikm/fonts-rekha/blob/master/LICENSE) file for full license text.
