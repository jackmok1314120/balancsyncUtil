## ETH合约余额查询

- eth_call

```shell
curl https://mainnet.infura.io/v3/<PROJECT ID> -X POST --data '{"jsonrpc":"2.0","method":"eth_call","params":[{"to":"0xdaC17f958D2eE523A2206206994597c13D831ec7", "data":"0x70a08231000000000000000000000000E5E4f085c81342529b650c5f0E792980D673942B"}, "latest"],"id":1 }'
curl https://mainnet.infura.io/v3/a965b25231ec4c8ba9c95f49c5f6f27e -X POST --data '{"jsonrpc":"2.0","method":"eth_call","params":[{"to":"0xdaC17f958D2eE523A2206206994597c13D831ec7", "data":"0x70a08231000000000000000000000000E5E4f085c81342529b650c5f0E792980D673942B"}, "latest"],"id":1 }'
```# balancsyncUtil
