1. Deploy a simple contract using Hardhat
```js
pnpm script ./scripts/deploy-1.ts
```
## Kết quả:

```js
$ pnpm script ./scripts/deploy-1.ts

> swisstronik-testnet2@1.0.0 script D:\Blockchain\swisstronik-testnet2
> hardhat run --network swisstronikTestnet "./scripts/deploy-1.ts"

Downloading compiler 0.8.20
Compiled 37 Solidity files successfully (evm target: paris).
Deployer: 0x859259FfA16A69188F109885D617e53a042b8494
Swisstronik contract deployed to: "0x3e2872b3EB2E5F72A1d09a3a542c1609f4425491" <- copy that for "the deployed contract address"
```
2. Mint 100 ERC-20 tokens

```js
pnpm script ./scripts/deploy-2.ts
```
## Kết quả:

```js
> swisstronik-testnet2@1.0.0 script D:\Blockchain\swisstronik-testnet2
> hardhat run --network swisstronikTestnet "./scripts/deploy-2.ts"

Deployer: 0x859259FfA16A69188F109885D617e53a042b8494
Deployed to: 0xD152B43155eDc8b5420790a41dED94366D882822 <- copy that for "the deployed contract address"
Mint Response: 0x4de6f742a22bd46c0201a5fea5039f860d860ce1eb8f67a14a74f5fb2e90f17b
Transfer Response: https://explorer-evm.testnet.swisstronik.com/tx/0xc864a8140897b0c843e07c3439ca40c7add36c81d28e02abce90288bae93d94f <- copy that for "the token transaction link"

```
3. Mint a ERC-721 token

``js
pnpm script ./scripts/deploy-3.ts
```

## Kết quả:

```js
> swisstronik-testnet2@1.0.0 script D:\Blockchain\swisstronik-testnet2
> hardhat run --network swisstronikTestnet "./scripts/deploy-3.ts"

Deployer: 0x859259FfA16A69188F109885D617e53a042b8494
Deployed to: 0xC2df62B022b21Eed041fF219fF586BF689C9fFAb <- copy that for "the deployed contract address"
Mint Response: https://explorer-evm.testnet.swisstronik.com/tx/0x2e2934c4ec4da33c6e4fc618d3bf8719c23bbf93db05c2dc816a2f37776eba21 <- copy that for URL
```
4. Mint a PERC-20 token

```js
pnpm script ./scripts/deploy-4.ts
```

## Kết quả task 4

```js
> swisstronik-testnet2@1.0.0 script D:\Blockchain\swisstronik-testnet2
> hardhat run --network swisstronikTestnet "./scripts/deploy-4.ts"

Deployer: 0x859259FfA16A69188F109885D617e53a042b8494
PERC20Sample was deployed to: 0xE56e256d12E83beF725D03eeCF5f27FCE14932F6 <- copy that for "the deployed contract address"
Transfer Response: https://explorer-evm.testnet.swisstronik.com/tx/0x9e36bf7f3be7582de0e58966c480806921415d33db6cd4d339ed27bd513eda2e <- copy that for URL
```
5. Deploy a Private NFT

```js
pnpm script ./scripts/deploy-5.ts
```
## Kết quả task 5

```js
> swisstronik-testnet2@1.0.0 script D:\Blockchain\swisstronik-testnet2
> hardhat run --network swisstronikTestnet "./scripts/deploy-5.ts"

Deployer: 0x859259FfA16A69188F109885D617e53a042b8494
Deployed to: 0x0C99f3Eea591CDF01E6CFda3A341B0E31b0D6800 <- copy that for "the deployed contract address"
Mint Response: https://explorer-evm.testnet.swisstronik.com/tx/0x910c42c7376e67db81443778416ae8017e2930d098f7b1f8836627d6498efded <- copy that for URL

```
6. Deploy Proxy

```js
pnpm script ./scripts/deploy-6.ts

```
## Kết quả task 6

```js
> swisstronik-testnet2@1.0.0 script D:\Blockchain\swisstronik-testnet2
> hardhat run --network swisstronikTestnet "./scripts/deploy-6.ts"

Deployer: 0x859259FfA16A69188F109885D617e53a042b8494
Contract address 1 deployed to: 0x59c443b8d8Ff01Fbb98831E71eFd90886A557a6E
ProxyAdmin address deployed to: 0x4F08Ee2686BDb36d1aFbD867aB1d6838BE6FCdB6
Proxy contract address: 0xA9Cd84Eea1D991a305c3360233123835349f15e5 <- copy that for "the deployed proxy contract address"
Contract address 2 deployed to: 0x265C7E00437A684d987177986866047633909c35
Response: https://explorer-evm.testnet.swisstronik.com/tx/0xe336addfc700595d72dc49987389521ca2e33f9399eab067aad097dfbabd7a74 <- copy that for "the link to the contract implementation replacement transaction"
```
