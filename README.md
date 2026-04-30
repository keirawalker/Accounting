**Accounting Project Overview**    
Algorithm to build Cash Flow Statements

**General Framework**  

```text
EDGAR 10-K
   ↓
Income Statement ─┐
                  ├── Feature Engine → Model → Predicted Cash Flow
Balance Sheet ────┘

EDGAR Cash Flow (label only, NOT input)
                         ↓
                 Evaluation layer only
```

**Data**  
Edgar SEC 10K's from Accenture PLC 2015-2025  
Only using Income Statement & Balance sheets

**Features**  
Income Statement  
Balance Sheet

**Model**  
Gradient Boosted Decision Trees (GBDT)
