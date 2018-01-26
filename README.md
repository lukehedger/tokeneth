<p align='center'>
  <img src='https://user-images.githubusercontent.com/1913316/35437267-8bf59230-0289-11e8-98a1-0b2935ddb89e.png' width='200'/>
</p>

> This is a WIP - contributions welcome!

## Comparison of Ethereum Token Standards

| Token standard | Fungible | ERC20 Compatible |
| :------------- | :------- | :--------------- |
| ERC20 | ✓ | - |
| ERC721 |  |  |
| ERC777 | ✓ | ✓ |
| ERC827 | ✓ | ✓ |
| MiniMe | ✓ | ✓ |

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

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/)
[![Run on Remix](static/remix.svg)](https://remix.ethereum.org/)

### ERC721

> Non-fungible Token Standard

- [Standard specification](https://github.com/ethereum/EIPs/issues/721)
- Created on 2017-09-20

ERC721 is a standard for non-fungible tokens (tokens that cannot be exchanged).
It was proposed by [Dieter Shirley](https://github.com/dete) from Axiom Zen, the
company behind [CryptoKitties](https://www.cryptokitties.co/).

#### Implementations
- [OpenZeppelin](https://github.com/OpenZeppelin/zeppelin-solidity/tree/master/contracts/token/ERC721)

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/)
[![Run on Remix](static/remix.svg)](https://remix.ethereum.org/)

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

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/)
[![Run on Remix](static/remix.svg)](https://remix.ethereum.org/)

### ERC827

> ERC20 Extension Token Standard

- [Standard specification](https://github.com/ethereum/EIPs/issues/827)
- Created on 2018-01-11

#### Implementations
- [OpenZeppelin](https://github.com/OpenZeppelin/zeppelin-solidity/tree/master/contracts/token/ERC827)

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/)
[![Run on Remix](static/remix.svg)](https://remix.ethereum.org/)

### MiniMe

> ERC20 compatible clonable token

- [Standard specification](https://github.com/Giveth/minime)
- Created on 2016-11-06

#### Implementations
- [Giveth](https://github.com/Giveth/minime/blob/master/contracts/MiniMeToken.sol)

[![Run on EthFiddle](static/ethfiddle.svg)](https://ethfiddle.com/)
[![Run on Remix](static/remix.svg)](https://remix.ethereum.org/)

## Credits

- Logo: [Blockchain Ethereum](https://thenounproject.com/tengwan/collection/cryptocurrency/?i=1506004#)
  by [Tengwan](https://thenounproject.com/tengwan/) from the Noun Project
