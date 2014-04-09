bashdoc
=======

simple portable documentation generator from sourcecode comments using simply bash &amp; markdown

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


### Why

To easily drop-in a doc-chain into your projects which is:

* portable
* deadsimple
* easy to extend 
* use inline bash in markdown (templating language)
* easy to trigger from githooks (on deployment e.g.)

I know there are fancy other packages, but sometimes I need the bare minimum.
