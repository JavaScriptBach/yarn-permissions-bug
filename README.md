# yarn-permissions-bug

To Repro:

1. `yarn install`
2. Run `node_modules/.bin/mocha`. Binary will run.
3. `yarn up mocha@10.7.3`
4. Run `node_modules/.bin/mocha`. Binary is missing permissions.

