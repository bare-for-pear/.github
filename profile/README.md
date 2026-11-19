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

## The seven organisations

SPLectrum's engineering is spread over seven GitHub organisations:

- **[splectrum](https://github.com/splectrum)**: where SPLectrum, the
  philosophy project, lives, and where its engineering is planned.
- **[bare-for-pear](https://github.com/bare-for-pear)** (this one): outside code
  changed to run on Bare. It rests until the platform needs it.
- **[pear-full-square](https://github.com/pear-full-square)**: the engines,
  all of the platform's code, one module a repository.
- **[HAICCing](https://github.com/haiccing)**: the packages made from those
  modules, and the `haicc` command: what you can run. Start here.
- **[myctral](https://github.com/myctral)**: mycelium's data
  repositories: state.
- **[myctrans](https://github.com/myctrans)**: data transformation:
  process.
- **[SPLectral](https://github.com/splectral)**: interaction, first of
  all the UI.

Part of the engineering of [SPLectrum](https://splectrum.world).
