# ethash-universal-pool
Universal mining pool with support any ethash based coin.

Supported algoritms
- ethash (any coin based on this algorithm)

Features
- Support for HTTP and Stratum mining
- Detailed block,uncle stats with luck percentage and full reward
- Support workers id
- PPLNS block reward
- JSON API for get statistic
- Html static frontend, easy for modification

Configuration
- Configuration is actually simple, just read it twice and think twice before changing defaults.
- Dev fee 1.5% of pool fee.

Proxies

- [Ether-Proxy](https://github.com/sammy007/ether-proxy) HTTP proxy with web interface
- [Stratum Proxy](https://github.com/Atrides/eth-proxy) for Ethereum

Dependencies:
- Ubuntu 16.04 LTS
- Redis-server
- Nodejs
- Coin daemon

Credits
- modifed by AME Corp
- based on open-ethereum-pool
