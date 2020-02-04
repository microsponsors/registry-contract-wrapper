### :warning: :x: DEPRECATED - DO NOT USE :x: :warning:

# Registry Whitelist Contract Wrapper
Generates a 0x Contract Wrapper for the Microsponsors Registry Whitelist contract.

More info:
https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen

## Install
```
npm install @0x/abi-gen -g
```

## Build
Assumes you are in the directory above this one, with this repo and the `registry-contract` repo directly below:
```
abi-gen --abis 'registry-contract/build/contracts/Whitelist.json' --out 'registry-contract-wrapper/build/' --partials 'registry-contract-wrapper/templates/partials/**/*.handlebars' --template 'registry-contract-wrapper/templates/contract.handlebars'
```

