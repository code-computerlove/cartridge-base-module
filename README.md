# Base Module

> Starting point for a base [Cartridge](https://github.com/cartridge/cartridge) module

## Using for a new module
[Create a new empty repository](https://github.com/new) for your expansion pack.

Clone this repository, giving the name of the new module. This should be prefixed with the word `cartridge-`. This will be the name of the folder the source is cloned into.
```sh
git https://github.com/cartridge/base-module.git --depth=1 cartridge-my-module
```

Update the git origin to match your new repository eg:

```sh
cd cartridge-my-module
git remote set-url origin https://github.com/cartridge/cartridge-my-module.git
git remote -v
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

Install dependencies
```sh
cd base-module
npm install
```

And do some coding!
