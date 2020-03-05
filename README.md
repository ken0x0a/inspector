# OpenRPC Inspector

OpenRPC Inspector is a simple tool to create, modify and execute JSON-RPC requests.

- Edit JSON-RPC request
- Test JSON-RPC request against a given URL

It can be used as a standalone tool or included in other projects.

![signatory_inspector_test](https://user-images.githubusercontent.com/364566/76027895-4917b180-5ee6-11ea-96b1-3aec4357120e.gif)

https://inspector.open-rpc.org

### Url configuration

You can configure the default request and url via url params:

`?url=http://localhost:8545`

`?request[jsonrpc]=2.0&request[method]=eth_chainId`

here is a full example:

https://inspector.open-rpc.org/?url=http://localhost:8002/multi-geth/mainnet/1.9.0&request[jsonrpc]=2.0&request[method]=eth_chainId&request[params][0]=foo

### Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.


# Resources
-  [open-rpc/client-js](https://github.com/open-rpc/client-js)
