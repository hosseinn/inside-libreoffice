![](LibreOffice_Initial-Artwork-Logo_BlackWhiteLogo_2000px.png)
# Inside LibreOffice

LibreOffice has been around, in one form or another, since the late 80s/early 90s. In 1988 Marco Börries wrote StarWriter for the Zilog Z80, then the next year formed the German company Star Division. Star Division eventually fleshed out their offering and renamed it to Star Office. At some point Star Division also marketed and sold a cross platform C++ framework they called StarView. This, [they claimed](http://www.trumphurst.com/cpplibs/datapage.php?frompage=navbar&sqldata=Category%3D%27Mcom2%27), was part of a larger framework they called SOLAR (which you can still see in several of the classes e.g. SolarMutex). In fact, StarView was in essence what we now call the Visual Components Library (VCL) and contained much the same [class structure](http://collaboration.cmc.ec.gc.ca/science/rpn/biblio/ddj/Website/articles/DDJ/1993/9312/9312h/9312h.htm) we still use today.

Sun Microsystems later bought Star Division and opened the Star Office code to the general public under their license, the CDDL. Star Office was renamed to OpenOffice.org. Whilst code was contributed by third parties, it became increasingly bureaucratic and frustrating. Sun took a long time to merge patches, so Ximian resorted to a fork that incorporated many changes, which was increasingly used by Linux distributions. When Sun was bought by Oracle, relationships with many of the developers outside of Oracle became increasingly strained. This reached a head in late September 2010 when a group of developers forked OpenOffice.org to LibreOffice under the stewardship of a new organization, [The Document Foundation](https://www.documentfoundation.org).

As with any codebase as old as LibreOffice, it can be quite hard to get your head around it. In fact, LibreOffice is quite large - I ran [cloc](https://github.com/AlDanial/cloc) over a snapshot of a recent git snapshot and it showed that there is just over 4 million lines of code in approximately 9,600 files. So it can be rather daunting when attempting to contribute, even with help from the many supportive hackers in the LibreOffice community! This is an attempt to show the guts of LibreOffice, in a similar style to [linux-insides](https://0xax.gitbooks.io/linux-insides/content/)


## Work in progress
I've chosen GitBook as my publishing medium because it has an intuitive distribution medium (git! and the editor is super easy to use), integrates with GitHub where I have an account, and because it's almost Wiki like in that I can make my changes, if I need to I can revert them, or branch the content - whatever is necessary :-) I can also accept pull requests on GitHub, if anyone so desires. 

What this does mean, however, is that the book is a work in progress. Initially, it is half formed and I'm still trying to work out the structure. I'm also reading through the code as I go so this is as much an excercise for me to understand LibreOffice's codebase as it is to enlighten the reader!

Feel free to send me feedback:

<div style="align:center"><img src="https://raw.githubusercontent.com/chrissherlock/inside-libreoffice/master/TwitterLogo_%2355acee.png" style="width:25px;height;25px;vertical-align:top" /><span style=""><a href="https://twitter.com/tbsdy">@tbsdy</a></span>

<img src="https://raw.githubusercontent.com/chrissherlock/inside-libreoffice/master/50px-TK_email_icon.svg.png" style="width:25px;height;25px;vertical-align:top" /> <span style="">chris.sherlock79 at gmail.com</span>
</div>

