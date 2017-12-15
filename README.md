# Dockerized IPM (Iota Peer Manager)

You can download it from original author akashgoswami as a NodeJS script

> https://github.com/akashgoswami/ipm

![IPM snapshot](https://github.com/akashgoswami/ipm/blob/master/public/img/ipm.jpg)


## Installation

To install 

```
docker pull carbonsphere/iota-ipm
```

## Environment Variable 

API_HOST

> Default value :  http://127.0.0.1:14265

```
Ex: http://yourhost:14265
```

## Run command

> If your full node is running at remote host.

```
docker run -d --name ipm -e API_HOST=http://remote-iri:port carbonsphere/iota-ipm
```

## Running with carbonsphere/iotaledger-iri

You can checkout my IOTA headless fullnode container at

> https://github.com/carbonsphere/iotaledger-iri

> If your full node container is running on the same host.

```
docker run -d --name ipm --net=host -v $(pwd)/iota-pm.conf:/root/iota-pm.conf -p 80:80 carbonsphere/iota-ipm
```


# Donation Address

If it works for you, please consider donating.

Every bit helps. Thanks!

- BTC: 395vsb41m46voFyhrgYMh6TauWKmNqJAtm
- ETH: 0xB205A4560BBc9840b80d36245333401E65d4f05e
- XMR: 46duR7umVuuCaAeVc27L1aXk4vJikNm81Xf2YbRkxDU3Nz69gTporVjbNkia6wkHc2BfYcH2xYPBY6m9t7AVQZU61dWmFro
- IOTA: FBIDRYFZKSYNGQICJTPPYAFUKYGCEVLCKHPKAXHLBGXJ9ENVRYYIYEMVQHIK9GNXFVILHYAKKPVBQSNTCBCKVPDM9Z

# Buy ETH or BTC with USD / Credit Card from CoinBase.com to get Free $10 BTC

- [CoinBase](https://www.coinbase.com/join/59fd2b2af2e50b01171a4ae6)

# Binance Exchange

Exchange your cryptos. Reliable and fast!

- [Binance](https://www.binance.com/?ref=11217913)
