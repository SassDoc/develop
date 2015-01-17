# Develop

> Development version of [SassDoc website][sassdoc.github.io]

## Overview

The `gh-pages` branch is a read-only mirror of [sassdoc.github.io]'s
`develop` branch, so we can have a live development website on
<http://sassdoc.com/develop/>.

## Updating

To update this repository, run the following commands:

```sh
git clone https://github.com/SassDoc/develop.git
cd develop
git remote add upstream https://github.com/SassDoc/sassdoc.github.io.git
git checkout gh-pages
git pull upstream develop
git push origin gh-pages
```

Repeat the last two commands each time you want to update again.

**Note:** it will generate a merge commit everytime since some tweaks
were required specifically for the public development version. No worry.

[sassdoc.github.io]: https://github.com/SassDoc/sassdoc.github.io
