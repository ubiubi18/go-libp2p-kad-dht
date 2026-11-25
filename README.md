# go-libp2p-kad-dht

### Reliability and consensus

Please treat the software in this repository as potentially unreliable. To the best of my knowledge, concerns relevant to Idena’s consensus security remain unresolved upstream.

As long as the chain continues to operate under its current rules, I will not change those rules on my own. I welcome working with upstream maintainers, node operators, and the wider Idena community to review any proposed consensus change and coordinate its adoption.

[![](https://img.shields.io/badge/made%20by-Protocol%20Labs-blue.svg?style=flat-square)](https://protocol.ai)
[![](https://img.shields.io/badge/project-libp2p-yellow.svg?style=flat-square)](https://libp2p.io)
[![GoDoc](https://godoc.org/github.com/libp2p/go-libp2p-kad-dht?status.svg)](https://godoc.org/github.com/libp2p/go-libp2p-kad-dht)
[![Discourse posts](https://img.shields.io/discourse/https/discuss.libp2p.io/posts.svg)](https://discuss.libp2p.io)

> A Go implementation of [libp2p Kademlia DHT specification](https://github.com/libp2p/specs/tree/master/kad-dht)

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Optimizations](#optimizations)
- [Contribute](#contribute)
- [Maintainers](#maintainers)
- [License](#license)

## Install

```sh
go get github.com/libp2p/go-libp2p-kad-dht
```

## Optimizations

Client-side optimizations are described in [optimizations.md](./optimizations.md)

## Usage

Go to <https://godoc.org/github.com/libp2p/go-libp2p-kad-dht>.

## Contribute

Contributions welcome. Please check out [the issues](https://github.com/libp2p/go-libp2p-kad-dht/issues).

Check out our [contributing document](https://github.com/libp2p/community/blob/master/CONTRIBUTE.md) for more information on how we work, and about contributing in general. Please be aware that all interactions related to libp2p are subject to the IPFS [Code of Conduct](https://github.com/ipfs/community/blob/master/code-of-conduct.md).

## Maintainers

- [@ipfs/kubo-maintainers](https://github.com/orgs/ipfs/teams/kubo-maintainers)
- [@libp2p/go-libp2p-maintainers](https://github.com/orgs/libp2p/teams/go-libp2p-maintainers)
- [@guillaumemichel](https://github.com/guillaumemichel)

See [CODEOWNERS](./CODEOWNERS).

## License

[MIT](LICENSE) © Protocol Labs Inc.
