**Easy and clean launch Dinastycoin using ForkNote, the most advanced CryptoNote software supporting numerous networks.

**Overview

Forknote uses configuration files to describe the properties of a Cryptonote blockchain. To get started you must download the latest version of Forknote.

Connecting the daemon to a blockchain

To connect to the daemon to existing blockchain, just start forknoted with the corresponding configuration file.

$ ./forknoted --config-file configs/imaginary_blockchain.conf
New blockchains are created by creating new configuration files. Configuration files are created with our blockchain creation form. You can find more about the available configuration options in our documentation.

**Examples

To connect the daemon to the Dinastycoin, start forknoted with its corresponding configuration file:

$ ./forknoted --config-file configs/dinastycoin.conf
To connect to the Dinastycoin blockchain, start forknoted with its corresponding configuration file:

$ ./forknoted --config-file configs/dinastycoin.conf
Starting simplewallet

Simplewallet uses the same configuration file as the daemon.

To start simplewallet:

$ ./simplewallet --config-file configs/imaginary_blockchain.conf
Examples

Starting simplewallet for the Dinastycoin blockchain:

$ ./simplewallet --config-file configs/dinastycoin.conf
Starting simplewallet for the Dinastycoin blockchain:

$ ./simplewallet --config-file configs/dinastycoin.conf

**CONFIG : 


BYTECOIN_NETWORK=092052ff-1110-5e2f-5522-02abf5a10255
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE_V1=10000
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE_V2=10000
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE=10000
CRYPTONOTE_DISPLAY_DECIMAL_POINT=8
CRYPTONOTE_NAME=dinastycoin
CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX=191
DIFFICULTY_TARGET=120
EMISSION_SPEED_FACTOR=18
GENESIS_BLOCK_REWARD=0
GENESIS_COINBASE_TX_HEX=010a01ff0001b8b886e69a16029b2e4c0281c0b02e7c53291a94d1d0cbff8883f8024f5142ee494ffbbd088071210152e2bfafe6e09c117af1794d2991751ba4d432ff85dd8a7b3027a97cc872670c
MINIMUM_FEE=100000
MONEY_SUPPLY=200044073709551615
P2P_STAT_TRUSTED_PUB_KEY=
MAX_TRANSACTION_SIZE_LIMIT=12500

CRYPTONOTE_COIN_VERSION=1

UPGRADE_HEIGHT_V2=270001
UPGRADE_HEIGHT_V3=270002

p2p-bind-port=37175
rpc-bind-port=37176

CHECKPOINT=284900:9df6576d02082092f0f5b2c2f00aafe895c1592888de92f48304a705cb9ed669

seed-node=108.61.188.93:7650
seed-node=104.238.188.213:7650
seed-node=87.13.117.53:37175 
seed-node=79.50.59.100:37175 
seed-node=94.177.178.107:37175

