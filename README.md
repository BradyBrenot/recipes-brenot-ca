# recipes-brenot-ca
This is used to build [recipes.brenot.ca](https://recipes.brenot.ca).

The goal is to make a nice recipe database. Principles:
 - This is not a food blog, this is a practical site with minimal cruft
 - It works well on PC and mobile
 - It's blazingly fast
 - Requires minimal hosting resources and minimal 

To these ends, I've settled on a static generated site, using GitHub to host the recipe "database" itself. Recipes are markdown with simple yaml front matter which should be easy to manipulate either programmatically or by hand.

Hugo is the generator, with the [PaperMod](https://github.com/adityatelange/hugo-PaperMod/) theme as a starting point.

[NetlifyCMS](https://www.netlifycms.org/) is used as a CMS to allow for _more or less_ mom-friendly editing.

If this eventually matures to the point where I'd want to share it, I'll probably split all the theme stuff out into another repo to make to more publishable.
