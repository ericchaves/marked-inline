## README

Sample project to ilustrate "base-reference" path problem between Marked-github/Github.

1. Linking to [pageone](pageone.md) 
1. Linking to [pagetwo](pagetwo.md)
1. Linking to [docs/pageone](docs/pageone.md) 
1. Linking to [docs/pagetwo](docs/pagetwo.md)


| Link | Marked | Github |
|:----:|:------:|:------:|
|  1   |   OK   |   NO   |
|  2   |   OK   |   NO   |
|  3   |   NO   |   OK   |
|  4   |   NO   |   OK   |

Partial navigation result


1. - https://github.com/ericchaves/marked-inline
1. clicked in "docs" goes to https://github.com/ericchaves/marked-inline/tree/master/docs
1. clicked in README link 1 goes to https://github.com/ericchaves/marked-inline
1. clicked in "docs" goes to https://github.com/ericchaves/marked-inline/tree/master/docs
1. clicked in README link 2 goes to https://github.com/ericchaves/marked-inline
1. clicked in "docs" goes to https://github.com/ericchaves/marked-inline/tree/master/docs
1. clicked in README link 3 goes to https://github.com/ericchaves/marked-inline/blob/master/docs/pageone.md
1. clicked in PAGEONE link 1 goes to https://github.com/ericchaves/marked-inline/blob/master/docs/README.md
1. clicked in README link 1 goes to https://github.com/ericchaves/marked-inline/blob/master/docs/pageone.md

It seems that it all resume to when Github links to "tree/master" and when it links to "blob/master".