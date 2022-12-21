# Relation between inflation and reward rate

Networks with low inflation rates are often left aside when delegators look for projects to buy and stake tokens. But it is important to know that you can still generate high returns if the percantage of bonded tokens is low.
That's why we will clearify that the inflation of a network is not always the same as its rewards rate.

The reported inflation rate is often different than this effective inflation rate.
This is because block times affect the system's calculation for minting new tokens, so this means it also affects your staking rewards.

### Let's use Comsos for an example

In the case of Cosmos, if block times are greater than 7,233 seconds per block, you're earning fewer rewards than anticipated. Currently block times are around 7,355 seconds per block.

***
TO BE ADJUSTED

Quick Take
Think of Cosmos' newly-minted ATOMs as a pie: inflation is the size of that pie. Staking is your right to claim a slice of the pie. We pool and split the rewards with everyone else staking, so the more that others stake, the smaller the slice of pie you get. The bigger the pie, the bigger the slice for everyone staking.

Cosmos Stats from Sep 25, 2019
Inflation = 7.50%
Rewards rate = ~10.61% (based on a rough calculation)

Inflation Rate Changes Slowly
Cosmos' inflation rate changes very slowly, based on a targeted staking participation rate of 67%. That means that when 67% of all ATOMs are staked, the inflation rate will stop changing.

Inflation decreases if over 67% of ATOMs are staked, and very gradually, bottoming out at 7%. Right now, 70.69% of ATOMs are staked and inflation is 7.50%. In a week from now, for example, we can expect that inflation will be 7.48% if over 67% of ATOMs are still staked. Let me know if you want to see the math for this.

Inflation increases if under 67% of ATOMs are staked, maxing out at 20%.

The pool of Cosmos rewards is a pie that we share
cosmos inflation
Think of Cosmos' newly-minted ATOMs as a pie: inflation is the size of that pie. Think of staking as your right to claim a slice of the pie. We pool and split the rewards with everyone else staking, so the more that others stake, the smaller the slice of the pie is that you get. The bigger the pie, the more rewards everyone staking gets.

The rewards rate
A quick way to do calculate the rewards rate is with this equation:

inflation_rate / staking_ratio

Right now the inflation rate is 7.50%, so:

inflation_rate = 0.075

173.10M ATOMs are currently staked out of the entire 244.86M ATOM supply, so:

staking_ratio = 173.10M / 244.86M = 0.7069

Final, rough calculation for staking rewards:

0.075 / 0.7069 = 0.10609

Therefore stakers are currently earning approximately 10.61% rewards for staking on Cosmos. And that could change much quicker than inflation can.

The rewards rate changes faster
The reason that rewards rate can change quicker than the inflation rate is because it's a factor of how many ATOMs are currently staked. Right now, 70.69% of ATOMs are staked, but let's take a look at two scenarios.

Scenario 1: stake 49M new ATOMs
If I suddenly staked 49M ATOMs, 90.69% of ATOMs would be staked. How would that impact on inflation? It would have no impact. But it would dramatically change the rewards rate:

0.075 / 0.9069 = 0.08270

As soon as I staked 49M ATOMs, stakers would go from earning ~10.61% to earning ~8.27%. This is very unlikely to happen, but it's an extreme example to show that the rewards rate is more volatile than the inflation rate is. Let's do the same for unstaking 49M ATOMs.

Scenario 2: unstake 49M ATOMs
If I suddenly unstaked 49M ATOMs, 50.69% of ATOMs would be staked. How would that impact on inflation? It would very little impact, taking over 12 weeks to increase from 7.50% to 7.75%. But it would dramatically change the rewards rate:

0.075 / 0.5069 = 0.14796

As soon as I unstaked 49M ATOMs, stakers would go from earning ~10.61% to earning ~14.80%. This is also very unlikely to happen.

Reported vs Effective Inflation
Popular staking explorers reporte the Cosmos Hub's inflation rate, but the effective rate is often different from the reported rate. This is important because even though the system is intended to mint new ATOMs at the reported rate, it actually tends to produce fewer ATOMs.

How come? Because block times affect the system's calculation for minting new ATOMs. The system mints new ATOMs assuming there will be 4,855,015 blocks per year, which means an average of 6.50 seconds per block. However, as of March 1, 2020, average block times are approximately 7.12 seconds per block. That means ~8.7% fewer blocks are being produced per year than what the system assumes.

How does that affect me? If you calculated your January 2020 rewards based on the reported inflation, you would expect to receive an annual rate of 9.43%, and instead you would receive 8.61%. In general, you're receiving fewer staking rewards than anticipated if block times are greater than 6.50 seconds per block.

How can I calculate my effective rewards rate? The quickest and most relatively accurate way is to take the assumed block time of 6.50 seconds/block and divide that by the actual block time. For example, if block times are currently 7.12 seconds/block:

6.50/7.12 = 0.91 = 91% (the effective rate is about 91% of the reported rate)
9.43% * 91% = 8.58%

In this case, you're effectively receiving approximately 8.58% staking rewards. Note that this is not the precise rate, but it's the quickest, relatively accurate calculation.
