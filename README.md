# import.meta is supported in globalSetup/globalTeardown
https://github.com/facebook/jest/issues/12580

# Usage

1. yarn install

2. yarn test

import.meta.url is printed in the console

```
✗ yarn test
yarn run v1.22.17
warning package.json: No license field
$ jest
Determining test suites to run...
import.meta.url is:  file:///Users/feng/dev/repro/setup.js
 PASS  __tests__/test.js
  ✓ hello (1 ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        0.234 s, estimated 1 s
Ran all test suites.
✨  Done in 1.27s.
```
