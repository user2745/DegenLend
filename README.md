DegenLend Protocol
=================

The DegenLend Protocol is an Ethereum smart contract for supplying or borrowing assets on SX Network. Through the cToken contracts, accounts on the blockchain *supply* capital (Ether or ERC-20 tokens) to receive cTokens or *borrow* assets from the protocol (holding other assets as collateral). The Compound cToken contracts track these balances and algorithmically set interest rates for borrowers.

Addresses:

  "Unitroller": "0xF1c01bCe4802935Df07a452dae85F88D9f197948",

  "Comptroller": "0x8D1230e6Ae4C1Bc573697D93103349C3FDefC944",

  "cWSX#CErc20Immutable": "0x78887e6863a1B696EF31E86604C72bF2828919FE",  // Depecrated

  "cUSDC#CErc20Immutable": "0xc53105aB43De1e9Fa81C5333eC7B3A2cC65004F4", // Depecrated

  "degenUSDC#CErc20Immutable": "0xC863E82CD46296F1F81C63cDEB3708505B5b0d97",

  "degenWSX#CErc20Immutable": "0x5cB7786A478eEc37Da5F6EA2e946cD860E784743",

  "priceOracle#SimplePriceOracle": "0x6ca684b4773aF95AB5AE8d0aB7bA078237536DDF",
  
  "sxInterestRateModel#JumpRateModelV2": "0xe5ADAbf78627cE464FaceE2970D0b71c0a525038"