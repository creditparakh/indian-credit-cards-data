# Indian Credit Cards: Fees, Rewards, Lounges (2026)

Fees, reward rates and airport lounge rules for **85 credit cards issued in India**, taken only from each bank's own product pages, fee schedules (MITC) and reward terms. Every row has the bank's source URL and the date it was last checked.

Maintained by [CreditParakh](https://creditparakh.in/credit-cards/compare/), an independent credit card and personal loan comparison site for India.

## Files

| File | Rows | What it is |
|---|---|---|
| [`data/card-fees.csv`](data/card-fees.csv) | 85 | Joining and annual fees, fee-waiver rule, lifetime-free flag, forex markup %, works on UPI (RuPay), published minimum income |
| [`data/card-rewards.csv`](data/card-rewards.csv) | 85 | Effective value back (% of spend) for everyday, online, grocery, fuel, UPI, travel, bills and dining spends; published reward caps; spends that earn nothing |
| [`data/card-lounges.csv`](data/card-lounges.csv) | 47 | Domestic, international and railway lounge visits a year, and the spend needed to unlock them |

The live files, always current, are at `https://creditparakh.in/data/card-fees.csv`, `card-rewards.csv` and `card-lounges.csv`. JSON versions are there too.

## How values are worked out

- **Value back** is the % of spend returned, at the redemption value the bank itself publishes. Where a bank doesn't publish what a point is worth, the cell is blank rather than estimated.
- **Dining** is value back on restaurant bills and food-delivery apps. Where a card pays more only on delivery apps, that rate is used.
- **Fees** exclude GST.

## Coverage

The cards compared on CreditParakh: the most-searched cards in India plus those available through our referral partner. It isn't every card in India. Rankings and data never depend on what we earn.

## Updates

Data as of 2 Nov 2026. Rechecked monthly. Dated card changes are logged at <https://creditparakh.in/credit-cards/changes/>. Banks change terms often; each row's `last_verified` date and the bank's current terms win.

Found an error? Email support@creditparakh.in or open an issue.

## Licence

[CC BY 4.0](LICENSE). Free to reuse, including commercially, with credit and a link:

> Source: CreditParakh, https://creditparakh.in/credit-cards/compare/
