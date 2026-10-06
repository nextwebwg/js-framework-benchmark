# HTML Next benchmark adapter

This entry exercises the live HTML Next loader and a declarative keyed `$each` region. The
checked-in `browser-loader.bundle.js` is generated from `nextwebwg/html-next` commit `cae92ab`
(alpha.30 plus the merged rendering-performance work); it is pinned so the benchmark runs exactly
this source revision. Rebuild it with the html-next repository's framework benchmark tooling.

The controller initializes once per instance and registers one component-owned delegated click listener for each connection. That is why the
benchmark metadata declares issue 801.
