`screen -S Celestia`

`git clone https://github.com/celestiaorg/celestia-node.git`

`cd celestia-node`

`make build`

`sudo make install`

(celestia light config-remove)

(https://docs.celestia.org/tutorials/celestia-node-key)

`make cel-key`

`./cel-key --help`

`./cel-key add My_Celestia_key_import --recover --keyring-backend file --node.type light --p2p.network celestia`

`celestia light init --keyring.backend file`

`celestia light start --keyring.backend file`
