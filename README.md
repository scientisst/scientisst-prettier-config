# Repository Archived

This repository has been archived and is no longer actively maintained.
Development of the project has been moved to
[scientisst/sense-web](https://github.com/scientisst/sense-web).

Please use the new repository for all future development and to report any
issues.

# @scientisst/prettier-config-next
This package contains recommended prettier settings for ScientISST or ScientISST-inspired applications that use the Next.js framework.

## Install

```bash
npm install --save-dev prettier @trivago/prettier-plugin-sort-imports @scientisst/prettier-config-next
```

```bash
yarn add -D prettier @trivago/prettier-plugin-sort-imports @scientisst/prettier-config-next
```

## prettier.config.cjs

```js
module.exports = {
  ...require("@scientisst/prettier-config-next")
}
```
