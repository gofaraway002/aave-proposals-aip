## Reserve changes

### Reserves added

#### LDO ([0x5A98FcBEA516Cf06857215779Fd812CA3beF1B32](https://etherscan.io/address/0x5A98FcBEA516Cf06857215779Fd812CA3beF1B32))

| description | value |
| --- | --- |
| supplyCap | 6,000,000 LDO |
| borrowCap | 3,000,000 LDO |
| aToken | [0x8A458A9dc9048e005d22849F470891b840296619](https://etherscan.io/address/0x8A458A9dc9048e005d22849F470891b840296619) |
| aTokenImpl | [0x7EfFD7b47Bfd17e52fB7559d3f924201b9DbfF3d](https://etherscan.io/address/0x7EfFD7b47Bfd17e52fB7559d3f924201b9DbfF3d) |
| borrowingEnabled | true |
| debtCeiling | 750,000,000 |
| decimals | 18 |
| eModeCategory | 0 |
| interestRateStrategy | ![[0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F](https://etherscan.io/address/0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F)](/.assets/1_0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F.svg) |
| isActive | true |
| isBorrowableInIsolation | false |
| isFlashloanable | true |
| isFrozen | false |
| isSiloed | false |
| liquidationBonus | 9 % |
| liquidationProtocolFee | 10 % |
| liquidationThreshold | 50 % |
| ltv | 40 % |
| oracle | [0xb01e6C9af83879B8e06a092f0DD94309c0D497E4](https://etherscan.io/address/0xb01e6C9af83879B8e06a092f0DD94309c0D497E4) |
| oracleLatestAnswer | 252,715,331 |
| reserveFactor | 20 % |
| stableBorrowRateEnabled | false |
| stableDebtToken | [0x0496372BE7e426D28E89DEBF01f19F014d5938bE](https://etherscan.io/address/0x0496372BE7e426D28E89DEBF01f19F014d5938bE) |
| stableDebtTokenImpl | [0x15C5620dfFaC7c7366EED66C20Ad222DDbB1eD57](https://etherscan.io/address/0x15C5620dfFaC7c7366EED66C20Ad222DDbB1eD57) |
| usageAsCollateralEnabled | true |
| variableDebtToken | [0x6Efc73E54E41b27d2134fF9f98F15550f30DF9B1](https://etherscan.io/address/0x6Efc73E54E41b27d2134fF9f98F15550f30DF9B1) |
| variableDebtTokenImpl | [0xaC725CB59D16C81061BDeA61041a8A5e73DA9EC6](https://etherscan.io/address/0xaC725CB59D16C81061BDeA61041a8A5e73DA9EC6) |
| optimalUsageRatio | 45 % |
| maxExcessUsageRatio | 55 % |
| baseVariableBorrowRate | 0 % |
| variableRateSlope1 | 7 % |
| variableRateSlope2 | 300 % |
| baseStableBorrowRate | 10 % |
| stableRateSlope1 | 13 % |
| stableRateSlope2 | 300 % |
| optimalStableToTotalDebtRatio | 20 % |
| maxExcessStableToTotalDebtRatio | 80 % |


## Raw diff

```json
{
  "reserves": {
    "0x5A98FcBEA516Cf06857215779Fd812CA3beF1B32": {
      "from": null,
      "to": {
        "aToken": "0x8A458A9dc9048e005d22849F470891b840296619",
        "aTokenImpl": "0x7EfFD7b47Bfd17e52fB7559d3f924201b9DbfF3d",
        "borrowCap": 3000000,
        "borrowingEnabled": true,
        "debtCeiling": 750000000,
        "decimals": 18,
        "eModeCategory": 0,
        "interestRateStrategy": "0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F",
        "isActive": true,
        "isBorrowableInIsolation": false,
        "isFlashloanable": true,
        "isFrozen": false,
        "isSiloed": false,
        "liquidationBonus": 10900,
        "liquidationProtocolFee": 1000,
        "liquidationThreshold": 5000,
        "ltv": 4000,
        "oracle": "0xb01e6C9af83879B8e06a092f0DD94309c0D497E4",
        "oracleLatestAnswer": 252715331,
        "reserveFactor": 2000,
        "stableBorrowRateEnabled": false,
        "stableDebtToken": "0x0496372BE7e426D28E89DEBF01f19F014d5938bE",
        "stableDebtTokenImpl": "0x15C5620dfFaC7c7366EED66C20Ad222DDbB1eD57",
        "supplyCap": 6000000,
        "symbol": "LDO",
        "underlying": "0x5A98FcBEA516Cf06857215779Fd812CA3beF1B32",
        "usageAsCollateralEnabled": true,
        "variableDebtToken": "0x6Efc73E54E41b27d2134fF9f98F15550f30DF9B1",
        "variableDebtTokenImpl": "0xaC725CB59D16C81061BDeA61041a8A5e73DA9EC6"
      }
    }
  },
  "strategies": {
    "0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F": {
      "from": null,
      "to": {
        "address": "0x27eFE5db315b71753b2a38ED3d5dd7E9362ba93F",
        "baseStableBorrowRate": "100000000000000000000000000",
        "baseVariableBorrowRate": 0,
        "maxExcessStableToTotalDebtRatio": "800000000000000000000000000",
        "maxExcessUsageRatio": "550000000000000000000000000",
        "optimalStableToTotalDebtRatio": "200000000000000000000000000",
        "optimalUsageRatio": "450000000000000000000000000",
        "stableRateSlope1": "130000000000000000000000000",
        "stableRateSlope2": "3000000000000000000000000000",
        "variableRateSlope1": "70000000000000000000000000",
        "variableRateSlope2": "3000000000000000000000000000"
      }
    }
  }
}
```