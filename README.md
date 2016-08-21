Jasmine with multiple config files demo
=======================================

Sometimes there are some tests we don't want it always run(e.g. slow, depends on special network), we can provide multiple config files and provide multiple commands to run them.

See the configuration in `scripts` part in file `package.json`, and all files under `spec`.

```
npm install -g jasmine
npm install
```

Run unit tests(without intergration tests)
------------------------------------------

```
npm test
```

Run all tests(unit + intergration)
----------------------------------

```
npm run test-all
```
