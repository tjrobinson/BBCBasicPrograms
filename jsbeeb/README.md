# jsbeeb (vendored build)

This directory contains a production build of [jsbeeb](https://github.com/mattgodbolt/jsbeeb)
v1.13.1 by Matt Godbolt and contributors, used by the site at the repository root to run the
BBC BASIC programs in the browser.

jsbeeb is licensed under the GPL v3 — see [COPYING](COPYING). Source code:
https://github.com/mattgodbolt/jsbeeb

To update: clone jsbeeb, run `npm ci && npm run build`, then copy `dist/` here
(the `teletext/`, `discs/` and `tapes/` directories and `*.map` files are omitted
as they aren't needed and are large).
