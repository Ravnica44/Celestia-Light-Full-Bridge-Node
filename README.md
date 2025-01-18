```shell
screen -S Celestia
```

```shell
git clone https://github.com/celestiaorg/celestia-node.git
```

```shell
cd celestia-node
```

```shell
make build
```

```shell
make install
```

remplace `light` par `full` ou `bridge`

```shell
celestia light config-remove # à utiliser uniquement si tu veux enlever une ancienne config
```

https://docs.celestia.org/tutorials/celestia-node-key

```shell
make cel-key
```

```shell
./cel-key --help
```

```shell
./cel-key add My_Celestia_key_import --recover --keyring-backend file --node.type light --p2p.network celestia
```

```shell
celestia light init --keyring.backend file
```

```shell
celestia light start --keyring.backend file
```
