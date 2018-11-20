

********************************************************************************
CME Prospectus
********************************************************************************

:Founder: TheLoneTopwolfx
:Coordinates: (-6720, 3050)

The CME is offering to sell shares of common stock. The selling stockholders
identified in this prospectus are offering an additional `1000` shares of common
stock. Each share of common stock is entitled to one vote.

.. contents::

Definitions
********************************************************************************

Ask
    The price at which an exchange chest will sell an item.

Bid
    The price at which an exchange chest will purchase an item.

CME Token
    A type of Secure Note that the CME buys and sells.

Exchange chest
    A shop chest that both buys and sells the same item

Exchange
    A set of exchange chests in the same physical location that buy and sell
    the same type and quantity of item at different prices.

    Exchanges have the following properties:

    - Range (tuple of the maximum price you can buy at, and the minimum price you
      can sell at)

    - Number of exchanges in each chest (tuple of bids, asks)

    - A spread

Spread
    The difference in price between the bid and ask offered by a single
    exchange chest.

Business
********************************************************************************

The CME is a market maker for commodities; it generates revenue by buying items
at once price (the "bid"), and reselling them at a second higher price (the
"ask").

As a market marker,  the CME is different from other shops in two important
ways:

1. Most shops only sell items; they do not also buy them. When a shop only sells
   items, the incentive of the shopkeeper is to charge the highest price he
   can sell an item for. This means many shops charge "unfair" prices, and,
   consequently, are not useful most of the time, nor very profitable.

   In contrast, market makers make money by reselling items. This is most likely
   to happen if prices are approximately fair to everyone involved.

2. Shops that only sell items require a large amount of maintenance. If the shop
   runs out stock, the shopkeeper must gather more materials.

   In contrast, market makers never runs out of stock. There is always a way to
   interact with them.

There are two ways we collect fees: through spreads, and though CME tokens. The
decision to use a spread or CME tokens depends on the value of the item.

Tokens
================================================================================

CME tokens are a form of debt. Customers buy CME tokens to spend in the shop,
similar to an arcade, and can redeem tokens back into the currency (hence a
debt). In this case, tokens are pegged to iron, so 1 $CME can be redeemed for 1
iron. However, there is a fee to purchase tokens: 32 iron buys only 31 $CME, a
3% fee.

CME tokens can be combined with exchange tests that also capture a spread, but
at present we chose not to do so, because spreads limit the `efficiency` of the
exchange.

We need to be careful if we let people exchange tokens for two different types
of items. Traders who trade daily may evade fees by never redeeming tokens. If
someone sells diamonds for CME tokens and then buys an XP block for the CME
token, we will not have collected any fees. If a second person then sells XP
blocks for tokens and buy diamonds, we will have enabled a trade without
collecting any fees. If we had not used tokens, we would have had collected two
fees (in the spreads) instead of 0.

Risk Factors
********************************************************************************

Investing in shares involves a degree of risk. You should consider carefully the
risks and uncertainties described below.

In some loose order of how serious I think these threats are, from least
threatening to most threatening:

#. People may move away from the #.,+, and be unwilling to travel to the CME.

#. MTA citizens may vote in laws that hurt the CME.

#. We may get raided and have chests destroyed. If raided by an organized
   group, they could defend the area and acid#.block the whole shop.

#. We may get griefed with obsidian. This would close the shop down for several
   days until the grief can be removed.

#. Romec owns the plot, and may force us off of it or attempt to charge rent.
   The more valuable the CME becomes, the more of a problem this could become.

#. The thesis that people will be willing to travel if there is large stock may
   be false.

#. A competitor may arise and steal away transactions, by offering reduced fees
   or being accessible in a more convenient location.

#. People may not understand CME tokens

#. People may learn that holding CME tokens enables them to trade certain item
   pairs without fees

#. If the CME token printing plate is destroyed, we will be unable to print new
   tokens (or we will need a system for people to exchange them for each other)

#. If the CME token printing plate is stolen, we will need to disable all
   exchanges that use them before the thief can

#. We have a short operating history, and metrics are hard to capture. Errors
   in our metrics could result in incorrect business decisions.

#. The shop steward can commit fraud by underreporting the amount of profit.
   For example, if a customer sells 10 diamonds for 10i each, and a second
   customer buys each of those 10 diamonds for 11i each, the shop should have
   made 10i in profit. However, the steward could remove the 10i from the
   chest, and it would appear as if those transactions never happened.

#. The shop steward could empty the shop chests and run away.

Market, industry, and other data
********************************************************************************

One other diamond exchanges on the ground floor of the MTA mall, owned by
Olivay. He makes no profit from it. This has the effect of reducing the total
number of buyers and sellers we will connect. However, it also increases the
total supply of iron and diamonds available for trading in MTA, which should
make it more attractive for people to travel further distances to do large
trades.

A second exchange was built by Jinyo_Robin in Commonwealth before the Somber
War, but Jinyo removed all the stock before becoming inactive.

There are some chests that let people exchange diamonds and iron, but they are
set up as single chests, and usually become useless as soon as the market for
iron changes. Some examples include the Hjaltland shops in Yoahtl, Commonwealth,
and MTA.

In the case of XP and other commodities, we compete with anyone who is selling
the materials directly. Anyone who purchases at a shop that sells the same item
we are trading is a lost opportunity for us.

Use of proceeds
********************************************************************************

The CME stores 10-12 diamonds worth of items in each exchange chest, and each
exchange consists of 13 exchange chests. So about 130-156d per row.

- Buy 2 bastions and secure them in obsidian at bedrock. This will require
  working with Romec - they may need to be property of the mall in order to
  avoid interfering with other shops below.

  Bastions cost about 25d each. Plus they require DRO. The total cost of this
  will be at least 25 * 2 + 5 * 2 diamonds (5 * 2 assuming we use one piece of
  DRO on all sides, and places the bastion at bedrock).

- Add 2 more rows of diamond exchanges. This will require 10 * 13 *
  2 = 260 diamonds plus 13 * 2 = 26 double chests. The estimated cost of this
  is 312 diamonds.

- Add 8 rows of XP blocks. This will require 8 * 13 * 6 = 624 XP blocks, and 13
  * 6 = 78 double chests. The estimated value of this is 624 * 2 + 78 * 2 =
  1404 diamonds.

- Increase the supply of core XP ingredients (e.g sand)

- Increase the supply of key bastion ingredients (e.g. gold, redstone, lapiz)

  In addition to possibly being profitable, this would give the server a
  good estimate on how valuable mining is, and the opportunity cost of doing
  anything else. This is also important for security, since it informs how many
  diamonds can be safely stored in a shop chest.

- Increase the supply of logs. Logs have constant demand.

Capitalization
********************************************************************************

Balance sheet
================================================================================

The valuation of the CME is measured in iron. This is because it will be simpler
to compare over time as we expand to trade other materials.

The valuation of the CME is calculated by summing 1) the total number of
diamonds and iron stored in the exchange chests, and 2) the costs of the chests
themselves. The iron value of diamonds is calculated by measuring the amount
that the diamonds could be sold for on the CME's exchange.

As of Nov 13, 2018, the estimated value of the CME assets is the following::

    Cash, cash equivalents                      0
    Assets                                      17816.75
      Diamonds (273)                            04201.75
        Inventory (67)
        Reinforcement (206)
      Iron                                      13615
    Total liabilities                           0
    Total equity                                17816.75

As of Nov 17, 2018 (bid: 16.5, ask: 16.5), the balance is the following::

    Cash, cash equivalents                      0
    Assets                                      17712.5
      Diamonds (416)                            6355.5
        Inventory (210)
        Reinforcement (206)
      Iron                                      11357
    Total liabilities                           0
    Total equity                                17712.5

Income statement
================================================================================

Because the CME uses two currencies, there is no simple way to calculate
revenue- we cannot simply sum up all the diamonds and iron and compare one week
to another because we will hold different amounts of each as the prices
fluctuates. Instead, we aim to measure the number of transactions per exchange
chest. To do this, we measure per exchange chest a score called :math:`V1`
defined the in the following way:

.. math::

    V1 = BidPrice \times Asks + IronTotal

To understand why this works, consider a chest that offers the following
trades::

    11 Iron -> 1 Diamond
    1 Diamond -> 10 Iron

Assume it starts with 10 diamonds (:math:`V1 = 100`). If Alice buys a diamond,
then V1 increases by 1 (:math:`V1 = 10 \times 9 + 11 = 101`). If Bob then sells
a diamond, V1 stays the same (:math:`V1 = 10 \times 10 + 1 = 101`).  If this
repeats itself itself 10 times, then :math:`V1 = 10 \times 10 + 10 = 110`. And
if on that tenth time, Bob sells an eleventh diamond, then R stays the same
(:math:`V1 = 10 \times 11 + 0 = 110`).

Assuming that V1 is a good measure, the CME made 133 iron in 8 days (~16 iron
per day):

::

                    V1          Difference

    2018-11-09      14845       -
    2018-11-17      14978       133

Management
********************************************************************************

Metrics
================================================================================

The two ongoing expenses we need to pay are the shop steward who is
responsible for:

1. Adding, removing, and editing exchanges

2. Periodically creating balance sheets

If we assume it takes about 5 seconds to do an operation on a chest, and there
are 13 chests in an exchange, then it should take about a minute to a perform
an operation on every chest in an exchange.

Security
================================================================================

My philosophy on security is that the only effective security is that which can
be publicly revealed and still work (Kerckhoffs's principle).

I do not consider bounties an effective form of security. Thieves today use
alts, and even if they did not, bounties are expensive to place.

The CME stores items all items in double chest reinforced with two diamonds
each. This means it takes 10 minutes to break into a double-diamond reinforced
chest using either an E4 or E5 diamond axe, both of which can break a chest in
0.15 seconds. [3]_ I had previously calculated that a person could generate 3
diamonds per minute from mining. If that is true, the maximum value that can be
safely stored is 30 diamonds. There are different factors that affect this, in
particular the probability of being caught, and the mining skill of the
attacker.

The CME also has snitches throughout the shop, some of which are surrounded by
diamond-reinforced obsidian. These form a chain, so there is no way to remove
a snitch without being caught by another snitch. At present, each floor of the
shop uses four snitches in each of the corners.

Snitches get culled if nobody with the permission to ``LIST_SNITCHES`` goes near
the snitches every so often. [2]_ It may be possible to give public access to a
subset of the snitches to prevent snitches from ever culling, so long as this
does not give people the ability to clear the logs.

The CME does not have bastions, which means the shop can be obby-griefed and
acid-blocked. Obby grief could disable the shop for hours or days. The shop was
acid-blocked in June 2018, and nobody noticed for at least a day. [1]_

The CME printing plate, if compromised, would require a new set of tokens to be
produced, and could lead to loss if we do not disable all chests that use them
before the attacker prints out tokens. Since CME tokens are used in 2
exchanges, the total value that could be lost if an attacker steals the
printing plate, prints tokens, and exchanges them for real items could be up to
2 * 13 * 12 = 312 diamonds. In addition, the CME tokens would need to be
replaced, which would cost about 50 diamonds.

The biggest potential threats to the CME are internal rather than external.
Anyone who has access to the shop chests can severely hurt the CME in multiple
ways:

1. By stealing items from all chests they have access to

2. By under-reporting profits

I see no simple way to protect against either of these threats. One option may
may be to hold the pearls of anyone who has access to chests. Another option
may be to insure the shop chests. (The insurance for this could be put up for
auction. [4]_)

References
********************************************************************************

.. [1]
    TheLoneTopwolfx. 8d bounty on Solitarire7 - Trying to acid block the CME.
    https://www.reddit.com/r/civclassics/comments/8ph55i/8d_bounty_on_solitarire7_trying_to_acid_block_the/

.. [2]
    Maxopoly.
    https://www.reddit.com/r/civclassics/comments/9tmxe2/when_do_snitches_get_culled/e8xhsxn/

.. [3]
    TheLoneTopwolfx. On the maximum value to store in a shop chest.
    https://www.reddit.com/r/civclassics/comments/6ss6pt/on_the_maximum_value_to_store_in_a_shop_chest/

.. [4]
    TheLoneTopwolfx. How to insure goods you want to ship.
    https://www.reddit.com/r/civeconomics/comments/86x0mn/how_to_insure_goods_you_want_to_ship/
