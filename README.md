<h1 align="center">DiversiFi: The Global Crypto Pawn Shop</h1>

<p align="center">John Shutt</p>
<p align="center">john.d.shutt@gmail.com</p>

It’s outrageous to pay 50% to 300% annual interest on an overcollateralized loan, but people do every day at pawn shops. It’s a $15 billion per year industry in the United States. Many borrowers are unbanked or underbanked, unable to access better lines of credit. This post outlines the basic operations of DiversiFi, a global and decentralized financial layer for collateralized loans. DiversiFi could slash the interest rates of borrowers, increase the lending capital of pawnbrokers, and provide superior returns for a global network of lenders.

## How Pawn Shops Work

A borrower leaves a valuable item as collateral with a pawnbroker, usually a local small business lending money from its own account. The pawnbroker assesses the item and gives a loan for a fraction of the assessed value, charging a high interest rate. The entire loan usually must be repaid within a certain timeframe, or the borrower must pay interest on the loan and renew the loan for another month. If the borrower fails to meet the terms of the loan, the pawnbroker can sell the collateral.<sup>1</sup> There is no hit to the borrower’s credit score.

## Why Are Pawnbroker Interest Rates So High?

Pawn shops tend to be undercapitalized small businesses with spiky cash flow and don’t always have efficient means of selling collateral from defaulted loans. Loan offers vary dramatically based on pawn shops’ lending capital, short-term operational costs, and ability to efficiently liquidate a particular type of collateral.<sup>2</sup> If pawnbrokers could resell their risk in a global market, locking in a profit and replenishing their lending capital before loans come to maturity, they could afford to issue more loans on better terms. The ultimate effect should be a dramatic reduction in interest rates as global price competition drives down local borrowing costs. There is no good reason why an overcollateralized loan should charge 300% annual interest. If anything, pawn shop loans should charge *lower* interest rates than unsecured credit cards.<sup>3</sup> Reducing pawn shop interest rates to be in line with or lower than credit card interest rates would save borrowers billions of dollars per year.

## Roles in the New System

**Pawnbrokers**
- Loan Origination
- Collateral Assessment
- Collateral Liquidation
- Warehousing
- Local Regulatory Compliance
- Customer Service
- Marketing

**DiversiFi DAO**
- Tokenization of Debt
- Debt Token Marketplace
- Pawnbroker Onboarding
- Lender Onboarding
- Debt Token Settlement
- Debt Token Buyer of Last Resort
- Smart Contract Governance

**DiversiFi Lenders**
- Purchase of Debt Tokens
- Automatic Collection of Interest

## Tokenization of Debt

As an example, let’s say a borrower in Kansas brings a diamond necklace to their local pawn shop. The pawnbroker assesses the resale value of the necklace at $2,000 and issues a $500 loan at a 10% monthly interest rate.

Using DiversiFi, the pawnbroker issues a debt token based on the underlying collateralized loan. The repayment terms are specified by the pawnbroker when creating the debt token. In this case, the pawnbroker wants to replenish their pool of lending capital while locking in a profit of 5% per month, so they issue a debt token that entitles the token holder to monthly payments of 25 Dai until the 500 Dai principal is repaid.<sup>4</sup> The token includes a link to off-chain metadata about the pawnbroker and the underlying collateralized loan.

A DiversiFi lender in Switzerland decides to buy the debt token after reviewing the loan terms and metadata. They send the pawnbroker 500 Dai, which the pawnbroker sells for $500 to replenish their lending capital.

One month later, the original borrower extends the loan and pays the pawnbroker $50 in interest. The pawnbroker buys 25 Dai and pays the DiversiFi token holder. The month after, the borrower reclaims the necklace from the pawnbroker by paying the $500 principal plus an additional $50 in interest. The pawnbroker buys 525 Dai and repays the principal and second month of interest to the token holder. As part of the settlement process, the debt token is automatically burned.<sup>5</sup>

The pawnbroker has earned $50 in interest and did not have to deplete their lending capital for two months. The DiversiFi token holder has earned 50 Dai in interest.

## Debt Reselling

DiversiFi’s debt marketplace could allow permissionless reselling of the debt token. Tweaking the example earlier, the lender in Switzerland buys the debt token for 500 Dai and immediately offers it for resale at 510 Dai. A lender in Osaka buys the token for 510 Dai the next day. The Switzerland lender has made a one-day profit of 10 Dai and the Osaka lender is entitled to interest payments from the pawnbroker until the principal has been repaid in full. The pawnbroker doesn’t need to concern themselves with who holds the debt token at any given time because they make their payments to a smart contract that routes the money where it is supposed to go.

## DiversiFi Buyer of Last Resort

There should be numerous safeguards to protect DiversiFi lenders from losing money on their investments. Pawnbrokers would need to be approved by the DiversiFi DAO in order to issue debt tokens in the first place, and their overall debt burden and repayment history would be immutably and publicly stored on the blockchain for lenders to review before buying their tokens.

However, there will always be a chance that, for whatever reason, the pawnbroker defaults on their payments to a DiversiFi token holder. In that case, the token holder may choose to try to personally collect on the debt through the court system or, more likely, resell the debt to someone in a better position to collect. The DiversiFi DAO itself could fund a smart contract, through transaction fees or otherwise, that acts as a buyer of last resort. Token holders could always sell their debt tokens to the buyer of last resort contract for a percentage of the principal set by the DiversiFi DAO governance process. This sets a floor on the amount of money a DiversiFi token holder may lose on a given investment.

A consequence of this safeguard is that there must always be enough money available to the buyer of last resort contract to cover the guaranteed portion of all of the loans in the system. For example, if the guaranteed percentage is 50%, and there is 1,000,000 Dai in the buyer of last resort contract, the total principal value of all outstanding debt tokens could not exceed 2,000,000 Dai.<sup>6</sup>

## DiversiFi DAO

There could be a DiversiFi DAO that manages the marketplace and smart contract ecosystem. The holders of DAO governance tokens could vote on proposals to modify variables in the smart contracts, approve and remove pawnbrokers, make payments to developers and other contractors, distribute profits from the DiversiFi system to governance token holders, and upgrade smart contracts. Votes could be weighted by the number of governance tokens held by the voter.

Governance token holders are incentivized to onboard pawnbrokers who will reliably pay their debts, because tokens in default can always be sold to DiversiFi’s buyer of last resort contract, leaving the DAO itself to try to collect the debt. The DAO’s ability to collect debts owed by a pawnbroker should be taken into account before approving a pawnbroker to sell debt tokens through DiversiFi. However, the DAO need not be the only buyer of distressed debt tokens, and other entities that believe they can efficiently collect on the debt may offer to buy the token at a rate higher than what is guaranteed by the buyer of last resort contract. Pawnbrokers who default on their debts may also be removed by DAO governance or automatically after a certain threshold.

On the other hand, governance token holders are also incentivized to encourage as many transactions as possible in order to increase transaction fees and profit sharing. In order to accomplish this, the DAO may vote to hire contractors to develop web and mobile interfaces, improve DiversiFi’s smart contracts, provide outreach to pawnbrokers and lenders, evaluate and propose new pawnbrokers, and assist in legal and regulatory compliance matters.

## Pawnbroker Onboarding and Debt Collection

DAOs have almost no track record of reaching out into the physical world and taking action. I'm not aware of any cases of a DAO filing a lawsuit, for instance. However, with the DiversiFi DAO's buyer of last resort contract autonomously buying up distressed debt tokens, the DAO would need to find an efficient way to collect on those debts through the legal system. This raises some very interesting administrative and incorporation questions.

However, it would be best to avoid defaults if at all possible, especially in the formative stages of DiversiFi. Pawnbrokers should be carefully evaluated before being approved to issue debt tokens. In addition, there might be limits on how much debt a single pawnbroker can issue at one time, and any debt defaults should trigger consequences ranging from a reduction of the pawnbrokers' debt limit to expulsion from the system.

## Next Steps

Write some code.

---

<sup>1</sup> The Maker Protocol can be thought of as a decentralized, semi-autonomous pawn shop on Ethereum for certain digital assets. Borrowers lock up collateral in a smart contract, value is assessed through price oracles, interest is compounded automatically, and if the borrower’s collateralization ratio drops below a certain point, the collateral is automatically sold at auction until the ratio is back above the minimum.

<sup>2</sup> https://blog.pawnguru.com/pawn-shops

<sup>3</sup> Or Maker Protocol loans that occasionally have to raise interest rates to protect the soft peg of the Dai to the U.S. dollar.

<sup>4</sup> Dai is used as an example, but the debt tokens could be priced in any kind of stablecoin.

<sup>5</sup> The fiat-to-crypto conversions could be handled by third-party loan management software that provides money services under the hood.

<sup>6</sup> These are just examples. The actual ratio would be set by DAO governance and could be adjusted up or down depending on the real-world performance of the system.
