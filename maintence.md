To publish future maintenance, follow the next steps:

Install gulp as global package

```npm install -g gulp-cli```

Install local dependencies

```npm install```

Do code changes

Commit

Build pdfjs-dist package

```gulp dist-install```

Commit and push to remote git repo (except changes in package.json and package-lock.json)

Publish package `@azinformatica/pdfjs-dist` to npmjs

```npm publish build/dist/ --access public```
