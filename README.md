# Generate 0x Contract Wrapper for Registry Whitelist

Install
```
npm i @0x/abi-gen -g
```

Build
```
abi-gen --abis 'registry-contract/build/contracts/Whitelist.json' --out 'registry-contract-wrapper/build/' --partials 'registry-contract-wrapper/templates/partials/**/*.handlebars' --template 'registry-contract-wrapper/templates/contract.handlebars'
```

More info:
https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen
