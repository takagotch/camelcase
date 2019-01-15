### camelcase
---
https://github.com/sindresorhus/camelcase

```
npm install camelcase
```

```js
const camelCase = require('camelcase');
camelCase('foo-bar');
camelCase('foo_bar');
camelCase('Foo-Bar');
camelCase('Foo-Bar', {pascalCase: true});
camelCase('--foo.bar', {pascalCase: false});
camelCase('foo bar');
camelCase(process.argv[3]);
camelCase(process.argv[3]);
camelCase(['foo', 'bar']);
camelCase(['__foo__', '--bar'], {pascalCase: true});

```

```
```


