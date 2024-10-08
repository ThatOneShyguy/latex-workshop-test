# Installing a LaTeX distribution

If you prefer to have everything needed for LaTeX installed locally rather than use an online editor like Overleaf, you have two options:
1. Install the full LaTeX distribution, which takes a few gigs of storage. 
2. Install only the minimum packages you need. 

Option 2 will give you a minimal setup without taking up much storage, but the downside is you'll need to use the package manager to install every package needed for your document to compile. You can do this by looking at the output/logs when a document fails to compile, and installing the package mentioned there. 

If you aren't low on storage and just want the easiest setup, go with the full distribution. 

Be sure to occasionally update through your package manager to get the latest packages and bugfixes, at least every month or so.

## Windows

[MiKTeX](https://miktex.org/)

[TeX Live](https://www.tug.org/texlive/)

## Mac

[MacTeX](https://www.tug.org/mactex/)

## Linux

Use your distribution's package manager to install texlive packages, or use the installer from the [Tex Live website](https://www.tug.org/texlive/) to get started, and use the command `tlmgr` to install and update LaTeX packages.


## [Next - Creating a Document](creating-a-document.md)
