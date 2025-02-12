# Reward Boosting

Reward boosting increases the amount of SNOB rewards you receive from Snowball's products. Boosts are earned by holding xSNOB and are capped at a maximum of 2.5x (250% of regular rewards).

Your boost multiplier is determined by two factors:

1. Your proportional share of the xSNOB supply. The larger your share, the larger your boost.
2. Your proportional share of a product’s pool. The larger your share in a pool, the more xSNOB is needed in order to boost your rewards in such pool.

The reward boost granted by the first factor (xSNOB) applies to all Snowball pools. However, the boost received (up to 2.5x) for each pool will still be affected by your proportional share of the pool.

## Math Behind Reward Boosting

$$
\text{Derived Balance = User Balance In Gauge ∗ 0.4}
$$

$$
\text{Adjusted Balance} = \frac{\text{Total Deposited In Gauge ∗ User xSNOB Balance}} {\text{xSNOB Total Supply}} \text{ ∗ 0.6}
$$

$$
\text{Boost Factor} = \frac{\text{min (Derived Balance + Adjusted Balance, User Balance In Gauge)}} {\text{Derived Balance}}
$$

## Reward Boosting Resources

{% content-ref url="./" %}
[.](./)
{% endcontent-ref %}

{% content-ref url="../../resources/frequently-asked-questions/xsnob-faq.md" %}
[xsnob-faq.md](../../resources/frequently-asked-questions/xsnob-faq.md)
{% endcontent-ref %}
