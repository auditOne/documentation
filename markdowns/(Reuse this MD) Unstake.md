# Unstake

Unstaking is the process of exiting a current staking position, which reduces the user’s {{ token.StakedToken }} balance and increases their {{ token.UnstakedToken }} balance by exactly the same amount (barring a small deviation due to fees).

Unstaking on most Proof-of-Stake networks takes a considerable amount of time (anywhere between 7 to 30 days, depending on the specific network). Most networks implement a 21-28 day unbonding period. This is not ideal for stakers and is a user experience problem that needs to be addressed. To bypass this restriction, pSTAKE allows for instant redemption of {{ token.UnstakedToken }}s from {{ token.StakedToken }}s by charging a fee from {{ token.StakedToken }} holders to exit their staking positions. 

Once a user sends an unstaking transaction, the following process takes place:

* {{ token.StakedToken }}s are locked up (cannot be transferred)
* Native tokens are unstaked on the network
* {{ token.StakedToken }}s are burned
* {{ token.UnstakedToken }}s are minted and locked up for the duration of the unbonding period
* {{ token.UnstakedToken }}s are transferred to the unstaking user’s wallet at the end of the network’s unbonding period
