# MoneroOcean/xmrig patched to run on systems with 256 MB or less. 

I got an error about not having enough memory for allocating RandomX dataset and MoneroOcean/xmrig would not run.

This fork removes RandomX based agorithms and was tested with systems with 128 MB of RAM.

Please report an issue if you need help. This software is free. Donations are welcome.
XMR: `432h9oos8JK2dVBBw8b2cJ14uLseLHetF1UsfTa8mmg2P2Uyg4osVN4Wz2anQ5TNhSi2iqhDhFLeX6fpVRUCint3S9pWusf`

# XMRig

[![GitHub license](https://img.shields.io/github/license/xmrig/xmrig.svg)](https://github.com/MoneroOcean/xmrig/blob/master/LICENSE)


XMRig is a high performance, open source, cross platform RandomX, KawPow, CryptoNight and AstroBWT unified CPU/GPU miner and [RandomX benchmark](https://xmrig.com/benchmark). Official binaries are available for Windows, Linux, macOS and FreeBSD.

## Mining backends
- **CPU** (x64/ARMv8)
- **OpenCL** for AMD GPUs.
- **CUDA** for NVIDIA GPUs via external [CUDA plugin](https://github.com/MoneroOcean/xmrig-cuda).

## Download
* **[Build from source](https://xmrig.com/docs/miner/build)**

## Usage
The preferred way to configure the miner is the [JSON config file](src/config.json) as it is more flexible and human friendly. The [command line interface](https://xmrig.com/docs/miner/command-line-options) does not cover all features, such as mining profiles for different algorithms. Important options can be changed during runtime without miner restart by editing the config file or executing API calls.

* **[Wizard](https://xmrig.com/wizard)** helps you create initial configuration for the miner.
* **[Workers](http://workers.xmrig.info)** helps manage your miners via HTTP API.

## Donations
* Default donation 1% (1 minute in 100 minutes) can be increased via option `donate-level` or disabled in source code.
* XMR: `48edfHu7V9Z84YzzMa6fUueoELZ9ZRXq9VetWzYGzKt52XU5xvqgzYnDK9URnRoJMk1j8nLwEVsaSWJ4fhdUyZijBGUicoD`

## Developers
* **[xmrig](https://github.com/xmrig)**
* **[sech1](https://github.com/SChernykh)**

## Contacts
* support@xmrig.com
* [reddit](https://www.reddit.com/user/XMRig/)
* [twitter](https://twitter.com/xmrig_dev)
