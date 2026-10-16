---
description: Method-level reference for `w3.seismic`
icon: list
---

# Methods

## Public methods

* [get\_tee\_public\_key](get-tee-public-key.md)
* [get\_deposit\_root](get-deposit-root.md)
* [get\_deposit\_count](get-deposit-count.md)

Available on both public and wallet clients.

## Wallet methods

* [send\_shielded\_transaction](send-shielded-transaction.md)
* [debug\_send\_shielded\_transaction](debug-send-shielded-transaction.md)
* [signed\_call](signed-call.md)
* [deposit](deposit.md)

Available only on wallet clients.

## Utility

* [encode\_shielded\_calldata](https://github.com/SeismicSystems/seismic/blob/main/docs/gitbook/clients/python/namespaces/methods/encode-shielded-calldata.md)

Used internally by contract/namespace methods, and available directly when needed.

All methods have both sync and async variants. Async variants use `await`.
