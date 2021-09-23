# Community Repository

Note this repository is not the repository where the devs are working on. It has 2 purposes:

1. Keeping all the solidity files together to ease the work of auditors.
2. Publishing the already accessible solidity code that got verified on the blockchain onto one place.

FEG and it's environment is closed source  thus we will only upload the solidity files that are already public to see on the blockchain!

**If something is missing  feel free to make a pull request.**


# Updates

## 20/09/2021

### Migration towards pairs v2.2 (Fegex Pro)

#### Gas rebat
On new Fegex pro pairs after a transaction and if the conditions are met the person is able to get partially or even completly his gas fees. This fee is collected on a sell. Every sell will have 0.15% that goes towards this gas rabat.
##### ETH side conditions
* Hold 20B feg.
* A sell be under 1 ETH worth.
* A buy be above 0.05 ETH worth.
* Needs to be a fegex pro trading pair.

##### BSC side conditions
* Hold 20B feg.
* A sell be under 2 BNB worth.
* A buy be above 0.2 ETH worth.
* Needs to be a fegex pro trading pair.

#### Results
**BSC side**

Here we can see that the user got even more in return  than  what he paid  for
![image](https://user-images.githubusercontent.com/82654229/134473150-c818b763-322c-4ac4-9132-0341619b5590.png)

**ETH side**

Here we can see that the user only paid for 40% of the gas fees

![image](https://user-images.githubusercontent.com/82654229/134473233-04b24045-2655-488c-8c3d-143a62832ace.png)


### Autodeployer update
The autodeployer is now deploying PRO pairs only. A migration is made possible from pair v2.1 to v2.2. Once v2.2 is created no further migration is possible and further liquidity needs to wait 1 year until it unlocks.

All pair owners will NOW have direct access to pool settings and “sell-shares” and they have an ability to set an activation of their trading pair. This allows owners to inform the community and avoids getting  snipped by bots.

Staking has now been  increased to 0.15% of every sell and having a treshold to avoid that every transaction pais more gas fees due to a transfer beeing done

Every sell/buy has a 0.1% fees to buy and burn feg. Brining the total to:

* 0.1% buying fee
* 0.60% sell transaction fee


## 03/09/2021

### Migration towards pairs v2.1

* New pairs have been made on fegex. These pairs will now be able to be trade for a 1:1 instead of 1:0.99 which was previously the case because of the 1% from the wrapping/unwrapping process.
* Increasing the data accuracy such that it's easier to create proper charts. This will also help for fegcharts.
* Swap 2 swap has been implemented with it as well

### First smartdefi pair has been created

ROX token is now finaly out on the ETH and BSC chain.

### Autodeployer

* Autodeployer has been released as well. Now everyone has the ability to create new pairs over on  fegdeployer.com . 
* If help is required please check out [the video](https://www.youtube.com/watch?v=AgjBD6F905U) or the [FAQ](https://docs.google.com/document/d/1u943HybA7zrhXJSwClBu1YnWX9yDX5gEoDmIsqe5kVI)
* Every new pair will be locked for 1 year.
* Each new pair can be searched via contract address.
* Each verified pair can be searched by name
* On the first week teamtokens tax is set to 0 until the pool owner is verified. This is one way we ensured that the tokens creators didn't got frontrunned.

### Fegstats

* Displaying of ROX token with the baseline on it as well.
* Early charting for ROX has been created.

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



