# BSC全能分红代币合约

支持分红SHIB/ETH/USDT/DOGE等BSC所有代币。带销毁。



## 源码

https://github.com/dogekingtokendev/daqiang_2/blob/main/daqing_2.sol



## 编译/开源参数

```
COMPILER: v0.8.0+commit.e28d00a7.js
Enable optimization: 开启并使用默认值200
Other Settings: default evmVersion, MIT license
```

## 部署参数

CONTRACT 选择 `daqiang`，Value `100000000000000000` （0.1BNB）

```
name_:  daqiang Token (代币名称)
symbol_: daqiang (代币符号)
totalSupply_: 1000000000000000 (发行量1000万亿)
ADDRS:['要分红的代币合约','0x10ed43c718714eb63d5aa57b78b54704e256024e','营销钱包地址','0xad6906b9689ba0f32cd29ff4964e6a5b1897922c']
FEESETTINGS: [4,3,2,1] (分红、流动性、市场营销、销毁)
SELLFEESETTING: [4,3,2,1] (分红、流动性、市场营销、销毁)
MINIMUMTOKENBALANCEFORDIVIDENDS_: 10000000000 (100亿持有多少代币参与分红。数量后要加18个0)
```

## BSC常用代币合约地址

```
SHIB: 0x2859e4544C4bB03966803b044A93563Bd2D0DD4D
USDT: 0x55d398326f99059fF775485246999027B3197955
ETH: 0x2170Ed0880ac9A755fd29B2688956BD959F933F8
DOGE: 0xbA2aE424d960c26247Dd6c32edC70B295c744C43
BUSD: 0xe9e7CEA3DedcA5984780Bafc599bD69ADd087D56
CAKE: 0x0E09FaBB73Bd3Ade0a17ECC321fD13a19e81cE82
```

## Remix国内加速版

https://pancake.kiemtienonline360.com/

## TG电报群

https://t.me/daqiang_solidity
