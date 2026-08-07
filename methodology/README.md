# Methodology

This project compares publicly disclosed investment transactions associated with Donald Trump’s investment accounts against major U.S. policy decisions, presidential announcements, regulatory actions, and government-backed corporate events during 2025–2026.

## Research Question

The central question is:

**Do investment transactions systematically occur before market-moving U.S. policy decisions or presidential announcements?**

This project does not assume wrongdoing. It is designed to test whether meaningful temporal relationships appear in publicly available data.

## Unit of Analysis

Each record links:

- Transaction date
- Company or asset
- Buy / Sell
- Reported transaction amount range
- Related policy or presidential event
- Event date
- Number of days between the transaction and the event
- Alternative explanation
- Evidence status
- Source

## Date Calculation

The basic calculation is:

**Event Date − Trade Date**

A positive number means the transaction occurred before the policy or presidential event.

A value of zero means both occurred on the same calendar day.

## Important Limitation on Same-Day Events

OGE disclosures generally provide transaction dates, but not precise execution times.

Therefore, when a transaction and a policy announcement occur on the same day, this project does not assume that the transaction occurred before the announcement.

Same-day cases are recorded separately.

## Transaction Amounts

OGE disclosures typically report transaction values as ranges rather than exact amounts.

For example:

- $15,001–$50,000
- $100,001–$250,000
- $1,000,001–$5,000,000

Accordingly, this dataset does not treat the upper or lower bound as the exact transaction value.

## Evidence Hierarchy

Sources are prioritized in the following order:

1. U.S. Office of Government Ethics filings
2. Official White House, government agency, or company announcements
3. Major reporting organizations such as Reuters, Associated Press, Wall Street Journal, and ABC News
4. Secondary commentary used only as a research lead

## Conflict of Interest vs. Illegal Trading

A temporal relationship between a trade and a policy decision does not by itself establish insider trading or any other illegal conduct.

A legal case would require evidence concerning matters such as:

- Material nonpublic information
- Who possessed that information
- Whether the information was communicated
- Whether the investment manager had access to it
- Whether the information influenced the transaction

This dataset does not attempt to make legal conclusions.

## Alternative Explanations

Each potentially significant case should also include plausible non-illegal explanations, including:

- Automated portfolio rebalancing
- Direct indexing
- Sector allocation
- Tax-loss harvesting
- Public information already available before the trade
- Broad market purchases
- Mixed buying and selling across different accounts

## Anti-Cherry-Picking Rule

The project will not include only transactions that appear suspicious.

It will also record:

- Trades occurring after policy announcements
- Cases with no clear policy connection
- Mixed buy and sell activity
- Transactions that contradict the original hypothesis
- Cases where public information existed before the trade

These counterexamples are important to the integrity of the analysis.

## Evidence Status

Records may be classified as:

- **Reported** — identified through credible reporting
- **Verified** — confirmed directly in an OGE filing or other primary source
- **Needs Review** — potentially relevant but incomplete
- **Excluded** — insufficient connection or evidence

## Scope

Current research period:

**2025–2026**

The dataset will be updated as additional OGE filings, policy records, and verified transaction data become available.

## Research Principle

The objective is not to prove a predetermined conclusion.

The objective is to make the relationship between investment activity and public policy observable, reproducible, and open to independent review.
