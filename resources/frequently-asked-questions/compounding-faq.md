# Compounding FAQ

### Where can I find the current list of compounding strategies?

All our compounding strategies can be found on the [**Compound**](https://app.snowball.network/compound-and-earn) page of our website. You can also find a list of all strategies under the [**Compounding Contracts**](../smart-contracts/compounding-contracts/) page of our documentation.

### What fees does Snowball charge for auto-compounding?

Snowball takes a 10% performance fee on all profits made through auto-compounding. This happens once every harvest. There are no deposit or withdrawal fees.

### Are Snowball’s compounding strategies safe?

Snowball’s compounding strategies use code that has been forked from [**Pickle Finance**](https://www.pickle.finance), which has been audited. However, we still recommend using the protocol with caution as any new code may not have been fully audited. You can review our code on the [**Snowball GitHub**](https://github.com/Snowball-Finance).

### How does auto-compounding work with Snowball?

To learn about how auto-compounding works with Snowball, visit the [**Compounding**](../../products/compounding.md) page of our documentation. For a step by step guide on how to use Snowball’s compound feature, view our [**compounding guides**](../guides/).

### How do I earn SNOB rewards while compounding?

Once you’ve deposited tokens into a compounding strategy on Snowball, you will automatically start to earn SNOB rewards if the pool you deposited into has been voted on to receive rewards. SNOB rewards are determined by each pool's [**gauges**](../../governance/xsnob/gauges.md).

### How often are rewards compounded?

Rewards from our compounding strategies are compounded / re-invested 2-3 times a day. Feel free to check the #harvests channel on our [**Discord server**](https://discord.gg/BPnBYDSqcb) to see updates each time this takes place.

### Where can I see total harvested amounts?

We take snapshots of our weekly harvests. These are available on our [**Harvest Stats**](../harvest-stats.md) page.

### Does the APY on pools take fees into account?

All APR and APY values displayed on Snowball have already taken into account our performance fee. What you see is what you get, always.

### I don't see my pool on Snowball anymore. Are my funds safe?

If a pool you've deposited into is deprecated (no longer in use) it will not be displayed on our website. But do not worry, your funds are safe. Check out our guides [**here**](../guides/) on how to withdraw them.

### Can I get liquidated when depositing in any of Snowball's single-asset auto-compounding strategies?

There is no liquidation risk for any of Snowball's strategies. This is because on our folding strategies, you are borrowing the same token you are providing as collateral, and Snowball is constantly re-investing your rewards, so your borrowed amount will never surpass 100% of your collateral's value.

### My single-asset strategy balance is slowly decreasing over time. What is going on?

If the single-asset strategy you are deposited into involves folding, your balance will slowly decrease due to borrowing costs until a harvest occurs. When this takes place, Snowball is selling the rewards you've accumulated for your original underlying asset, and your balance will increase by a value much higher than what it decreased by previously. At the moment, these harvests take place 2-3 times a day and can be tracked through the #harvests channel on our Discord server.
