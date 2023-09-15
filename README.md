## About

In monorepositories, `npm publish` and `npm pack` take into account `.gitignore` and ignore `.npmignore`.
Tested with npm v9.6.7 and v10.1.0.

## Init

```bash
npm i
cd packages/pkg1
npm pack
```

Now you can see that the `packages/pkg1/pkg1-1.0.0.tgz` archive does not contain a `dist` directory.
