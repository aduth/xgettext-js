v3.0.0 (2018-06-07)
===================
- Breaking: Support Node v10 or greater (#20).
- Updated: Lodash dependency from ^4.13.1 to ^4.17.15.
- Updated: @babel/parser dependency from ^7.0.0-beta.58 to ^7.5.5.
- Updated: estree-walker dependency from ^0.5.2 to ^0.6.1.
- Updated: devDependencies

v2.0.0 (2018-06-07)
===================
- Breaking: Support Node v6 or greater (#16).
- Updated: Switch parser from deprecated babylon to @babel/parser (#14).

v1.1.0 (2016-10-31)
===================
- New: `#getMatches()` now returns `column` in the match result (#13, props @anoek)
- General: The project now enforces a Node minimum version of >=4 . This could
be seen as a breaking change justifying a semver major version bump, but there
was no previous expectation on the Node version used aside from that inferred 
from the Travis configuration.

v1.0.0 (2016-08-01)
===================
- Breaking: Switch to `babylon` as a JavaScript parser.
  - There are [slight incompatibilities](https://www.npmjs.com/package/babylon#output) in the AST from the previous parser `acorn`.
  - Advantage of `babylon`: Ability to parse JSX and other advanced ES7 features (all with [enabled plugins](https://www.npmjs.com/package/babylon#plugins) in the `parserOptions`).

v0.3.1 (2016-06-17)
===================
- Updated: Lodash dependency from ^2.4.1 to ^4.13.1

v0.3.0 (2016-03-02)
===================
- Updated: Acorn dependency from 0.6.0 to 3.0.4
