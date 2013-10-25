A template for development projects.

# Introduction

__For now just copy and modify those files!__

Later on, it will be a smarter tool able to generate a scaffolding, like templates for [brunch](http://brunch.io/) for instance.

Right now, you can use [volo](http://volojs.org/) to generate the scaffolding from this repository:

````bash
npm install -g volo
volo create https://github.com/ymeine/project-template
```

# File system layout

* [`README.md`](./README.md): this current file
* [`.gitignore`](./.gitignore): Git related file
* [`package.json`](./package.json): npm package definition
* `node_modules`: 3rd party libraries installed through npm

## Folders

* [`src`](./): sources of the project
* [`bin`](./bin): binary scripts for npm
* [`doc`](./doc): general documentation about the project or resources for other documentation files
* [`scripts`](./scripts): npm scripts
* [`test`](./test): folder containing tests source and resources

# Versioning

To ignore:

* `node_modules`: generated from [`package.json`](./package.json)

# Contribute

## Development

See [issues](https://github.com/ymeine/project-template/issues).
