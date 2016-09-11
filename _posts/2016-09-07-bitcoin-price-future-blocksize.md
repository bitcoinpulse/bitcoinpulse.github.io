---
layout: post
title: "Bitcoin Economics: The Impact of the 2016 Halving in Mining Revenue and Price"
---

<style>
.blockquote {
  font-size: 13px;
}
.blockquote p {
  margin-bottom: 0.35rem;
}
.footnotes {
  font-size: 10px;
}
</style>

2016 has been another interesting year for Bitcoin.
It started with a fracture in the community caused by the ongoing blocksize debate.
Later, the 2nd halving day arrived, lowering the mining reward to 12.5 BTC/block.

In terms of price, as of the time of writing (September 7th, 2016), Bitcoin has increased by ~180 USD (+41.5%).

Here, we will see how this might be affecting miners and also take a peek at transaction fees.<br /><br />



### Mining Revenues

It is a fact that miners play a big role in the price of Bitcoin.
Every day (every 100 blocks, to be precise), they have the opportunity to increase the supply of bitcoins in the market, by selling their mining reward.
The mining rewards include the (12.5) bitcoin from the coinbase transaction and the fees from the transactions included in the mined block.

As such, it is probably a good guess that miners are one of the biggest players in the trading game, potentially selling over 1800 BTC/day.
While not everyone's selling - some might decide to hold partial or total amounts for strategic reasons, and others might be using the rewards to repay debt that was incurred when investing in equipment, etc - it's reasonable to assume that a good chunk of the newly mined bitcoins is traded in the market.


##### A Peek Into Transaction Fees

Currently, on average, each mined block contains less than 0.5 BTC from transaction fees [^1], i.e. around ~4% of the total mining reward in a block.
If we assume an average of 1600 transactions per block [^2], that's an average fee of 0.00031250 BTC (31250 satoshi, ~0.20 USD) per transaction.

[^1]: Assuming 144 blocks mined, and a total of 70 BTC in transaction fees, per day.

[^2]: [Average Number of Transactions Per Block](https://blockchain.info/charts/n-transactions-per-block?timespan=1year)

The following image overlays two graphs: on top, the [Average Number of Transactions Per Block](https://blockchain.info/charts/n-transactions-per-block?timespan=1year) and, on the bottom, the [Total Transaction Fees](https://blockchain.info/charts/transaction-fees?timespan=1year).

![](/resources/2016-09-07-txs-per-block-and-fees.png)

<sub>For information on what happened in the transaction fees of April 27 [^3].</sub>

[^3]: [User Error Sees Bitcoin Mining Pool Earn $135,000 as Fee](https://www.cryptocoinsnews.com/user-error-sees-bitcoin-mining-pool-earn-135000-fee/)

We can see that since last year, both transactions per block and their fees have significantly increased.<br/>
The number of transactions per block has gone up ~166%, from ~900 transactions to ~1500 transactions (rough average).<br/>
The fees have gone up ~280%, from ~25 BTC/day (~0.17 BTC/block) to ~70 BTC/day (~0.49 BTC/block).<br/><br/>



### The Impact of the 2016 Halving in Miners' Revenues

It is believed that the 2016 Halving was the main cause for the price rally in the 4 weeks prior to July 9th (the date of the halving).
While the price has been following a general upwards tendency, it spiked from ~450 USD to a year-high of 762 USD until finally stabilizing at ~650 USD after the halving.

But things are actually not looking rosy for miners - even with the price increase and although more transaction fees are being included in each mined block since last year, there has been a very significant drop in the miners' revenues [^4].

[^4]: [Blockchain.info Chart - Miners Revenue](https://blockchain.info/charts/miners-revenue?timespan=1year)

![Annotated Miners' Revenues](/resources/2016-09-07-miners-revenue.png)

As we can see from the image, post-halving miners' revenues have not yet returned to the pre-halving rally levels, even though Bitcoin has gone from ~370 USD to ~570 USD (+200 USD)!
(In the same period, transaction fees have also gone from ~40 BTC/day to ~70 BTC/day.) [^5]

[^5]: An alternative analysis that seems to confirm this is to look at the number of [Confirmed Transactions Per Day](https://blockchain.info/charts/n-transactions?timespan=1year) (going up), the [Cost Per Transaction](https://blockchain.info/charts/cost-per-transaction) (which is actually the miners' revenue divided by the number of transactions), and the [Bitcoin Market Price](https://blockchain.info/charts/market-price?timespan=1year).

But it is worth noting that, since late 2013, miners' revenues are only slightly above the historical 2015-lows.
One could always argue that the price bump from late-2015 was factoring in the upcoming halving day and that the current mining revenue is the point of equilibrium for the miners [^6].

[^6]: I'm not sure I would buy such an argument given the evolution of the ecosystem, but if anyone has any data to back such an argument, please send it over.
<br/>



### What Now for Miners?

Some interesting opinions have been thrown around pre-halving in [What to Expect When the Bitcoin Halving Happens](http://www.coindesk.com/bitcoin-halving-2016-what-to-expect-traders-miners/):

<div class="blockquote">
<p>At one point, there were some miners who expressed concern that the halving could impact their profitability, enough so that some would be forced offline. Chandler Guo, the founder of Bitbank and its subsidiary, BW, was one of these community members.</p>
<p>He argued in the beginning of June that, "<b>if the price doesn’t go up very quickly, up two times, it means a lot of the older machines will be shut down. They must shut down</b>".</p>
<p>Further, he cautioned that 300 petahash of older machines could be forced off the network. But, since that interview, the price has increased from $530 to $650, meaning that this dynamic has changed.</p>
</div>

Indeed the price did increase, but not 2x yet (and the Bitfinex hack did not help).

<div class="blockquote">
<p>While Armageddon is not around the corner, <b>there is agreement that hashrate on the network, which currently stands at 1.54 exahashes per second will experience a slight decline</b>.</p>
<p>Marco Streng, CEO of hosted mining services firm, Genesis Mining, isn’t too concerned about this, however. "I think due to the halving, a slight hashrate drop is realistic to assume,” he said.</p>
<p>Terrence Thurber, co-founder and CEO of hosted bitcoin miner Oregon Mines, echoed Streng's predictions about the network experiencing some drop in the total hashrate.</p>
<p>"We continue to believe that total network hash rate will decrease by approximately 10% after halving as older equipment that is no longer economically viable will leave the network. Later generation machines ... will pick up some of the slack," he told CoinDesk.</p>
<p>Elsewhere, BitFury CEO Valery Vavilov expressed optimism about the halving, though admitted that his firm expects some drop in hashrate.</p>
<p>"Some decline in the bitcoin network hashrate is expected (after the halving), and we believe it will be insignificant," he told CoinDesk (...)</p>
</div>

And while the [Hash Rate](https://blockchain.info/charts/hash-rate?timespan=180days) did take a dip after the halving, it was a blip and has since gone up again.

<div class="blockquote">
<p>But the drop in hashrate won’t be as significant primarily because the only real cost that miners have is electricity.</p>
<p>Eric Mu, the chief marketing officer at HaoBTC, a mining firm with approximately 5.5% of hashrate, explained that the effect of halving likely won’t be immediate.</p>
<p><b>"The bulk of the cost is sunk in the form of mining equipment and infrastructure, at least that is our case," he said.</b></p>
<p>Litecoin’s halving event, which took place on 25th August, 2015, supports Mu and Lombrozo's belief that the effect won’t be significant.</p>
<p>When the halving happened, the hashrate was 1.19 TH/s. Over the following days, that dropped to 1.11 TH/s, which was only a 7% drop.</p>
<p>Charlie Lee, the creator of Litecoin and director of engineering at Coinbase, explained why the drop was so small in a reddit post.</p>
<p><b>Because China-based hydro power plants generate too much electricity, he explained, they will sometimes give miners free electricity for a share of revenue. Miners may make half as much at halving, but with free electricity, he argued they're still profitable.</b></p>
</div>

Here, we start to get into the real economics behind mining.
Most of the mining capacity is concentrated in China.
As long as the mining electricity is subsidized by the Chinese Power Companies, and the fixed costs (personnel, rents) and other possible costs (e.g. investment in mining equipment) are all below the current revenue, we could assume that the revenue drop is being buffered by the those miners.

But miners are not all the same, and those without free subsidized power should want to sell their Bitcoin at a higher price.
And even though equipment development seems to have hit a ceilling, any new mining players coming into the market will squeeze returns even more.

Perhaps we have not yet felt the full impact of the 2016 Halving.<br/><br/>


