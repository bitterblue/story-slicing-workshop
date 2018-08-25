
# Story Slicing

We are building a new Point-of-Sales system to support the cashiers in our
shops.  The new system will calculate total prices including value-added tax
(VAT) and potential discounts.  We plan to roll out in several European
markets.

Input is:

* number of items
* price per item
* a 2-letter code for the country we are selling in

Output is the total price.

Discounts based on the total price are

| Order Value | Discount Rate |
|------------:|---------------|
|     1.000 € | 3%            |
|     5.000 € | 5%            |
|     7.000 € | 7%            |
|    10.000 € | 10%           |
|    50.000 € | 15%           |

VAT is applied to the discounted price and differs from country to country.

| Country        | Code | VAT Rate |
|----------------|------|----------|
| Luxembourg     | LU   | 17%      |
| Germany        | DE   | 19%      |
| France         | FR   | 20%      |
| Poland         | PL   | 23%      |
| Hungary        | HU   | 27%      |


Original exercise by Alistair Cockburn. See also the [Facilitation Guide][1] by
Henrik Kniberg.

[1]: https://blog.crisp.se/2013/07/25/henrikkniberg/elephant-carpaccio-facilitation-guide

