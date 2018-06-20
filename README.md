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
- An easily extendable, responsive, light-weight front-end using API to display data
- IP banning to prevent low-diff share attacks
- Session managing for purging DDoS/flood initiated zombie workers
- Auto ban IPs that are flooding with invalid shares
- Socket flooding detection
- Detailed logging
- Support Nicehash, MiningRigRentails

Configuration
- Configuration is actually simple, just read it twice and think twice before changing defaults.
- One instance one coin
- Dev fee 1.5% of pool fee.

Proxies

- [Ether-Proxy](https://github.com/sammy007/ether-proxy) HTTP proxy with web interface
- [Stratum Proxy](https://github.com/Atrides/eth-proxy) for Ethereum

Dependencies:
- Ubuntu 16.04 LTS
- Nginx
- Redis-server
- Nodejs
- Coin daemon

Credits
- Modifed by AME Corp
- Based on open-ethereum-pool
