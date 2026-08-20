# Partner Credit Limit Assessment — B2B Book

Built for the **Senior Commercial Credit Risk Analyst** role at Expedia Group (B2B Finance Credit team).

## What it does

An interactive credit memo tool that mirrors the core workflow of the role: pick one of five synthetic B2B travel partners (an airline consolidator, a corporate travel management company, an online reseller, an offline agent network, and a financial-institution loyalty partner) and see, transparently, how a recommended credit limit gets built —

- **Financial strength** from current ratio and debt/equity
- **Payment behaviour** from days sales outstanding against Expedia's real 30-day standard receivable terms, plus late-settlement history
- **Country risk** as a simple tier adjustment

These roll up into a composite score, a risk tier (A–D), a recommended credit limit sized against the partner's monthly settlement volume, and a credit insurance coverage check that flags any uncovered exposure gap — directly reflecting the JD's asks around credit limit recommendations, multi-currency exposure, and managing insurance coverage gaps. A portfolio panel then aggregates the five partners into total exposure, weighted insurance coverage, currency mix, and tier distribution.

## Why it was built

Two things this role asks for stood out: analysing real financial statements to size credit exposure, and managing risk across a genuinely international, multi-currency partner book. Rather than build a generic dashboard, I wanted to show the actual mechanics of a credit decision — the formula, not just the output — and ground it in something real rather than invented. The three context figures at the top (B2B segment revenue, group receivables, and the allowance for credit losses) are pulled from Expedia Group's actual FY2025 results: receivables grew roughly 30% year-over-year against 8% group revenue growth, which is the kind of divergence a credit team would want to understand as the B2B book scales. Everything below that line — partners, financials, scores — is synthetic.

## Data disclaimer

All partner names, financials, and portfolio figures are entirely synthetic and built for demonstration purposes only. No real partner, counterparty, or confidential Expedia data is used or referenced. The three FY2025 figures in the context strip are Expedia Group's own publicly reported results (announced February 12, 2026), cited for framing only. The scoring weights, limit multiples, and insurance coverage assumptions are illustrative and do not represent Expedia's actual credit policy.

## Built with AI

This tool was designed and built using Claude (Anthropic), with the underlying credit scoring logic, portfolio structure, and real financial context researched and directed by me. I'm sharing it as a transparent example of how I use AI as a working tool — not to replace financial judgment, but to move faster from idea to a working, testable model.
