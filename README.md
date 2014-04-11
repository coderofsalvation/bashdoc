bashdoc
=======

simple portable documentation generator for sourcecode using simply bash &amp; markdown.

Need a simple doc-chain without fancyness?

### Installation

    $ git clone https://github.com/coderofsalvation/bashdoc.git
    $ cli/build docs
    
    bashing down doc/menu.md
    bashing down doc/changes.md
    bashing down doc/dirstructure.md
    bashing down doc/functions.md
    bashing down doc/index.md

Now browse to /doc and voila!

### Screenshots

<img alt="screenshot of index view" src="https://raw.githubusercontent.com/coderofsalvation/bashdoc/master/examplecode/screenshot1.png"/>

<img alt="screenshot of index view" src="https://raw.githubusercontent.com/coderofsalvation/bashdoc/master/examplecode/screenshot2.png"/>

<img alt="screenshot of index view" src="https://raw.githubusercontent.com/coderofsalvation/bashdoc/master/examplecode/screenshot3.png"/>

<img alt="screenshot of index view" src="https://raw.githubusercontent.com/coderofsalvation/bashdoc/master/examplecode/screenshot4.png"/>

### Why

To easily drop-in a doc-chain into your projects which is:

* portable
* deadsimple
* easy to extend 
* for any language, just fiddle with the regexes for other languages
* use inline bash in markdown (templating language)
* easy to trigger from githooks (on deployment e.g.)

I know there are fancy other packages, but sometimes I need the bare minimum.

The example scans all php files from the root, but with a bit of bashfu you can tailor it to your own needs.

### Credits

* [bashdown](https://github.com/coderofsalvation/bashdown)
* [markdown.bash](https://github.com/chadbraunduin/markdown.bash)
* GNU coreutils
* GNU bash
