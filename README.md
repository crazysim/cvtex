# Template of a CV typeset in XeTeX

This is a fork of Taraborelli's CV template. As he himself says, I also was not happy with the templates over the internet. I was looking for some nice template with focus on typesetting and a nice output, not only a lot of information and details. I ended up in Tamborelli's website, with this nice template. Another source of inspiration is the [CV from Kieran Healy][kjh-vita].

[kjh-vita]: http://kjhealy.github.com/kjh-vita/

I forked this work on github and made the modifications for my needs, like the cinclusion of some comments, changes on the fonts used, and a little modification in the layout itself.

## Requirements

DISCLAIMER: This template is provided for free and without any guarantee that it will correctly compile on your system if you have a non-standard configuration.

I currently use TeX Live 2011 in Fedora 16, but I also was succesfull generating the pdf file on Windows using MiKTeX with the appropriate packages and fonts intalled. Some packages are not installed by default and is your responsibility to have them installed and working.

### Fonts

I tried to use Open Type fonts, since they are more flexible and scalable. But you'll probably need the XeTeX engine for full support of these fonts.

 - [Linux Libertine and Biolinum][libertine]
 - [Inconsolata][inconsolata]

[libertine]:	http://www.linuxlibertine.org/
[inconsolata]:	http://levien.com/type/myfonts/inconsolata.html

### Packages

Just search for these packages in CTAN for instructions or download. If you use Linux, probably these packages can be installed easily with the software manager.

 - xltxtra
 - xcolor
 - geometry
 - fontspec
 - marginnote
 - sectsty
 - ulem
 - hyperref

Below you'll find the original README from [Taraborelli's website][taraborelli]. Please note that this work is licensed under Creative Commons license.

[taraborelli]: http://github.com/dartar/cvtex

_Some typos were fixed_


Typesetting your academic cv in LaTeX
_____________________________________

Several dedicated packages are available to typeset a curriculum vitae or a resume in LATEX, such as europecv or ecv. For some reason I have always found these solutions not flexible enough to suit my needs. This is why I opted for a standard article class as a basis for my CV. Some TeX engines such as XeTeX allow you not only to benefit from the advanced typesetting features available in LATEX, but also to use in your documents expert fonts such as Hoefler Text or Adobe Garamond Pro and to edit TeX sources in your native (Western or non-Western) writing system. This is a custom template based on the Linux Libertine typeface that I designed to typeset an academic curriculum vitae in XeTeX.

LL cv template: http://github.com/dartar/cvtex
LL Libertine fonts: http://linuxlibertine.sourceforge.net/
Documentation: http://nitens.org/taraborelli/cvtex

Some rights reserved: http://creativecommons.org/licenses/by-sa/3.0/