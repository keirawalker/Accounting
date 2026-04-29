# Accounting
Algorithm to build Cash Flow Statements

**General Framework**
EDGAR 10-K
   ↓
Income Statement ─┐
                  ├── Feature Engine → Model → Predicted Cash Flow
Balance Sheet ────┘

**Data**
Edgar SEC 10K's from Accenture PLC 2015-2025
Only using Income Statement & Balance sheets

**Features**
Income Statement
Balance Sheet

**Model**
Gradient Boosted Decision Trees (GBDT)
