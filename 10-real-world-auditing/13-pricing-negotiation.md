# Pricing and Negotiation for Smart Contract Audits

## Simple Definition
Pricing your audit services correctly is one of the hardest skills to master. Charge too little, and you burn out while attracting low-quality clients. Charge too much, and you lose deals to competitors. This file teaches you how to price, negotiate, and position yourself in the market.

## The Best Analogy
Think of audit pricing like a **freelance consultant's rate card**. A junior consultant charges $50/hour and gets small projects. A senior consultant with a track record charges $500/hour and gets Fortune 500 clients. The difference isn't just skill—it's reputation, specialization, and perceived value.

## Audit Pricing Models

```text
1. Per-Line-of-Code (LOC):
   - Range: $50 - $150 per line of Solidity
   - Example: 1,000 LOC × $100 = $100,000
   - Best for: Well-scoped, standard contracts
   - Pros: Easy to estimate
   - Cons: Punishes efficient coders (less code = less pay)

2. Per-Contract:
   - Range: $5,000 - $50,000 per contract
   - Example: 5 contracts × $15,000 = $75,000
   - Best for: Modular architectures
   - Pros: Simple to quote
   - Cons: Doesn't account for complexity differences

3. Time-and-Materials (T&M):
   - Range: $150 - $400 per hour
   - Example: 80 hours × $250 = $20,000
   - Best for: Unclear scope or ongoing engagements
   - Pros: Fair for both parties
   - Cons: Hard to estimate total cost upfront

4. Fixed-Price (Most Common):
   - Range: $10,000 - $150,000+ per audit
   - Example: $40,000 for a 2-week audit
   - Best for: Well-defined scopes
   - Pros: Predictable for both parties
   - Cons: Risk of scope creep
```

## Market Rates by Auditor Level (2024)

```text
Junior Auditor (0-1 year experience):
- Solo audit: $5,000 - $15,000
- Code4rena/Sherlock earnings: $500 - $5,000 per contest
- Hourly rate: $50 - $100

Mid-Level Auditor (1-3 years):
- Solo audit: $15,000 - $40,000
- Code4rena/Sherlock earnings: $5,000 - $20,000 per contest
- Hourly rate: $100 - $200

Senior Auditor (3-5 years):
- Solo audit: $40,000 - $100,000
- Code4rena/Sherlock earnings: $20,000 - $100,000 per contest
- Hourly rate: $200 - $400

Top-Tier Auditor / Firm Partner (5+ years):
- Solo audit: $100,000 - $300,000+
- Bug bounty: $100,000 - $1,000,000+ per Critical find
- Hourly rate: $400 - $1,000+
```

## How to Calculate Your Rate

```text
Step 1: Determine Your Desired Annual Income
   Example: $100,000/year

Step 2: Estimate Billable Days
   - 260 working days/year
   - Subtract vacation (20), sick days (5), admin/marketing (30)
   - Billable days: ~200

Step 3: Calculate Daily Rate
   $100,000 / 200 days = $500/day

Step 4: Convert to Project Pricing
   - Typical audit: 2-4 weeks (10-20 billable days)
   - Project rate: $5,000 - $10,000 (junior) to $50,000 - $100,000 (senior)

Step 5: Add Buffer (20-30%)
   - For scope creep, revisions, and unpaid admin time
   - Final rate: $6,000 - $130,000 per project
```

## Negotiation Strategies

```text
1. Anchor High:
   - Start with your ideal price, not your minimum.
   - Example: Quote $50,000 when you'd accept $35,000.
   - Gives room for negotiation without going below your floor.

2. Justify with Value, Not Time:
   - Bad: "This will take me 2 weeks, so $20,000."
   - Good: "This audit protects your $5M TVL from potential exploits. My fee is $40,000—less than 1% of what you could lose."

3. Offer Tiered Packages:
   - Basic: Code review + report ($20,000)
   - Standard: Above + remediation review ($30,000)
   - Premium: Above + 3 months of support ($45,000)

4. Use "If-Then" Concessions:
   - "If you can pay 100% upfront, I can offer a 10% discount."
   - Never give concessions without getting something in return.

5. Know Your Walk-Away Point:
   - Define your minimum acceptable rate before the call.
   - If the client won't meet it, politely decline.
   - Desperation kills negotiation power.
```

## Example: Pricing Email to a Client

```text
Subject: Audit Proposal for [Protocol Name]

Hi [Client Name],

Thank you for considering me for your audit. Based on the scope (~1,500 LOC across 5 contracts), I propose the following:

**Standard Audit Package - $45,000**
- Full manual review of all in-scope contracts
- Automated analysis (Slither, Foundry fuzzing)
- Detailed report with severity ratings and PoCs
- One round of remediation review
- Delivery in 14 business days

**Optional Add-ons:**
- Extended remediation support (3 months): +$10,000
- Post-deployment monitoring (1 month): +$5,000

**Payment Terms:**
- 50% ($22,500) upon signing
- 50% ($22,500) upon final report delivery
- Payment in USDC or wire transfer

I'm available to start on [Date]. Let me know if you'd like to discuss the scope or pricing further.

Best regards,
[Your Name]
```

## Key Takeaways
- **Know Your Worth:** Don't undercharge just to get clients. It attracts bad clients and burns you out.
- **Value-Based Pricing:** Price based on the value you provide (protecting millions), not the hours you work.
- **Get 50% Upfront:** Never start work without a deposit.
- **Scope Creep is Real:** Define exactly what's included. Charge extra for additional work.
- **Negotiate from Strength:** Have multiple clients in your pipeline so you're not desperate for any single deal.
- **Raise Rates Regularly:** Increase your rates by 20-30% every 6-12 months as your reputation grows.
