# HTML Next benchmark adapter

This entry exercises the live HTML Next loader and a declarative keyed `$each` region. The
checked-in `browser-loader.bundle.js` is generated from `nextwebwg/html-next` commit `4eaf25b`;
it is pinned here until the package has a public release that the benchmark can install.

The root controller uses one component-owned delegated click listener. That is why the
benchmark metadata declares issue 801.
