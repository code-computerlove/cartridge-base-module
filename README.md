# Base Module [![Build Status][travis-image]][travis-url]

> Starting point for a base [Cartridge](https://github.com/cartridge/cartridge) module

## Setup for a new module
[Create a new empty repository](https://github.com/new) for your expansion pack.

Clone this repository, giving the name of the new module - prefixed with the word `cartridge-`. This will be the name of the folder the source is cloned into.
```sh
git clone https://github.com/cartridge/base-module.git --depth=1 cartridge-my-module
```

Update the git origin to match your new repository eg:

```sh
cd cartridge-my-module
git remote set-url origin https://github.com/cartridge/cartridge-my-module.git
git remote -v
```

Set `NODE_ENV`to `development` - this is so none of the postinstall scripts run when installing dependencies.

```sh
# Linux / OS X
export NODE_ENV=development

# Windows
set NODE_ENV=production
```

Install dependencies
```sh
npm install
```

And do some coding!


## Development on the base module
Clone repository
```sh
git clone https://github.com/cartridge/base-module.git
```

Set `NODE_ENV`to `development` - this is so none of the postinstall scripts run when installing dependencies.

```sh
# Linux / OS X
export NODE_ENV=development

# Windows
set NODE_ENV=production
```

Install dependencies
```sh
cd base-module
npm install
```

And do some coding!



[travis-url]: https://travis-ci.org/cartridge/base-module
[travis-image]: https://travis-ci.org/cartridge/base-module.svg?branch=master
