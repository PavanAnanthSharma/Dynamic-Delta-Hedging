# Dynamic-Delta-Hedging
- Full worked example of the impact of delta hedging European options.
  
Dynamic delta hedging (DDH) is a trading strategy that involves hedging a non-linear position with linear instruments. Linear instruments include spot, forward, and futures contracts. DDH helps traders manage the Delta or Gamma of a portfolio without monitoring it

The most basic type of delta hedging involves an investor who buys or sells options and then offsets the delta risk by buying or selling an equivalent amount of stock or exchange-traded fund (ETF) shares. Investors may want to offset their risk of moving in the option or the underlying stock by using delta hedging strategies.

More advanced options strategies seek to trade volatility through the use of delta-neutral trading strategies. Since delta hedging attempts to neutralize or reduce the extent of the move in an option's price relative to the asset's price, it requires a constant rebalancing of the hedge. Delta hedging is a complex strategy mainly used by institutional traders and investment banks.

The delta represents the change in the value of an option in relation to the movement in the market price of the underlying asset. Hedges are investments—usually options—taken to offset any exposure to the risk of an asset.

Let's assume the options discussed have equities as their underlying security. Traders want to know an option's delta since it can tell them how much the value of the option or the premium will rise or fall with a move in the stock's price. The theoretical change in premium for each basis point or $1 change in the price of the underlying is the delta, while the relationship between the two movements is the hedge ratio.

The delta of a call option ranges between zero and one, while the delta of a put option ranges between negative one and zero. The price of a put option with a delta of -0.50 is expected to rise by 50 cents if the underlying asset falls by $1. The opposite is true, as well. For example, the price of a call option with a hedge ratio of 0.40 will rise 40% of the stock-price move if the price of the underlying stock increases by $1.

### Delta is dependent on if it is:

In-the-money or currently profitable
At-the-money at the same price as the strike
Out-of-the-money not currently profitable
A put option with a delta of -0.50 is considered at-the-money meaning the strike price of the option is equal to the underlying stock's price. Conversely, a call option with a 0.50 delta has a strike that's equal to the stock's price.
Reaching Delta-Neutral
An options position could be hedged with options exhibiting a delta that is opposite to that of the current options holding to maintain a delta-neutral position. A delta-neutral position is one in which the overall delta is zero, which minimizes the options' price movements in relation to the underlying asset.

For example, assume an investor holds one call option with a delta of 0.50, which indicates the option is at-the-money and wishes to maintain a delta neutral position. The investor could purchase an at-the-money put option with a delta of -0.50 to offset the positive delta, which would make the position have a delta of zero.


