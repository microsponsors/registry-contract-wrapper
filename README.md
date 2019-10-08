# Registry Whitelist Contract Wrapper
Generates a 0x Contract Wrapper for the Microsponsors Registry Whitelist contract.

Install
```
npm install @0x/abi-gen -g
```

Build
```
abi-gen --abis 'registry-contract/build/contracts/Whitelist.json' --out 'registry-contract-wrapper/build/' --partials 'registry-contract-wrapper/templates/partials/**/*.handlebars' --template 'registry-contract-wrapper/templates/contract.handlebars'
```

More info:
https://github.com/0xProject/0x-monorepo/tree/development/packages/abi-gen
