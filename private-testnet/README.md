# Private Testnet

Essential parts : docker, docker-compose

If Run below command then setup private network plasma-evm base on private Pow chain

```bash
private-testnet $ docker-compose up
```

Expecting 3 containers : rootchain(private PoW chain), plasma-evm(Operator, miner), plasma-evm(bootnode, kind-proxy)

you can turn off with "ctrl + c" at terminal.