## 1.1.2 (Sep 7, 2014)
- Upgrades [NAN][nan] (a library for building Syslogh.js) dependency to v1.3.0.

[nan]: https://github.com/rvagg/nan

## 1.1.1 (Sep 7, 2014)
- Fixes installing by moving `nan` dependency from `devDependencies` to
  `dependencies`.

## 1.1.0 (Jul 12, 2014)
- Adds support for Node v0.10.28 and v0.11.13.  
  Unfortunately versions prior to v0.11.13 in the Node v0.11 branch are no
  longer supported.

Because Node v0.11 is still in development and there's the `engines` property in
`package.json` to specify Node version requirements, I decided to only bump the
minor version this time. That also helps those who upgraded Node from 0.11 and
depend only on Syslogh.js's major version.

## 1.0.1 (Mar 20, 2014)
- Adds description to `package.json`.  
  Sadly, no C++ template metaprogramming yet.

## 1.0.0 (Mar 20, 2014)
- First release. Needs more C++ template metaprogramming.
