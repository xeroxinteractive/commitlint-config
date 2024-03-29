# ~~@xerox/commitlint-config~~ __Archived__: Moved to monorepo [xeroxinteractive/config](https://github.com/xeroxinteractive/config)

> commitlint shareable config for Xerox projects

[![circleci status][circleci-badge]][circleci-link]
[![npm package][npm-badge]][npm-link]
[![license MIT][license-badge]][license]
[![commit style angular][commit-style-badge]][commit-style-link]
[![semantic-release][semantic-release-badge]][semantic-release-link]
[![Dependabot Status][dependabot-badge]][dependabot-link]

## Usage
1. Install this config and @commitlint/cli and husky in `devDependency`:
```bash
yarn add @xerox/commitlint-config @commitlint/cli husky --dev
# or
npm install @xerox/commitlint-config @commitlint/cli husky --save-dev
```
2. Extend this configuration:
```jsonc
// package.json
{
  // ...
  "commitlint": {
    "extends": [
      "@xerox/commitlint-config"
    ]
  },
  // ...
}
```
3. Create a `.huskyrc.js` file in your project root with the following contents:
```javascript
module.exports = require('@xerox/commitlint-config/.huskyrc.json');

```

---

[LICENSE][license] | [CHANGELOG][changelog] | [ISSUES][issues]

[license]: ./LICENSE
[changelog]: ./CHANGELOG.md
[issues]: https://github.com/xeroxinteractive/commitlint-config/issues

[circleci-badge]: https://flat.badgen.net/circleci/github/xeroxinteractive/commitlint-config/master
[circleci-link]: https://circleci.com/gh/xeroxinteractive/commitlint-config/tree/master

[npm-badge]: https://flat.badgen.net/npm/v/@xerox/commitlint-config?color=cyan
[npm-link]: https://www.npmjs.com/package/@xerox/commitlint-config

[license-badge]: https://flat.badgen.net/npm/license/@xerox/commitlint-config

[commit-style-badge]: https://flat.badgen.net/badge/commit%20style/angular/purple
[commit-style-link]: https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines

[semantic-release-badge]: https://flat.badgen.net/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80/semantic%20release/e10079
[semantic-release-link]: https://github.com/semantic-release/semantic-release

[dependabot-badge]: https://flat.badgen.net/dependabot/xeroxinteractive/commitlint-config?icon=dependabot
[dependabot-link]: https://dependabot.com
