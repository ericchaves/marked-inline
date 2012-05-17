## README

Sample project to ilustrate "base-reference" path problem between Marked-github/Github.

Those links will work on Marked, but produce a 404 in Github due to the fact that Github references tree/master

Linking to [pageone](docs/pageone.md) 
Linking to [pagetwo](docs/pagetwo.md)

Those links will work on Github, but won't be followed in Marked

Linking to [pageone](marked-inline/tree/master/docs/pageone.md) 
Linking to [pagetwo](marked-inline/tree/master/docs/pagetwo.md)

Also, check the pages inside the docs/ folder. Samething applies using only relative-paths (no reference to the marked-inline root folder).