# Below Branches Should NOT Be Used

## `testnet` branch
Based on `main` branch.

Specific tweaks: 
- `chainId()` tweak (fixed value) for different network: “testnet” `0x27`.
- `istanbul` compiler option change to `constantinpole`.
- `CREATE2` init code hash change of `UniswapV2Library.sol`.
- Test cases changes to include `chainId` as a parameter.

## `mainnet` branch
Based on `testnet` branch

Specific tweaks:
- `chainId()` tweak (fixed value) for different network: “mainnet” `0x4a`.
- `istanbul` compiler option change to `constantinpole`
- `CREATE2` init code hash change of `UniswapV2Library.sol`.
- Test cases changes same as on `testnet` branch.