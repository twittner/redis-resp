# REdis Serialisation Protocol (RESP)

This library provides [RESP][1] encoding/decoding functionality and
defines most of the available Redis [commands][2] as an GADT which
allows for different interpreter implementations such as [redis-io][3].

[1]: http://redis.io/topics/protocol
[2]: http://redis.io/commands
[3]: https://github.com/twittner/redis-io
