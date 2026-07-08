# ApartmentCorp Cost Segregation Portfolio
**CSSI Report Series #107752 | As of December 31, 2024**

Engineering-based cost segregation studies for 10 residential rental properties across 6 states. All 10 properties now include full Form 3115 documentation with Before/After depreciation reconciliation.

## Repository Structure

```
cost-segregation-project/
├── workbooks/
│   ├── 3115/          # Full 3115 workbooks with Before/After dep reconciliation (10 properties)
│   └── cost-seg/      # Cost segregation only workbooks (superseded by 3115 versions)
├── bundles/
│   └── CSSI_All_Workbooks.zip
└── portal/
    └── CSSI_Portal.html  # Self-contained web portal (all 10 x 3115 workbooks embedded)
```

## Properties

481(a) values below are computed uniformly as Before − After end depreciation from each workbook's Summary sheet (negative = additional deductions in year of change).

| Property | Entity | Location | Type | 481(a) Adj |
|---|---|---|---|---|
| Marrero 3 | LP | Marrero, LA | 3115 ✓ | ($52,330) |
| Grace Townhomes | Housing LLC | Multiple, LA | 3115 ✓ | ($205,583) |
| Coral Village | Housing LP | Cape Coral, FL | 3115 ✓ | ($265,512) |
| Granite Ridge | Housing LP | Stockton, CA | 3115 ✓ | ($368,478) |
| Grove Park Terrace | Housing LP | Waxahachie, TX | 3115 ✓ | ($257,874) |
| Fairfax Senior | Partners LP | Los Angeles, CA | 3115 ✓ | ($144,998) |
| St. Charles Housing | LP | Lake Charles, LA | 3115 ✓ | ($1,762,893) |
| River Garden Estates | Housing LP | Sacramento, CA | 3115 ✓ | $34,581 |
| Macedonia Apartments | LLC | Panama City, FL | 3115 ✓ | ($220,444) |
| Silver Spring Terrace | Silver Springs Housing, LP | Hickory, NC | 3115 ✓ | ($427,882) |
| **Portfolio Net** | | | | **($3,671,413)** |

## Portal
Open `portal/CSSI_Portal.html` in any browser for a full portfolio dashboard with live workbook preview, sheet navigation, and one-click downloads.

## Notes
- All workbooks built with live SUM formulas (zero hardcoded totals)
- 3115 workbooks include full Before/After depreciation reconciliation tables
- Prepared by Cost Segregation Services LLC (CSSI)

## ⚠️ Silver Spring Terrace — CSSI PDF discrepancy
The CSSI Form 3115 for Silver Springs Housing, LP (#107752-39) states a total 481(a) adjustment of **($259,107.40)** on its summary page and in the Part IV/Q26 narrative. However, that figure equals only the **first 10 of the 20 line items** listed on the same summary page. The sum of all 20 line items — each of which ties exactly to its own detailed Before/After schedule in the PDF — is **($427,882.48)**. This should be confirmed with CSSI and the CPA before filing. The workbook uses live formulas and reflects the full 20-item total, with a note on the Summary sheet.
