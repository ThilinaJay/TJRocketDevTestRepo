
# Rocket UniVerse Monster Sample Project

⚠️ **This is a completely dummy project** built for **AI code understanding, indexing, and analysis**.

## Purpose
- Stress-test AI understanding of legacy UniVerse BASIC
- Large procedural files (800–1200 LOC)
- Repetitive, legacy enterprise-style logic
- Mixed responsibilities and poor abstractions (by design)

## Domains Covered
- Sales Order Management
- Pricing & Discount Rules
- User & Role Validation
- Product Catalog
- Reporting

## Business Rules (Fake)
- VIP customers receive stacked discounts
- Orders above certain thresholds trigger extra pricing logic
- Pricing rules are duplicated across programs intentionally
- Product prices may be overridden by hardcoded rules
- Users are validated procedurally, not centrally

## Structure
```
rocket-universe-monster-project/
├── README.md
├── SALES.ORDER.MONSTER
├── PRICING.MONSTER
└── COMMON.UTILS
```

This repo is **not intended to run in production**.
