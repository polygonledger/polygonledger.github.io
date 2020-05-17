## Polygonledger

Polygon is a new blockchain. It uses a delegated proof-of-asset algorithm and is written in golang.

Polygon uses accounts to store state. The scripting occurs through transaction multiplexing, which means there are several modes of transactions. Transactions are structures encoded in the [extensible data notation](https://github.com/edn-format/edn). They are generic code of a certain form which can be understood by the parser.

Polygon allows for arbitrary message encoding and signing, using new primitives for communication between nodes employing [golang channels](https://tour.golang.org/concurrency/2). This makes it more general as a transaction and communcation platform.

## Documentation

[investor intro deck](https://docs.google.com/presentation/d/15sgQPFWZCz6p9X04N3gRBgz71tEi9vG4V-5MrbrT4ag/edit?usp=sharing)

[whitepaper draft](https://github.com/polygonledger/docs/blob/master/whitepaper.md)

### Community

[Discord](https://discord.gg/wf5Qu72)

[Telegram](https://t.me/joinchat/Dzif7R1cHnAzulflui53fA)

### Code

see [node](https://github.com/polygonledger/node).

