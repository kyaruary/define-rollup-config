# Why

Although Rollup has good support for TypeScript,

But rollup.config files usually export a plain object.

So the purpose of this package is to make it easier to write rollup.config files.

# Install

```bash
# npm
npm install define-rollup-config -D
# yarn
yarn add define-rollup-config -D
```

# Usage

```js
// rollup.config.js
import defineRollupConfig from "define-rollup-config";

export default defineRollupConfig({
    // there will be intelligent prompts
    input: "index.js",
});
```
