In order to submit richtext pieces to subs in InCopy, I had a handful of bad options available to me.

You can copy-paste each fact check hyperlink or footnote or comment box individually when submitting, which is an annoying copy-paste mess.

Or you could upload and submit a google doc along with a piece, which was also annoying.

This code runs in visual basic so a word document that looks like this:

    Here’s a [[hyperlink: piece]] of science writing with some1 fact checking notes in it
 
    1 I’m not sure about this; can we look into it?
 
Into something that looks like this:
 
    Here’s a piece<< google.com]] of science writing with some<< I’m not sure about this; can we look into it?]] fact checking notes in it

Read how to use VB here:

    https://www.process.st/how-to/open-microsoft-visual-basic-for-applications/

(I'd like to get a version of this working with javascript/ google docs. This is harder than it sounds as I don't think there's an easy way to manipulate comment boxes in the scripting behind google docs.)
