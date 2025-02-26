# SRBMiner-MULTI: Cryptocurrency Miner for AMD, NVIDIA, INTEL, and CPU

SRBMiner-Multi is a powerful cryptocurrency miner supporting a variety of algorithms across multiple platforms, including **AMD**, **NVIDIA**, **Intel GPUs**, and **CPUs**. With SRBMiner, you can mine up to 4 different algorithms or coins simultaneously.

## Download

- [Official Website](https://www.srbminer.com/download.html)
- [GitHub Repository](https://github.com/doktor83/SRBMiner-Multi)

## Support

- [Discord Community](https://discord.gg/zXY23De)
- [Bitcointalk Discussion](https://bitcointalk.org/index.php?topic=5190081.0)


# Miner Software README

## Features:

- **Mine up to 4 algorithms simultaneously**: Run multiple algorithms at the same time to maximize mining performance.
- **Guided setup mode**: Simple and easy-to-follow setup process for quick configuration.
- **Run in the background without a window**: Minimize the miner to run silently in the background, saving screen space.
- **Hashrate watchdog**: Monitors your mining performance and automatically restarts the miner in case of a GPU error.
- **GPU temperature monitoring**: Keeps track of your GPU's temperature and automatically shuts down the miner if the temperature gets too high.
- **System shutdown on excessive GPU temperature**: If your GPU temperature exceeds safe limits, the system will shut down to prevent hardware damage.
- **Miner auto-restart on too many rejected shares**: Automatically restarts the miner if there are too many rejected shares, ensuring consistent mining performance.
- **API for miner statistics**: Provides an API to retrieve detailed statistics about your mining session.
- **Web-based GUI interface**: Offers a user-friendly web interface to monitor miner statistics in real time.
- **Multiple pools with failover support**: Configure multiple mining pools, and the miner will automatically switch to a backup pool in case the primary one fails.
- **Difficulty monitor**: Monitors the pool's difficulty, automatically reconnecting to the pool if the difficulty is too high.
- **Job timeout monitor**: Detects job timeouts and reconnects to the pool if no job has been received for an extended period.
- **Other useful features**: A variety of additional functionalities for optimized mining performance and stability.

---

Feel free to modify any part of this if needed!
---

## Supported Algorithms

| **C** | **A** | **N** | **I** | Algorithm        | Hashrate Efficiency |
|-------|-------|-------|-------|------------------|---------------------|
| ✓     | ✓     | -     | -     | argon2d_16000    | 0.85%               |
| ✓     | ✓     | -     | -     | argon2d_dynamic  | 0.85%               |
| ✓     | ✓     | -     | -     | argon2id_chukwa  | 0.85%               |
| ✓     | ✓     | -     | -     | argon2id_chukwa2 | 0.85%               |
| -     | ✓     | ✓     | ✓     | astrixhash       | 1.00%               |
| ✓     | ✓     | ✓     | ✓     | aurum            | 2.00%               |
| -     | ✓     | ✓     | ✓     | autolykos2       | 1.00%               |
| -     | ✓     | ✓     | ✓     | blake3_decred    | 1.00%               |
| -     | ✓     | ✓     | ✓     | blocx_autolykos2 | 1.00%               |
| ✓     | -     | -     | -     | cpupower         | 0.85%               |
| -     | ✓     | ✓     | ✓     | cryptixhash      | 1.00%               |
| ✓     | ✓     | -     | -     | cryptonight_ccx  | 0.85%               |
| ✓     | ✓     | ✓     | ✓     | cryptonight_gpu  | 0.85%               |
| ✓     | ✓     | -     | -     | cryptonight_turtle | 0.85%             |
| ✓     | ✓     | -     | -     | cryptonight_upx  | 0.85%               |
| ✓     | ✓     | -     | -     | cryptonight_xhv  | 0.85%               |
| ✓     | ✓     | -     | -     | curvehash        | 0.85%               |
| -     | ✓     | ✓     | ✓     | etchash          | 0.65%               |
| -     | ✓     | ✓     | ✓     | ethash           | 0.65%               |
| -     | ✓     | ✓     | ✓     | ethashb3         | 0.85%               |
| -     | ✓     | ✓     | ✓     | evrprogpow       | 0.85%               |
| -     | ✓     | ✓     | ✓     | firopow          | 0.85%               |
| -     | ✓     | ✓     | ✓     | fishhash         | 0.85%               |
| ✓     | -     | -     | -     | flex             | 2.00%               |
| -     | ✓     | ✓     | ✓     | fphash           | 1.00%               |
| ✓     | -     | -     | -     | ghostrider       | 0.85%               |
| -     | ✓     | ✓     | ✓     | heavyhash        | 0.85%               |
| -     | ✓     | ✓     | ✓     | hoohash          | 2.00%               |
| -     | ✓     | ✓     | ✓     | hoohashv1        | 2.00%               |
| -     | ✓     | ✓     | ✓     | karlsenhashv2    | 1.00%               |
| -     | ✓     | ✓     | ✓     | kawpow           | 0.85%               |
| ✓     | ✓     | ✓     | -     | lyra2v2_webchain | 0.85%               |
| -     | ✓     | ✓     | ✓     | meowpow          | 0.85%               |
| ✓     | -     | -     | -     | mike             | 0.85%               |
| ✓     | -     | -     | -     | minotaurx        | 0.85%               |
| -     | ✓     | ✓     | ✓     | nxlhash          | 1.00%               |
| ✓     | -     | -     | -     | panthera         | 0.85%               |
| -     | ✓     | ✓     | ✓     | phihash          | 0.85%               |
| -     | ✓     | ✓     | ✓     | progpow_epic     | 0.85%               |
| -     | ✓     | ✓     | ✓     | progpow_quai     | 0.85%               |
| -     | ✓     | ✓     | ✓     | progpow_sero     | 0.85%               |
| -     | ✓     | ✓     | ✓     | progpow_telestai | 0.85%               |
| -     | ✓     | ✓     | ✓     | progpow_veil     | 0.85%               |
| -     | ✓     | ✓     | ✓     | progpow_zano     | 0.85%               |
| ✓     | -     | -     | -     | randomarq        | 0.85%               |
| ✓     | -     | -     | -     | randomepic       | 0.85%               |
| ✓     | -     | -     | -     | randomscash      | 0.85%               |
| ✓     | -     | -     | -     | randomsfx        | 0.85%               |
| ✓     | -     | -     | -     | randomtuske      | 0.85%               |
| ✓     | -     | -     | -     | randomx          | 0.85%               |
| ✓     | -     | -     | -     | randomxeq        | 0.85%               |
| ✓     | -     | -     | -     | randomyada       | 0.85%               |
| -     | ✓     | ✓     | ✓     | sha256dt         | 0.85%               |
| -     | ✓     | ✓     | ✓     | verthash         | 1.00%               |
| ✓     | ✓     | ✓     | -     | verushash        | 0.85%               |
| -     | ✓     | ✓     | ✓     | walahash         | 1.00%               |
| -     | ✓     | ✓     | ✓     | xehash           | 1.00%               |
| ✓     | -     | -     | -     | xelishashv2      | 1.50%               |
| ✓     | -     | -     | -     | xelishashv2_pepew| 1.50%               |
| ✓     | ✓     | -     | -     | yescrypt         | 0.85%               |
| ✓     | ✓     | -     | -     | yescryptr16      | 0.85%               |
| ✓     | ✓     | -     | -     | yescryptr32      | 0.85%               |
| ✓     | ✓     | -     | -     | yescryptr8       | 0.85%               |
| ✓     | -     | -     | -     | yespower         | 0.85%               |
| ✓     | -     | -     | -     | yespower2b       | 0.85%               |
| ✓     | -     | -     | -     | yespowerdogemone | 0.85%               |
| ✓     | -     | -     | -     | yespoweric       | 0.85%               |
| ✓     | -     | -     | -     | yespowerltncg    | 0.85%               |
| ✓     | -     | -     | -     | yespowermgpc     | 0.85%               |
| ✓     | -     | -     | -     | yespowerr16      | 0.85%               |
| ✓     | -     | -     | -     | yespowersugar    | 0.85%               |
| ✓     | -     | -     | -     | yespowertide     | 0.85%               |
| ✓     | -     | -     | -     | yespowerurx      | 0.00%               |

---

## Dual Mineable Algorithms

Some algorithms can be mined simultaneously with others for increased efficiency:

- **fishhash** + **cryptixhash**
- **fishhash** + **walahash**
- **fishhash** + **blake3_decred**
- **fishhash** + **hoohash**

(See the full list for more combinations)

---

## Supported GPUs

### AMD GPUs:
- RX 7900/7800/7700/7600/7500
- RX 6500/6600/6650/6700/6750/6800/6900/6950
- RX 5300/5400/5500/5600/5700
- VEGA 56/64/FE/VII
- RX 470/480/570/580/590
- BC-250

### NVIDIA GPUs:
- Blackwell
- Hopper
- Ada Lovelace
- Ampere
- Turing
- Pascal
- For older models, try using the parameter `--disable-ptx-check`

### INTEL GPUs:
- Alchemist
- Battlemage
