## Polygonledger

Polygon is a new blockchain. It uses a delegated proof-of-asset algorithm and is written in golang.

Polygon uses accounts to store state. The scripting occurs through transaction multiplexing, which means there are several modes of transactions. Transactions are structures encoded in the [extensible data notation](https://github.com/edn-format/edn).
They are generic code of a certain form which can be understood by the parser.

Polygon allows for arbitrary message encoding and signing, using new primitives for communication between
nodes. This makes it more general as a transaction and communcation platform

### Code

see [node](https://github.com/polygonledger/node).

