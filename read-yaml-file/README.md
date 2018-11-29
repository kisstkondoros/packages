# read-yaml-file

> Read and parse a YAML file

## Installation

```sh
npm install --save read-yaml-file
```

## Usage

```js
const readYamlFile = require('read-yaml-file')

readYamlFile('foo.yml').then(data => {
  console.log(data)
  //=> {foo: true}
})
```

## API

### readYamlFile(filepath)

Returns a promise for the parsed YAML.

### readYamlFile.sync(filepath)

Returns the parsed YAML.

## Related

- [write-yaml-file](https://github.com/zkochan/packages/tree/master/write-yaml-file) - Stringify and write YAML to a file atomically

## License

[MIT](./LICENSE) © [Zoltan Kochan](https://www.kochan.io)