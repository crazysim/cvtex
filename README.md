# Template of a CV typeset in XeTeX

This is a fork of [Taraborelli's CV template][taraborelli]. As he himself says, I also was not happy with the templates found over the internet. I was looking for some nice template with focus on typesetting and a nice output, not only a lot of information and details. I ended up in Tamborelli's website, with this nice template. Another source of inspiration is the [CV from Kieran Healy][kjh-vita].

Some rights reserved: http://creativecommons.org/licenses/by-sa/3.0/

[kjh-vita]: http://kjhealy.github.com/kjh-vita/

I forked this work on github and made the modifications for my needs, like the inclusion of some comments, changes on the fonts used, and a little modification on the layout.

## Requirements

**DISCLAIMER: This template is provided for free and without any guarantee that it will correctly compile on your system if you have a non-standard configuration or missing packages and fonts.**

I currently use TeX Live 2011 in Fedora 16, but I also succesfully generated the pdf file on Windows using MiKTeX with the appropriate packages and fonts installed. Note that some packages are not installed by default.

### Fonts

I tried to use Open Type fonts, since they are more flexible and scalable. You'll probably need the XeTeX engine for full support of these fonts.

 - [Linux Libertine and Biolinum][libertine]
 - [Inconsolata][inconsolata]

[libertine]:	http://www.linuxlibertine.org/
[inconsolata]:	http://levien.com/type/myfonts/inconsolata.html

### Packages

Just search for these packages in CTAN for instructions or download. If you use Linux, these packages can probably be installed easily with the default software manager. Look at the source file for more information on these packages.

 - xltxtra
 - xcolor
 - geometry
 - fontspec
 - marginnote
 - sectsty
 - ulem
 - hyperref
