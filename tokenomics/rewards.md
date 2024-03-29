# Rewards

As described on the [Token Emission](token-emission.md) Section, the Rewards are the incentives cobogo has designed for Fans to fund their favorite Creators while also being rewarded for it. It is a win-win mechanism for both Patrons and Creators.&#x20;

### 1. Game Theory

Let us introduce you, through a simple Game Theory example, the incentives that cobogo creates that makes it, for some people, a superior option to sustainably fund Content Creators.

To show each particular incentive and differentiate them, let us show you a model: this will be a static game, prices are constant and the players can only choose to either use cobogo or Donate.&#x20;

Just to be clear, in real life, when you join cobogo, you're not required to give up on donations, in fact as a funding aggregator we encourage individuals to choose the best way for them to fund their favorite Creator.

#### 1.1. The Game

Suppose there are 2 players, one is the Creator and the other is the Fan. The latter dedicates $100 of his monthly income to donate to his favorite Open Source Software Creator. Financially the amount he donates gives him a **-** **$100** payoff, but, let's say that the satisfaction of donating to his favorite project is equivalent to him to a **+$100** payoff. The net payoff for him would be **$0**.

![](../.gitbook/assets/2.png)

Now consider that a Creator has his project pool on cobogo and only accepts CBG. In this case, the potential Patron who either did not afford to be altruistic or did not get the sufficient satisfaction from being altruistic to justify a donation might get the incentive to fund that project.

Let's say that the Patron stakes the sufficient amount of CBG tokens that the Monthly Yield equals $100. In this case he gets both the **+$100** from the staking rewards AND the equivalent of **+$100** from the satisfaction of donating for his favorite project.

![](../.gitbook/assets/1.png)

So in this game, both strategies **cobogo staking:cobogo staking** and **Donation:Donation** are Nash Equilibria. But, when the Fan deviates his strategy to cobogo staking he has a better payoff, making it the **dominant, and** **optimal** **strategy**.

### 2. Detailing the Rewards

In our split funding mechanism both Fans and Creators get a yield that come from the token emission, the treasury and platform fees.

The reward emission is inversely proportional to the staking ratio, that is, the lower the amount of CBG staked in relation to the total CBG circulating supply, the higher the Reward is, and vice-versa. This way, we are creating incentives for first-mover Patrons to fund their favorite creators and be rewarded for it.

In our model, staking ratio ( amount of tokens staked / Circulating Supply ) is inversely proportional to the Rewards. If set free, just taking in consideration these two variables, at lower tail, the APY could be explosive. So, instead of tending to infinite, we designed it to have a cap at 10%. This way, at the staking ratios, it tends to 10% and at high staking ratios it tends to 0%, that's what we call the emission band. The staking ratio changes over time so does emission rate - inside the bands.

Here is our model:

```
                       R_t = S_t - S_t-1  (1)
                       R_t = 1.1 S_t * (1-\sigma CBG Staked / Circ. S_t)^[(10-\sigma CBG Staked / Circ. S_t*8)/3]  (2)
```

By minimally increasing the total supply, and distributing it to stakers (part of the circulating supply), we are able to create a significant APY to reward first-movers. Our goal is to use this mechanism to attract as many Creators as possible, which will generate network effects, implement easy to offer perks and services to collect fees (Content and Media Market).

As the number of active creators grow, valuable Perks are implemented, we expect that the APY coming from emissions will continue to go down and the APY coming from fees will continue to go up.

We also expect the platform to be viewed as less risky, and the Perks so valuable that individuals are willing to stake instead of donating just to be able to access those Perks, interact with the Creator .

