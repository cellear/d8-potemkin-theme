*D8 Potemkin Theme*

Fake it till you make it!  Literally.  This theme allows you to very quickly create a professional-looking theme, strictly for demo purposes

The phrase "Potemkin Village" comes from this story:

https://en.wikipedia.org/wiki/Potemkin_village

"While modern historians claim accounts of this portable village are exaggerated, the original story was that Potemkin erected 
phony portable settlements along the banks of the Dnieper River in order to impress the Russian Empress; the structures would 
be disassembled after she passed, and re-assembled farther along her route to be viewed again as if another example."

Basically, it was the first rigged demo!

The idea of the Potemkin theme is to make it easy to demo some Drupal capabilities to a client who is not yet using Drupal.  
Rather than go through the arduous process of constructing a proper theme, just go to a typical content page on the
client's existing (non-Drupal, most likely) site and capture a local version.  ("Save Page As" in Chrome works well for
this, though you could use wget or curl if you prefer.)  Make sure all the CSS and JavaScript works locally (which typically
works out of the box, though some very JavaScript-heavy sites have trouble) then graft the relevant bits into the supplied
templates (html, page, and node).  Place the output of the page.content variable wherever you want to demo the Drupal feature
(like a view or node content) and BOOM! -- it looks just like an actual Drupal site.  Except instead of taking weeks, you
put it together in a few hours.

Don't let the client touch it, though, unless they fully understand what it is.  None of the links will do the right thing, 
except for the ones you've created as part of your demo.

In my experience clients love this.  They're used to the design of their own site, so you get to concentrate on the unique
value that you are adding with your Drupal skilz.  It's better than Lorem Ipsom, since it's much less stressful for the 
client, who generally don't speak Latin and feel more comfortable looking at their existing familiar content.


