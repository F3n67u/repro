# repro for https://github.com/facebook/jest/issues/12562

```bash
$ yarn
$ yarn test
yarn run v1.22.10
$ jest
 PASS  ./test.js
  ✓ .add(1, 1) (1 ms)
  ✓ .add(1, 2)
  ✓ .add(2, 1) (1 ms)

Test Suites: 1 passed, 1 total
Tests:       3 passed, 3 total
Snapshots:   0 total
Time:        0.228 s, estimated 1 s
Ran all test suites.
✨  Done in 1.32s.
```
