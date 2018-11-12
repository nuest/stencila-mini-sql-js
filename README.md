# stencila-mini-sql-js

Demo for Stencila &amp; DAR on binder with [mini](https://www.r-project.org/), [SQL by SQLite](https://www.sqlite.org/lang.html) and [JavaScript by Node.js](https://nodejs.org/) code.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/binder-examples/stencila-mini-sql-js/master)

Learn more about [Stencila](https://stenci.la/) and it's integration with [Binder](https://mybinder.org/) in this blog post: [TODO](TODO)

`repo2docker` automatically picks up if there is a `*.jats.xml` file in a repository and then installs and configures the required software.

Since there is no build-in support for JavaScript projects yet, required libraries are installed in the file `postBuild`.
