## RISK AND RETURN

### Definitions
- The return and risk of an asset are commonly measured in terms of the mean and standard deviation (SD).
- The total return represents income + capital gains or losses
- The mean is the return one expects to obtain on an average
- The SD is a measure of the volatility of a return. Its commonly associated to the risk of an asset

### Why SD = Risk ?
- SD is a measure of how much an investment fluctuates from its expected return
- When a price moves widly, SD is high
- Low fluctuations in price generally signals low SD.
Thus SD helps determine the market volatility or the spread of asset price from their average price thereby serving as a good proxy to for "risk". So low fluctuations signal low risk and high fluctuations signal high risk.

### Relation between Return and SD
For a Bell Shape distribution curve signifying the return, one will actually experience price fall within one SD either side of the mean about 68% of the times. Within 2 SD's 95% of the time and with 3 SD's 99.7% of the time

![alt text](https://github.com/devak23/stockmarket-glossary/blob/main/images/Return_SD.png?raw=true)

### Historical Returns Vs Future Returns
The mean and SD of a return for a given asset can be computed from historical returns. In that case, however, they are merely "summary descriptors" of the past performance and may or may not relfect the probability distribution of future returns.
Investors ofcourse need to estimate the mean and SD of the future returns (which is impossible in practise unless you are Dr. Strange). This is one of the main limitations of Markowitz portfolio theory.

### Asset Comparison
Assets can be compared on the basis of their means and standard deviation by drawing a simple diagram as shown below.

![alt text](https://github.com/devak23/stockmarket-glossary/blob/main/images/InvestInOnlyOneAsset.png?raw=true)

The X represents the returns (mean) and Y represents the risk (standard deviation). 
- Asset A is a risk free asset like a cash/govt bonds
- Asset B has higher mean and higher SD than asset A
- Asset C has higher mean and higher SD than asset B
- Finally asset D has the highest SD but a lower return than B and C.

If you can invest in one of the 4 assets which one would you pick? The ideal choice would be an asset that lies at the top left corner indicating ALL returns and ZERO risk. The right hand bottom corner on the other hand would be the worst of all with NO returns and ALL risk. 
- Thus we can easily rule out asset D since it has lower returns than B and C and higher risk.
- Assets such as D are said to be "dominated" by B and C. In this figure D is the only dominated asset. Dominated assets are relatively easier to remove from consideration.
- Which one is the dominated asset between A,B and C? That requires knowledge of risk.
- A risk neutral investor would prefer C and a risk averse investor would prefer A.
- Asset B is probably best for somone who is not overly risk averse and also not quite risk neutral.

### Portfolio Standard Deviation (Diversification)
Suppose we can invest our money in a portfolio of just two assets, asset A and B, both of which are risky. Let Wa be the fraction invested in asset A and Wb be the fraction invested in asset B, where Wa + Wb = 1 (or 100%)

The portfolio return is just the weighted average of Wa & Wb as follows:

Ep = Wa x Ea + Wb x Eb
- Wa = investment in A
- Wb = investment in B
- Ea = expected return of A
- Eb = expected return of B
- Wa + Wb = 1

This formula of the portfolio expected return is quite easy and intuitive. However, the formula for the portfolio standard deviation is more complicated. It is given as follows:

Sp = sqrt[sqr(Wa) x sqr(Sa) + 2 x Wa x Sa x Wb x Sb x R + sqr(Wb) x sqr(Sb)]

Wa, Wb = investment in A and B respectively
Sa, Sb = SD of A and B respectively
R = correlation between returns of A and returns of B

Correlations are between -1 and 1. They are a measure of the degree to which the returns on to assets fluctuate together. 

- When the correlation = 1, the returns are perfectly correlated. When one goes up, you know exactly by how much the other will go up.

- When the correlation = -1, the returns are perfectly negatively correlated. When one goes up, you know exactly by how much the other will go down.

- When the correlations = 0, knowledge of what happened to an asset gives no information about the other.


The square root formula is the most general one and encompass all these special cases we have so far discussed. For example, when R = 1, the assets are perfectly correlated:

Sp 	= sqrt[sqr(Wa)sqr(Sa) + 2 WaSaWbSb + sqr(Wb)sqr(Sb)]
	= sqrt[sqr(WaSa + WbSb)]
	= WaSa + WbSb

For risky assets that are not perfectly correlated, the correlation is less than one and there is a non-linear or curve relationship between the SD of the portfolio and the investment in the assets.

![alt text](https://github.com/devak23/stockmarket-glossary/blob/main/images/ImperfectCorrelation.png?raw=true)

Moreover, the SD of the portfolio is always less than the weighted average of the SD of asset A and B, as we can see in the figure. This fact is of great significance in lies at the heart of the portfolio theory.

It means if one holds, say, equal amounts of risky assets that are not perfectly correlated, the portfolio expected return will be the average of the respective returns of the assets in the portfolio. However, the portfolio SD will be less than the average of the SD of the assets in the portfolio.

The power of prior statement is best demonstrated by imagining two assets with the same expected returns and the same SD of return in an imperfect correlation.

By holding both assets in a portfolio, one obtains the same expected return as either one of them, but a SD that is no worse than any of them individually. Thus, diversification leads to a reduction in risk without any sacrifice in expected return.

