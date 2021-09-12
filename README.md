# create-conjurate-template

[![conjurate-template][conjurate-badge]][conjurate-github] [![npm-url][npm-img]][npm-url]

## 1.0 Clone
```bash
git clone git@github.com:filipelinhares/create-conjurate-template.git your-template-name
cd your-template-name
npx trash .git
```

## 2.0 Configure your *./index.js* as you do in *templates* config inside *.conjurate.json*

```js
module.exports = {
  component: './src/components'
}
```

## 3.0 Create your template folders inside *./templates*

## License
[MIT](LICENSE.md) © Filipe Linhares

[conjurate-badge]: https://img.shields.io/static/v1?label=conjurate&message=template&color=green
[npm-img]: https://img.shields.io/npm/v/create-conjurate-template
[npm-url]: https://www.npmjs.com/package/create-conjurate-template
[conjurate-github]: https://github.com/filipelinhares/conjurate
