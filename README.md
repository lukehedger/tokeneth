<p align='center'>
  <img src='https://user-images.githubusercontent.com/1913316/35437267-8bf59230-0289-11e8-98a1-0b2935ddb89e.png' width='200'/>
</p>

## Comparison of Ethereum Token Standards

| Token standard | Status | Fungible | ERC20 Compatible |
| :------------- | :----- | :------- | :--------------- |
| ERC20  | Accepted | ✓ | - |
| ERC721 | Draft |  |  |
| ERC777 | Draft | ✓ | ✓ |
| ERC827 | Draft | ✓ | ✓ |
| ERC981 | Draft | - |  |
| MiniMe | n/a | ✓ | ✓ |

### ERC20

> The Original Token Standard

- [Standard specification](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md)
- Created on 2015-11-19

ERC20 is the original Ethereum token standard. It is designed to promote
interoperability between users, applications, wallets and exchanges by providing
a standard interface that can be implemented by token creators.

It was first proposed as part of
[a set of genesis standards](https://github.com/ethereum/wiki/wiki/Standardized_Contract_APIs/499c882f3ec123537fc2fccd57eaa29e6032fe4a#currency)
by Vitalik Buterin.

#### Implementations
- [ConsenSys](https://github.com/ConsenSys/Tokens/tree/master/contracts/eip20)
- [OpenZeppelin](https://github.com/OpenZeppelin/zeppelin-solidity/tree/master/contracts/token/ERC20)

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/1qsZ_6IMXa)
[![Run on Remix](static/remix.svg)](https://ethereum.github.io/browser-solidity/#version=soljson-v0.4.19+commit.c4cbbb05.js&optimize=false&gist=539b19641ef8d635b8b9815fff5e6e10)

### ERC721

> Non-fungible Token Standard

- [Standard specification](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md)
- Created on 2017-09-20

ERC721 is a standard for non-fungible tokens (tokens that cannot be exchanged).
It was proposed by [Dieter Shirley](https://github.com/dete) from Axiom Zen, the
company behind [CryptoKitties](https://www.cryptokitties.co/).

#### Implementations
- [OpenZeppelin](https://github.com/OpenZeppelin/zeppelin-solidity/tree/master/contracts/token/ERC721)

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/iJSyouNfF2)
[![Run on Remix](static/remix.svg)](https://ethereum.github.io/browser-solidity/#version=soljson-v0.4.19+commit.c4cbbb05.js&optimize=false&gist=43b97dc45f48012eca52081ac1923de4)

### ERC777

> A New Advanced Token Standard

- [Standard specification](https://github.com/ethereum/EIPs/issues/777)
- Created on 2017-11-19

ERC777, authored by Jordi Baylina, Jacques Dafflon and Thomas Shababi, aims to
optimise the ERC20 standard.

It introduces the concept of 'operators', which are addresses (verified
contracts) with rights to manage the tokens in circulation (eg. an exchange).

#### Implementations
- [jacquesd](https://github.com/jacquesd/eip777/blob/master/contracts/ReferenceToken.sol)

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/Ad5IWIm3sW)
[![Run on Remix](static/remix.svg)](https://ethereum.github.io/browser-solidity/#version=soljson-v0.4.19+commit.c4cbbb05.js&optimize=false&gist=f86c75146a8f28c7e8a67eeb9f147141)

### ERC827

> ERC20 Extension Token Standard

- [Standard specification](https://github.com/ethereum/EIPs/issues/827)
- Created on 2018-01-11

#### Implementations
- [OpenZeppelin](https://github.com/OpenZeppelin/zeppelin-solidity/tree/master/contracts/token/ERC827)

<!-- [![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/)
[![Run on Remix](static/remix.svg)](https://remix.ethereum.org/) -->

### ERC981

> Barter Token Standard

- [Standard specification](https://github.com/ethereum/EIPs/issues/981)
- Created on 2018-04-07

<!-- [![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/)
[![Run on Remix](static/remix.svg)](https://remix.ethereum.org/) -->

### MiniMe

> ERC20 compatible clonable token

- [Standard specification](https://github.com/Giveth/minime)
- Created on 2016-11-06
- Note: MiniMe is not on the Ethereum standards track

#### Implementations
- [Giveth](https://github.com/Giveth/minime/blob/master/contracts/MiniMeToken.sol)

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/bw0ojHMrGG)
[![Run on Remix](static/remix.svg)](https://ethereum.github.io/browser-solidity/#version=soljson-v0.4.19+commit.c4cbbb05.js&optimize=false&gist=fe7ee566b28bd525637481ddaa22a4c0)

## Credits

- Logo: [Blockchain Ethereum](https://thenounproject.com/tengwan/collection/cryptocurrency/?i=1506004#)
  by [Tengwan](https://thenounproject.com/tengwan/) from the Noun Project
