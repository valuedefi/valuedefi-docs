---
id: vsafefaq
title: vSafe FAQ
sidebar_label: vSafe FAQ

---
---


**1. What is a vSafe?**

vSafe is a yield aggregator that will search for the best farming targets, deposit your investment, trade farming rewards for deposited tokens, and re-invest automatically.

It compounds your deposited assets frequently, ranging from once every few hours to once per hour, depending if yield is higher than $200 during that period as more frequent harvests with lower yield might actually reduce returns. 

**2. What are the deposit and withdraw fees?**

Good news; there are **NO** deposit and withdraw fees on the Value DeFi platform.

**3. What is the performance fee?**

Performance fee is a fee that is paid out from vSafes profits and is already calculated in APY, it doesn't affect your capital as we have no deposit or withdrawal fees.

**4. Does a vSafe auto-compound the rewards? And if true, why is there a 'Compound for all' button?**

A vSafe will automatically auto-compound the rewards and that capability is enabled by default.  vSafe frequently auto compounds but users who wish to increase compounding frequency or who are withdrawing from vSafe are able to press the “Compound for all” button in order to squeeze a bit more profit before withdrawing.

**5. What is the reward token?**

The reward token of a vSafe is the same token/LP that was used to stake into it.  If a vSafe has a 'BOOSTED' label, it means you will be receiving some additional vBSWAP as an incentive.  The mutliplier on a 'BOOSTED' vSafe (i.e., 0.1x) will help you determine the approximate amount of extra vBSWAP tokens the vSafe will be emitting.

**6. When i deposit my LPs i get less shares, why and what are shares?**

Shares are proof of deposit tokens and a way that vSafe calculates auto compound for each user equally. 

![vsafefaq1](../img/vsafefaq1.png)

In this example if you deposit 100 CODEX/BNB LP tokens you would receive 63.63 vSafe CODEX/BNB shares (100/1.57136 = 63.63). Over time as vSafe auto compounds, for example, 1 share will be worth 2.4 CODEX/BNB so when you withdraw you would receive 152.71 CODEX/BNB LP tokens (63.63*2.4=152.71) which would make your profit 52.71 CODEX/BNB LP tokens.

**7. What is the lock symbol and why am I getting less than it is shown on UI?**

Some of our vSafes are using strategies that are dealing with locked/vested/delayed reward emissions, you can find general principles how it works [here](https://docs.valuedefi.io/guides/vFarmvsvSafe) but we will be adding vSafe overview with more detailed release schedule soon.

This is just short overview of our currently locked strategies

| Name         	| Instantly claimable  	| Locked / burned                                                                                                        	| True Daily APY pre reward release    	|
|--------------	|----------------------	|------------------------------------------------------------------------------------------------------------------------	|--------------------------------------	|
| Codex        	| 20%                  	| 80% released linearly to approximate [block](https://bscscan.com/block/countdown/8891201)                                    	| 80% lower due to lock                	|
| Ellipsis     	| 50%                  	| 50% burned (already calculated in APY)                                                                                 	| APY accurate                         	|
| Iron.finance 	| 30%                  	| 70% locked till [block](https://bscscan.com/block/countdown/6675734) then linearly released for 90 days                	| 70% lower due to lock                	|
| Nerve        	| 33.33%               	| 66.66% linearly released at approximate [block](https://bscscan.com/block/countdown/11483201)                                  	| 66% lower due to lock                	|

**8. What is deposit and stake?**

Some vSafes have boosted tags which means users have the option to stake their vSafe shares for additional vBSWAP incentives. If users choose to do so, external portfolio trackers such as growing.fi, farm.army or vfat.tools will only display your APR of vBSWAP incentives, not the compounding APY of vSafe that is done on the back end. 

**9. Why is my USD amount displayed on vSafe UI lower, same, higher?**

![vsafefaq2](../img/vsafefaq2.png)

As the tooltip says, USD amount is estimated and may vary, best advice is to use an external tracker such as growing.fi, farm.army or vfat.tools and be aware that it will not display your deposited amount and yield if you staked your shares.

**10. Why are there two apy numbers and which one is real?**

![vsafefaq3](../img/vsafefaq3.png)

Green apy number is calculated as compound interest with optimal 8760 compounds per year (once per hour). APY in white letters at bottom of the screenshot is one of our strategies or liquidity mining pool/vault that we are using.
