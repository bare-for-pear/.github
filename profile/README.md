# bare-for-pear

Outside code brought to the [Bare](https://github.com/holepunchto/bare)
runtime. Bare is Holepunch's small JavaScript runtime, the ground the HAICC
platform stands on, while much of the JavaScript world assumes Node.js. The
repositories here are barified: changed to run on Bare. Some are whole clones
(avsc for Avro, isomorphic-git), some extracts (avsc-rpc and rpc-server, from
avsc's RPC layer), and git wraps the official git command line for Bare.

They come from the first rounds of work on Bare and rest while the platform
does not need them; Avro, which avsc carries, is on the way for SPLectrum's
language layer. One of them has grown into our own: the git engine p2p-git
began here, as a clone of isomorphic-git, and now lives in
[pear-full-square](https://github.com/pear-full-square).

Part of the engineering of [SPLectrum](https://splectrum.world).
