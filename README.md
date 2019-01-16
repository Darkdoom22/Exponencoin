### About
Forknote is innovative way to create Cryptonote (https://cryptonote.org) based cryptotokens. It gives the users the ability to create cryptotokens just by creating a simple configuration file.

### Dependencies
* GCC 4.7.3 or later     (http://gcc.gnu.org/)
* CMake 2.8.6 or later   (http://www.cmake.org/)
* Boost 1.55 or later    (http://www.boost.org/)
* MSVC 2013 (Windows only)

Step by step Windows instructions:
https://github.com/forknote/cryptonote-generator/blob/master/docs/windows-requirements-install.md

Ubuntu (tested on Ubuntu 14.04) / Mac dependencies install script:
https://github.com/forknote/cryptonote-generator/blob/master/configure.sh


### Usage
1. Download or compile the binaries
2. Create configuration file. The easiest way is to use the form on http://forknote.net
3. Start the daemon:
```
./forknoted --config-file PATH_TO_YOUR_CONFIG
```

Config File for Exponencoin
Create a Configs folder where your binaries are, and place this in a file named Expo.conf

seed-node=104.40.13.238:23616
seed-node=13.64.38.195:23616
EMISSION_SPEED_FACTOR=21
DIFFICULTY_TARGET=120
CRYPTONOTE_DISPLAY_DECIMAL_POINT=9
MONEY_SUPPLY=18446744073709551615
GENESIS_BLOCK_REWARD=0
DEFAULT_DUST_THRESHOLD=1000000
MINIMUM_FEE=1000000
CRYPTONOTE_MINED_MONEY_UNLOCK_WINDOW=10
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE=100000
MAX_TRANSACTION_SIZE_LIMIT=100000
CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX=86
DIFFICULTY_CUT_V1=60
DIFFICULTY_CUT_V2=60
DIFFICULTY_CUT=0
DIFFICULTY_LAG_V1=15
DIFFICULTY_LAG_V2=15
DIFFICULTY_LAG=0
DIFFICULTY_WINDOW_V1=720
DIFFICULTY_WINDOW_V2=720
DIFFICULTY_WINDOW=17
ZAWY_DIFFICULTY_BLOCK_INDEX=30
p2p-bind-port=23616
rpc-bind-port=23617
BYTECOIN_NETWORK=e60f651b-a45a-0cb3-529c-b11aadbc4e5f
CRYPTONOTE_NAME=Exponencoin
GENESIS_COINBASE_TX_HEX=010a01ff0001ffffffffffff0f029b2e4c0281c0b02e7c53291a94d1d0cbff8883f8024f5142ee494ffbbd08807121012a2c2646e69f96497bd6e53cd85bbb3fda823b478c0536ed9e6735517a717900
MAX_BLOCK_SIZE_INITIAL=100000
UPGRADE_HEIGHT_V2=1
UPGRADE_HEIGHT_V3=30
