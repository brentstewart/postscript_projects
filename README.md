This is a collection of postscript files that I've been playing with off-and-on.  They are not organized, nor do they build a larger piece.  I'm not terribly creative, so most of them print my name in a neat way.

Postscript is a stack based programming language - there's no variables, you just throw everything onto a single stack.  Commands then pop off the number of elements they need to complete.  Values are loaded onto the stack, then commands grab as many values as they need to complete.  I don't think spacing or line returns are important.

In college, I "discovered" postscript by printing a file for an Apple LaserWriter to an HP Laserjet.  Since the Laserjet didn't speak Postscript (they use PCL) it just dumped raw text onto a stack of paper.  I was fascinated because I could _kinda_ read it, so I researched it and bought three books and just started playing:
* Postscript Language: Tutorial and Cookbook by Adobe
* Graphic Design with Postscript by Gerard Kunkel
* Postscript by Example by Henry McGilton and Mary Campione

At first, I wrote text files and dumped them to the LaserWriter.
> copy myfile.ps > lpt1:

Later I started using early ghostscript to output to my dot matrix printer.  I recently rediscoverd some of my files from the 1980's and found that I could display them in Linux with modern Ghostscript.
> gs myfile.ps

This isn't really practical or useful, but I got into computers because I loved programming and getting a graphical result and this just makes me happy.  I hope you choose to clone my examples and play and it makes you happy too!
