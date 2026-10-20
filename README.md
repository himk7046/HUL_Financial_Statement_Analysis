
# Hindustan Unilever (HUL): Five-Year Financial Statement Analysis

A formula-driven Excel model of **Hindustan Unilever Limited** (one of India's largest FMCG companies) for
FY2020-21 to FY2024-25. It turns the income statement and balance sheet into comparative, common-size and
trend analysis, ratio analysis, DuPont, Altman Z-score and Piotroski F-score, then ends with advice for five
stakeholder groups.

*MBA coursework: Accounting for Managers project, Business Analytics and Intelligence (Semester 1).*

## Key results

| Metric | FY2020-21 | FY2024-25 | Reading |
|---|---:|---:|---|
| Revenue from operations (₹ crore) | 45,996 | 61,469 | 7.5% a year, but almost all of it before FY24 |
| Profit after tax (₹ crore) | 7,954 | 10,644 | 7.6% a year |
| Net profit margin | 17.3% | 17.3% | Stayed between 16.7% and 17.3% |
| Return on equity (year-end) | 16.8% | 21.7% | Up, with a change in what drives it |
| Earnings per share (₹) | 33.85 | 45.29 | |
| Altman Z-score | 3.59 | 3.34 | Safe zone every year; peaked at 3.87 in FY23 |
| Piotroski F-score (of 9) | 6 | 5 | Peaked at 7 in FY22 |

## What the analysis found

### 1. Growth stalled after FY23, while profit held up
Revenue rose 11.3% in FY22 and 15.5% in FY23, then only 2.2% in FY24 and 1.7% in FY25. Net profit margin stayed
in a 16.7% to 17.3% band throughout, so profit growth followed revenue growth.



### 2. ROE improved, but the drivers changed
DuPont splits ROE into margin × asset turnover × equity multiplier. Margin was flat. ROE first rose because
assets worked harder (turnover 0.68 to 0.82 by FY23); in FY24-25 it rose because the equity multiplier climbed from
1.43 to 1.59. A rise driven by leverage is lower quality than one driven by efficiency.



### 3. Bankruptcy risk is very low but trending the wrong way
The Altman Z-score stays above the safe-zone threshold in all five years. It fell from 3.87 (FY23) to 3.34 (FY25)
as total liabilities grew from ₹21,604 cr to ₹29,160 cr and equity fell.



### 4. Equity funds a smaller share of the balance sheet
Equity went from 69.6% to 62.8% of total assets and current liabilities from 15.9% to 20.0%. This is **not**
borrowing: the balance sheet has no borrowings line. The growth is in tax liabilities (a new ₹1,887 cr current tax
liability in FY25), trade payables and leases. Equity fell ₹1,820 cr in FY25 despite ₹10,644 cr of profit, which
implies distributions and other reserve movements larger than profit; the workbook does not itemise them.



### 5. Liquidity weakened in FY25
Recalculated from the year-end statements, the current ratio moved from 1.64 (FY24) to 1.33 (FY25). The workbook's
ratio table shows the two years the other way round (see [Known issues](#known-issues-in-the-workbook)).

## Recommendations by stakeholder

The workbook closes with a risk table. This is a classroom exercise, **not investment advice**.

| Stakeholder | Conclusion | Risk |
|---|---|---|
| Current shareholder | Keep shares, don't buy more now | Medium |
| Prospective investor | Wait for better signs | Medium |
| Supplier | Safe to supply, watch payment times | Low |
| Bank | Lend with confidence | Very low |
| Job seeker | Good company to join | Low |
| Employee | Job is safe, keep upskilling | Low |

## What is in the workbook

[`HUL_Financial_Statement_Analysis.xlsx`](HUL_Financial_Statement_Analysis.xlsx) has 12 sheets and 609 formula
cells. Open it in Excel or LibreOffice.

| Sheet | Purpose |
|---|---|
| Group, Intro | Project details and company background |
| Vertical financial statements | **Source of truth**: income statement and balance sheet, five years |
| comparative statements | FY24 vs FY25 absolute and % change |
| common size statements | Each line as % of total assets (balance sheet) or total income (P&L) |
| trend statements | Five-year index, FY2020-21 = 100 |
| Ratio analysis | Eleven liquidity, leverage, profitability and turnover ratios |
| DuPont Analysis | Three-step ROE decomposition with commentary |
| Z-Score, F-Score | Altman bankruptcy-risk score and Piotroski financial-strength score |
| Assumptions | Accounting assumptions behind the analysis |
| Decisions and Suggestions | Advice for investors, suppliers, banks and management |

## Skills this project shows

- Reading and restructuring financial statements (comparative, common-size and trend analysis)
- Ratio analysis, DuPont decomposition, Altman Z-score and Piotroski F-score in Excel
- Checking figures against their source and spotting inconsistencies
- Turning numbers into plain-language conclusions and stakeholder recommendations

## Known issues in the workbook

Before publishing, the workbook was checked against its own source statements and clear typing errors were
corrected. These items need an analyst's judgement and were left unchanged:

- **Ratio analysis sheet:** FY2023-24 and FY2024-25 look swapped for four ratios (current ratio, ROE, receivables
  turnover, net capital turnover). The commentary on that sheet is built on the swapped values.
- **Altman zones:** the sheet's cut-offs belong to the private-firm variant while the weights are the original model.
  The conclusion (safe zone every year) holds either way.
- **Wording:** "taking on more loans" is not supported by the balance sheet (there are no borrowings); "higher
  liabilities" is accurate.
- **Source citation:** exact annual-report page references, and whether the statements are standalone or
  consolidated, still need to be added.

## Limitations

- One company over five years, with no peer benchmark, so ratios are judged against HUL's own history.
- The Z-score uses book equity in place of market value, and *other equity* in place of retained earnings.
- Operating cash flows and the ratio table are typed in by hand from the annual reports.
- FY2020-21 F-score is not like-for-like because of the April 2020 merger with GSK Consumer Healthcare.

## Project by

**Mukesh Kumar**, MBA - BAI, NFSU GANDHINAGAR

## Sources and attribution

- **Data:** Hindustan Unilever Limited annual reports, FY2020-21 to FY2024-25 (exact page references are an open item).
  The FY2024-25 profit after tax was spot-checked against [HUL's published result](https://www.hul.co.in/news/press-releases/2025/financial-results-for-march-quarter-and-financial-year-2025/).
- **Images:** the Intro sheet embeds excerpts from HUL's *Integrated Annual Report 2022-23* and the Unilever logo.
  Third-party data, images and trademarks belong to their owners and are included for educational illustration only.
