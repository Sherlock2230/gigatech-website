# Declined Markets

Markets Granite has evaluated, could technically serve, and has deliberately chosen not to enter — with reasoning. This document exists because knowing what we won't do is part of what makes a payments company licensable. Reviewers, banking partners, and investors should read this as a statement of scope discipline, not a list of missed opportunities.

---

## 1. Retail Forex / CFD Broker Funding

**Status: Declined. Revisit only if Zimbabwe introduces a domestic retail OTC forex licensing regime.**

### The observed problem

Zimbabwean retail traders funding offshore broker accounts (Deriv, Exness, and similar) face severe payment friction:

- Zimbabwe-issued cards (including EcoCash Mastercard) are unreliable for broker deposits and frequently cannot receive withdrawals back.
- The gap is filled by informal payment agent networks — individuals coordinating over WhatsApp who accept EcoCash/Zipit/cash and credit broker accounts, charging roughly 5–10% per round trip.
- Crypto (USDT) has become the de facto workaround rail for traders who can navigate it.

This is a real market with real willingness to pay. The agent networks are, structurally, an unlicensed miniature of what Granite builds properly: local-value-in, platform-credit-out, trust-based settlement.

### Why we decline it

**1. Exchange control exposure.** The brokers in question operate under offshore entities (Seychelles, Mauritius) with no RBZ authorisation. Facilitating retail capital outflows to unlicensed offshore CFD platforms sits at the centre of what exchange control regulation exists to prevent. A platform that does this cannot simultaneously present itself to the RBZ Regulatory Sandbox as licensed B2B payment infrastructure. The two positions are mutually exclusive, and we choose the license.

**2. Banking partnership contamination.** Granite's negotiating position with a partner bank rests on bringing stable float and clean, auditable B2B flows. Forex/CFD-adjacent flows are a globally recognised de-risking category — the flows compliance departments are specifically trained to flag. Any broker-funding volume in Granite's accounts would degrade the banking relationship that the entire platform depends on.

**3. Wrong customer, wrong economics.** Retail trader deposits are consumer flows: small tickets, high fraud exposure, chargeback-prone, emotionally driven. This is the crowded consumer segment Granite's chokepoint thesis deliberately avoids. The informal agents' 5–10% margins are only achievable *because* they are unlicensed and carry no compliance cost. A licensed operator inherits KYC, monitoring, and reporting obligations that make this segment unservable at those margins. Their business model is unavailable to us by construction — this is a structural fact, not a pricing problem.

### What we take from it

The trader-funding failure is additional evidence for Granite's core cross-border thesis: wherever Zimbabwe's licensed payment rails fail, informal agent networks scale up to fill the gap — in B2B supplier payments (see CROSS_BORDER_STRATEGY.md), in car imports, and now observably in retail brokerage. The pattern is consistent. Granite's response is also consistent: build the licensed, KYC-trailed version of the capability for **businesses paying businesses**, and let netting reduce nostro dependence. Same plumbing, correct customer.

### Revisit trigger

If Zimbabwe establishes a domestic licensing regime for retail OTC forex brokers (comparable to Kenya's CMA regime, which is what enables clean M-Pesa/broker integration), locally licensed brokers would become legitimate B2B counterparties — a business paying a business, inside the regulatory perimeter. At that point, broker treasury and settlement services could be evaluated as a standard B2B vertical. Until that regime exists, this market remains closed to Granite regardless of demand.

---

## Template for future entries

Each declined market entry should answer four questions:

1. **The observed problem** — what real demand did we see, and how is it currently served?
2. **Why we decline it** — regulatory, relationship, and economic reasoning, in that order.
3. **What we take from it** — what the observation teaches us about our actual market.
4. **Revisit trigger** — the specific, external condition under which the decision would be re-evaluated. "Never" is an acceptable answer; vague answers are not.
