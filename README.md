# Community Repository

Note this repository is not the repository where the devs are working on. It has 2 purposes:

1. Keeping all the solidity files together to ease the work of auditors.
2. Publishing the already accessible solidity code that got verified on the blockchain onto one place.

FEG and it's environment is closed source  thus we will only upload the solidity files that are already public to see on the blockchain!

**If something is missing  feel free to make a pull request.**


# Updates

## 24/08/2021
### Swap 2 swap
#### Highlights:

S2S allows you to move your fWrapped base-pair (fBNB, fETH, fUSDT, etc.) between SmartSwap Contracts (e.g., FEG/fBNB --fBNB moving→ TRY/fBNB)
* There is a 1.00% tax on all fWrapped tokens when moved into and out of SmartSwap.
  * External balance + 1.00% tax → Internal balance
  * Internal balance + 1.00% tax → External balance
* Swap-2-Swap fee: (separate from taxes moving into and out of SmartSwap)
  * 0.30% Systems fee for any fWrapped token, fee used for high-end server hosting, IT security firm payment, and further development of the FEG Token ecosystem
* Before & Utilizing S2S Fees Explained:
  * Before S2S (fWrap already inside SmartSwap): FEG/fBNB to TRY/fBNB
    * 1% fee moving fBNB from Internal FEG/fBNB balance to External Balance
    * 1% fee moving fBNB from External Balance to Internal TRY/fBNB Balance
      * Total 2% Fees 
  * Utilizing S2S: (fWrap already inside SmartSwap): FEG/fBNB to TRY/fBNB
    * 1% fee moving fBNB from External Balance into FEG/fBNB SmartSwap
    * 0.3% fee Swapping fBNB from Internal FEG/fBNB SmartSwap to Internal TRY/fBNB SmartSwap -> Purchase TRY inside of SmartSwap

### SmartDeFi

SmartDeFi
The World's First ALL-in-ONE SmartDeFi Ecosystem
Introducing the first-ever frictionless token with its trading and liquidity - all within a single ecosystem! There is no longer a need to pick where to host trading. On-Token-hosted trading can now be performed globally.

#### Elimination of Rugpulls

This code eliminates the ability to rug since its trading system is not hosted via a third party. The token contract now owns its liquidity, making it impossible to rug! Eliminating liquidity provider (LP) tokens while fully empowering safe liquidity.


#### Routing Features

All SmartDeFi and FEGex pairs can send and receive SmartFunds to and from each other. This allows Peer-to-Peer (P2P) and Swap-to-Swap (S2S) transfers of SmartFunds anywhere within FEGex and SmartDeFi networks.


#### Peer-2-Peer


#### Swap-2-Swap



#### SmartSwap-Enabled

SmartSwap technology has been added inside the token hosted swap protocol offering record gas savings. Swing or day trading can be done inside the On-Token Swap protocol, providing countless savings while frequently trading.

SmartSwap


#### Directly Rewards FEG Staking Pools

The same 0.12% sell fee built within FEGex that rewards FEG staking pools is built inside ALL SmartDeFi tokens, which supports the increase in rewards within the FEG Token ecosystem.


#### fWrap-Enabled

All SmartDeFi Tokens are built to run seamlessly with fWrap-based assets. This means that all trading performed universally on the same base assets provides positive price pressure on ROX and every token launched on SmartDeFi. Since the base fWrap collects rewards, the rewards originate from the token’s liquidity, giving a perpetual price increase.


#### SmartDeFi Tokens are 100% ASSET-BACKED!

Every SmartDeFi token is fully backed by its base asset, guaranteeing the tokens’ baseline value is secured from suffering loss. Base assets are what assets the tokens are traded against (for example, fBNB/fETH). A set percentage of every BUY/SELL is given to the asset-backing pool which is secured inside the SmartDeFi tokens’ smart contract. This results in a perpetual increase of the SmartDeFi tokens’ baseline value, resulting in the formation of a baseline value that can never decrease (Seriously!)

The asset-backing can be recovered instantly by burning SmartDeFi tokens for their share of asset-backing. When SmartDeFi tokens burn for their backed asset, it creates a “black hole” that burns more and more tokens automatically and effortlessly over time. Burnt tokens forward their backing to remaining tokens, increasing the backing per token faster. This guarantees that every SmartDeFi token will always have value, regardless of the market price!

Since all SmartDeFi tokens are based on fWrap technology, their market price even rises when there is zero (0) volume. SmartDeFi "DeFi"es the laws of physics - when any tokens are sold the baseline value goes up instead of down. SmartDeFi also helps to eliminate pump-and-dump schemes. With the baseline value being transparent, buyers know what the risk ratios are even before trading

Anyone can deploy their own SmartDeFi token with FEGdeployer!


#### Example

(Figures are based on the USD value of BNB not changing and a supply of 1,000 ROX. If BNB increases over time, then results will yield more.)

1,000 ROX (Total Supply)
5% of volume allocated for backing
Every $1m volume adds $50,000 to asset-backing

RESULTS based on example:
After $1m volume:
$50,000 / 1,000 = $50 per token total backing

After $100m volume:
$5,000,000 / 1,000 = $5,000 per token total backing

After $1b volume:
$50,000,000 / 1,000 = $50,000 per token total backing

If volume is $10m per day for 1 year:
$182,500,000 / 1,000 = $182,500 per token total backing

If volume is $1b per day for 1 year:
$18,250,000,000 / 1,000 = $18,250,000 per token total backing

If volume is $1b per day for 10 years:
$180,250,000,000 / 1,000 = $180,250,000 per token total backing



