# Precedent Transaction Analysis.xlsx

Formula cells render as the value, then `=formula`. Percent-formatted cells are shown as %.


## Benchmarking & Valuation

| # | A | B | C | D | E | F | G | H | I | J | K |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Benchmarking |  |  |  |  |  |  |  |  |  |  |
| 2 | Food & Beverage Sector |  |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |  |
| 4 |  |  |  |  |  |  |  | Enterprise Value / |  |  |  |
| 5 | Date Announced | Acquirer | Target | Transaction Type | Purchase Consideration | Equity Value | Enterprise Value | LTM Sales | LTM EBITDA | LTM EBIT | LTM EBITDA Margin |
| 6 | 2021-11-25 00:00:00 | Universal Robina Corp. | Munchy Food Industries | Public Acquirer / Private Target | Cash | ₱22,899.55 | ₱22,899.55 | 4.6 | 17.7 | 34 | 18.0000% |
| 7 | 2021-03-24 00:00:00 | Century Pacific Food, Inc. | Pacific Meat Company, Inc. | Public Acquirer / Private Target | Cash | ₱649.92 | ₱649.92 | 0.6 | 4.3 | 9.3 | 11.0000% |
| 8 | 2021-12-24 00:00:00 | Century Pacific Food, Inc. | Ligo | Public Acquirer / Private Asset Carve-out | Cash | N / A | ₱1,719.66 | 1.1 | 5.7 | 8.5 | 15.9000% |
| 9 | Mean |  |  |  |  |  |  | 2.1<br>`=(H6+H7+H8)/3` | 9.233333333<br>`=(I6+I7+I8)/3` | 17.26666667<br>`=(J6+J7+J8)/3` | 14.9667%<br>`=(K6+K7+K8)/3` |
| 10 | Median |  |  |  |  |  |  | 1.1<br>`=H8` | 5.7<br>`=I8` | 9.3<br>`=J7` | 15.9000%<br>`=K8` |
| 11 | High |  |  |  |  |  |  | 4.6<br>`=H6` | 17.7<br>`=I6` | 34<br>`=J6` | 18.0000%<br>`=K6` |
| 12 | Low |  |  |  |  |  |  | 0.6<br>`=H7` | 4.3<br>`=I7` | 8.5<br>`=J8` | 11.0000%<br>`=K7` |
| 13 |  |  |  |  |  |  |  |  |  |  |  |
| 14 | Implied Valuation Range |  |  |  |  |  |  |  |  |  |  |
| 15 | Monde Nissin Corporation (MONDE) |  |  |  |  |  |  |  |  |  |  |
| 16 | (₱ in millions, LTM 6/30/2026) |  |  |  |  |  |  |  |  |  |  |
| 17 |  |  |  |  |  |  |  |  |  |  |  |
| 18 | EBITDA | Metric | Multiple Range | Implied Enterprise Value |  |  |  |  |  |  |  |
| 19 | LTM | 16147.9 | 8.5x - 9.5x | ₱137,257.15 - ₱153,405.05 |  |  |  |  |  |  |  |

## Target Company

| # | A | B | C | D | E | F | G | H | I | J | K | L | M | N |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Monde Nissin Corporation (MONDE) |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 2 | Target Company |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 4 | General Information |  |  | Reported Income Statement |  |  |  |  |  |  |  | Balance Sheet Data |  |  |
| 5 | Company Name | Monde Nissin Corporation |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  | (₱ in millions) |  |  |
| 6 | Ticker | MONDE |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  | 2025A | Q2 2026 |
| 7 | Stock Exchange | Philippine Stock Exchange (PSE) |  | Sales | 80169.5 | 83120.1 | 86483 | 41457.2 | 44295.6 | 89321.4<br>`=G7+I7-H7` |  | Cash and Cash Equivalents | 15398.3 | 14379.9 |
| 8 | Fiscal Year Ending | 2026-12-31 00:00:00 |  | COGS (incl. D&A) | 55441.7 | 54430.4 | 57664.6 | 27661.2 | 28706.8 | 58710.2<br>`=G8+I8-H8` |  | Accounts Receivable | 8401 | 6875.1 |
| 9 | Marginal Tax Rate | 25.0000% |  | Gross Profit | 24727.8<br>`=E7-E8` | 28689.7<br>`=F7-F8` | 28818.4<br>`=G7-G8` | 13796<br>`=H7-H8` | 15588.8<br>`=I7-I8` | 30611.2<br>`=J7-J8` |  | Inventories | 8971.7 | 9309.3 |
| 10 |  |  |  | SG&A | 28084.5 | 22806.2 | 16548.9 | 7644.9 | 8625.3 | 17529.3<br>`=G10+I10-H10` |  | Prepaids and Other Current Assets | 3566 | 3846.4 |
| 11 | Selected Market Data |  |  | Other Expense / (Income) | -1742 | 2278.6 | 639.8 | 155.9 | -395.2 | 88.7<br>`=G11+I11-H11` |  | Total Current Assets | 36337<br>`=SUM(M7:M10)` | 34410.7<br>`=SUM(N7:N10)` |
| 12 | (In ₱ millions, except per share data. Stock Data is as of August 14, 2026.) |  |  | EBIT | -1614.7<br>`=E9-E10-E11` | 3604.9<br>`=F9-F10-F11` | 11629.7<br>`=G9-G10-G11` | 5995.2<br>`=H9-H10-H11` | 7358.7<br>`=I9-I10-I11` | 12993.2<br>`=J9-J10-J11` |  |  |  |  |
| 13 | Current Price | 7.12 |  | Net Finance Costs / (Income) | 232.4 | 93.5 | -37.2 | 26.4 | -91.3 | -154.9<br>`=G13+I13-H13` |  | Property, Plant and Equipment, net | 27309.4 | 27611.9 |
| 14 | % of 52-week High | 94.1799%<br>`=B13/B15` |  | Pre-tax Income | -1847.1<br>`=E12-E13` | 3511.4<br>`=F12-F13` | 11666.9<br>`=G12-G13` | 5968.8<br>`=H12-H13` | 7450<br>`=I12-I13` | 13148.1<br>`=J12-J13` |  | Goodwill and Intangible Assets | 6654.8 | 6759 |
| 15 | 52-week High Price | 7.56 |  | Income Taxes | -1220.6 | 3061.9 | 3067.8 | 1553.9 | 1657.7 | 3171.6<br>`=G15+I15-H15` |  | Other Assets | 12663 | 13190.4 |
| 16 | 52-week Low Price | 5.61 |  | Non-controlling Interest | 9.8 | 3.7 | -19 | 3.7 | -35 | -57.7<br>`=G16+I16-H16` |  | Total Assets | 82964.2<br>`=M11+SUM(M13:M15)` | 81972<br>`=N11+SUM(N13:N15)` |
| 17 | Dividend Per Share (MRQ) | 0.24 |  | Net Income | -636.3<br>`=E14-E15-E16` | 445.8<br>`=F14-F15-F16` | 8618.1<br>`=G14-G15-G16` | 4411.2<br>`=H14-H15-H16` | 5827.3<br>`=I14-I15-I16` | 10034.2<br>`=J14-J15-J16` |  |  |  |  |
| 18 | Fully Diluted Shares Outstanding | 17968.61 |  | Effective Tax Rate | 66.1000% | 87.2000% | 26.3000% | 26.0000% | 22.3000% | 24.1000% |  | Accounts Payable & Accrued Liabilities | 12441.4 | 12276 |
| 19 |  |  |  |  |  |  |  |  |  |  |  | Other Current Liabilities | 3612.6 | 965.3 |
| 20 | LTM ROI Ratios |  |  | Weighted Avg. Diluted Shares | 17968.61 | 17968.61 | 17968.61 | 17968.61 | 17968.61 | 17968.61 |  | Total Current Liabilities (excl. debt) | 16054<br>`=M18+M19` | 13241.3<br>`=N18+N19` |
| 21 | Return on Invested Capital | 19.4076%<br>`=(J34*(1-B9))/((M28+N28+M22+N22+M26+N26-M7-N7)/2)` |  | Diluted EPS | -0.03541175416<br>`=E17/E20` | 0.02480993243<br>`=F17/F20` | 0.4796197369<br>`=G17/G20` | 0.2454947823<br>`=H17/H20` | 0.3243044398<br>`=I17/I20` | 0.5584293944<br>`=J17/J20` |  |  |  |  |
| 22 | Return on Equity | 17.2495%<br>`=J46/((M28+N28)/2)` |  |  |  |  |  |  |  |  |  | Total Debt | 5235.7 | 5170.1 |
| 23 | Return on Assets | 12.7052%<br>`=J46/((M16+N16)/2)` |  | Adjusted Income Statement |  |  |  |  |  |  |  | Other Long-Term Liabilities | 1643.3 | 1831.3 |
| 24 | Dividend Yield | 13.4831%<br>`=(B17*4)/B13` |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  | Total Liabilities | 22933<br>`=M20+M22+M23` | 20242.7<br>`=N20+N22+N23` |
| 25 |  |  |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  |  |  |
| 26 | LTM Credit Statistics |  |  | Reported Gross Profit | 24727.8<br>`=E9` | 28689.7<br>`=F9` | 28818.4<br>`=G9` | 13796<br>`=H9` | 15588.8<br>`=I9` | 30611.2<br>`=J9` |  | Non-controlling Interest | 155.6 | 120.6 |
| 27 | Leverage Ratios |  |  | Non-recurring Items in COGS | - | - | - | - | - | - |  | Preferred Stock | - | - |
| 28 | Debt / Total Capitalization | 7.7282%<br>`=N22/(N28+N22+N26)` |  | Adjusted Gross Profit | 24727.8<br>`=E26` | 28689.7<br>`=F26` | 28818.4<br>`=G26` | 13796<br>`=H26` | 15588.8<br>`=I26` | 30611.2<br>`=J26` |  | Shareholder's Equity | 59875.6 | 61608.7 |
| 29 | Total Debt / EBITDA | 0.3201716632<br>`=N22/J38` |  | % margin | 30.8444%<br>`=E28/E7` | 34.5160%<br>`=F28/F7` | 33.3226%<br>`=G28/G7` | 33.2777%<br>`=H28/H7` | 35.1927%<br>`=I28/I7` | 34.2708%<br>`=J28/J7` |  | Total Liabilities and Equity | 82964.2<br>`=M24+M26+M28` | 81972<br>`=N24+N26+N28` |
| 30 | Net Debt / EBITDA (1) | -0.5703404158<br>`=(N22-N7)/J38` |  |  |  |  |  |  |  |  |  |  |  |  |
| 31 |  |  |  | Reported EBIT | -1614.7<br>`=E12` | 3604.9<br>`=F12` | 11629.7<br>`=G12` | 5995.2<br>`=H12` | 7358.7<br>`=I12` | 12993.2<br>`=J12` |  | Balance Check | 0<br>`=M16-M29` | 0<br>`=N16-N29` |
| 32 | Coverage Ratios (2) |  |  | Non-recurring Items in COGS | - | - | - | - | - | - |  |  |  |  |
| 33 | EBITDA / Interest Expense | 41.90994031<br>`=J38/385.3` | (1) | Other Non-recurring Items (Operating) | 13786.7 | 7122.9 | 377.5 | 201.3 | 78 | 254.2<br>`=G33+I33-H33` |  |  |  |  |
| 34 | (EBITDA - CapEx) / Interest Expense | 28.88242928<br>`=(J38-J59)/385.3` |  | Adjusted EBIT | 12172<br>`=E31+E33` | 10727.8<br>`=F31+F33` | 12007.2<br>`=G31+G33` | 6196.5<br>`=H31+H33` | 7436.7<br>`=I31+I33` | 13247.4<br>`=J31+J33` |  |  |  |  |
| 35 | EBIT / Interest Expense | 34.38203997<br>`=J34/385.3` |  | % margin | 15.1828%<br>`=E34/E7` | 12.9064%<br>`=F34/F7` | 13.8839%<br>`=G34/G7` | 14.9467%<br>`=H34/H7` | 16.7888%<br>`=I34/I7` | 14.8312%<br>`=J34/J7` |  |  |  |  |
| 36 | Notes: |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 37 | (1) The resulting net cash reflects MONDE's substantial net cash position of ₱9,209.8M where cash exceeds total debt. |  |  | Depreciation and Amortization (D&A) | 2772 | 2687.9 | 2826.7 | 1370.2 | 1444 | 2900.5<br>`=G37+I37-H37` |  |  |  |  |
| 38 | (2) Calculated using the LTM finance costs as the denominator. |  |  | Adjusted EBITDA | 14944<br>`=E34+E37` | 13415.7<br>`=F34+F37` | 14833.9<br>`=G34+G37` | 7566.7<br>`=H34+H37` | 8880.7<br>`=I34+I37` | 16147.9<br>`=J34+J37` |  |  |  |  |
| 39 |  |  |  | % margin | 18.6405%<br>`=E38/E7` | 16.1401%<br>`=F38/F7` | 17.1524%<br>`=G38/G7` | 18.2518%<br>`=H38/H7` | 20.0487%<br>`=I38/I7` | 18.0784%<br>`=J38/J7` |  |  |  |  |
| 40 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 41 |  |  |  | Reported Net Income | -636.3<br>`=E17` | 445.8<br>`=F17` | 8618.1<br>`=G17` | 4411.2<br>`=H17` | 5827.3<br>`=I17` | 10034.2<br>`=J17` |  |  |  |  |
| 42 |  |  |  | Non-recurring Items in COGS | - | - | - | - | - | - |  |  |  |  |
| 43 |  |  | (1) | Other Non-recurring Items (Operating) | 13786.7<br>`=E33` | 7122.9<br>`=F33` | 377.5<br>`=G33` | 201.3<br>`=H33` | 78<br>`=I33` | 254.2<br>`=J33` |  |  |  |  |
| 44 |  |  | (2) | Non-operating Non-recurring Items | -1471.5 | 2658.8 | 1062.3 | 260.8 | -298.6 | 502.9<br>`=G44+I44-H44` |  |  |  |  |
| 45 |  |  | (3) | Tax Adjustment | -4059.2 | -435.5 | -340 | -139.3 | -112.9 | -313.6<br>`=G45+I45-H45` |  |  |  |  |
| 46 |  |  |  | Adjusted Net Income | 7619.7<br>`=E41+E43+E44+E45` | 9792<br>`=F41+F43+F44+F45` | 9717.9<br>`=G41+G43+G44+G45` | 4734<br>`=H41+H43+H44+H45` | 5493.8<br>`=I41+I43+I44+I45` | 10477.7<br>`=J41+J43+J44+J45` |  |  |  |  |
| 47 |  |  |  | % margin | 9.5045%<br>`=E46/E7` | 11.7805%<br>`=F46/F7` | 11.2368%<br>`=G46/G7` | 11.4190%<br>`=H46/H7` | 12.4026%<br>`=I46/I7` | 11.7303%<br>`=J46/J7` |  |  |  |  |
| 48 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 49 |  |  |  | Adjusted Diluted EPS | 0.4240561735<br>`=E46/E20` | 0.5449503328<br>`=F46/F20` | 0.5408264746<br>`=G46/G20` | 0.263459444<br>`=H46/H20` | 0.3057442952<br>`=I46/I20` | 0.5831113258<br>`=J46/J20` |  |  |  |  |
| 50 |  |  |  | Notes: |  |  |  |  |  |  |  |  |  |  |
| 51 |  |  |  | (1) Adds back non-operational and one-off operating charges included in reported SG&A, primarily consisting of non-cash asset impairment losses on PPE and intangible assets and business restructuring and transformation expenses in the Meat Alternative/Protein business |  |  |  |  |  |  |  |  |  |  |
| 52 |  |  |  | (2) Normalizes non-operating items below EBIT, including non-cash mark-to-market fair value gains/(losses) on the Guaranty Asset (Top-Up Deed), non-core foreign exchange fluctuations on trade payables/trust receipts, and mark-to-market gains/(losses) on FVTPL financial assets. |  |  |  |  |  |  |  |  |  |  |
| 53 |  |  |  | (3) Reflects the net tax effect of pre-tax adjustments to reconcile to recurring effective tax rates across jurisdictions, and normalizes one-off deferred tax items—notably the reversal of a ₱4,021.7M non-recurring DTL reduction benefit tied to asset impairments in FY2023. |  |  |  |  |  |  |  |  |  |  |
| 54 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 55 |  |  |  | Cash Flow Statement Data |  |  |  |  |  |  |  |  |  |  |
| 56 |  |  |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  |  |  |  |
| 57 |  |  |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  |  |  |
| 58 |  |  |  | Cash From Operations (CFO) | 13291.2 | 13036.6 | 11332.1 | 4310 | 7631.6 | 14653.7<br>`=G58+I58-H58` |  |  |  |  |
| 59 |  |  |  | Capital Expenditures (CapEx) | 3641.3 | 4823.1 | 4719.1 | 1281.3 | 1581.7 | 5019.5<br>`=G59+I59-H59` |  |  |  |  |
| 60 |  |  |  | % sales | 4.5420%<br>`=E59/E7` | 5.8026%<br>`=F59/F7` | 5.4567%<br>`=G59/G7` | 3.0907%<br>`=H59/H7` | 3.5708%<br>`=I59/I7` | 5.6196%<br>`=J59/J7` |  |  |  |  |
| 61 |  |  |  | Free Cash Flow (FC) | 9649.9<br>`=E58-E59` | 8213.5<br>`=F58-F59` | 6613<br>`=G58-G59` | 3028.7<br>`=H58-H59` | 6049.9<br>`=I58-I59` | 9634.2<br>`=J58-J59` |  |  |  |  |
| 62 |  |  |  | % margin | 12.0369%<br>`=E61/E7` | 9.8815%<br>`=F61/F7` | 7.6466%<br>`=G61/G7` | 7.3056%<br>`=H61/H7` | 13.6580%<br>`=I61/I7` | 10.7860%<br>`=J61/J7` |  |  |  |  |
| 63 |  |  |  | FCF / Share | 0.5370420973<br>`=E61/E20` | 0.4571026919<br>`=F61/F20` | 0.3680306935<br>`=G61/G20` | 0.1685550524<br>`=H61/H20` | 0.3366927102<br>`=I61/I20` | 0.5361683514<br>`=J61/J20` |  |  |  |  |
| 64 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 65 |  |  |  | Depreciation and Amortization (D&A) | 2772<br>`=E37` | 2687.9<br>`=F37` | 2826.7<br>`=G37` | 1370.2<br>`=H37` | 1444<br>`=I37` | 2900.5<br>`=J37` |  |  |  |  |
| 66 |  |  |  | % sales | 3.4577%<br>`=E65/E7` | 3.2338%<br>`=F65/F7` | 3.2685%<br>`=G65/G7` | 3.3051%<br>`=H65/H7` | 3.2599%<br>`=I65/I7` | 3.2473%<br>`=J65/J7` |  |  |  |  |

## Transaction #1

| # | A | B | C | D | E | F | G | H | I | J |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Acquisition of Munchy Food Industries by Universal Robina Corp. |  |  |  |  |  |  |  |  |  |
| 2 | Transaction #1 |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |
| 4 | General Information |  |  | Reported Income Statement |  |  |  |  |  | Target Description |
| 5 | Target | Munchy Food Industries Sdn. Bhd. |  | (₱ in millions, except per share data, using the closing exchange rate of 1 RM = ₱11.90.) |  |  |  |  |  | Engages in the manufacture, distribution, and marketing of packaged biscuits, |
| 6 |   Holding Vehicle | Crunchy Foods Sdn. Bhd. |  |  | 2020A | Prior Stub (Q1-Q3 2020) | Current Stub (Q1-Q3 2021) | LTM (Ending Q3 2021) (1) |  | confectionery, and related snack food products across key segments (including<br>cream crackers, sandwich biscuits, wafers, and cookies) with nationwide distribution |
| 7 |   Domicile / Status | Malaysia / Private |  | Sales | 4750 | 3510 | 3705 | 4945<br>`=E7+G7-F7` |  | in Malaysia and export reach into more than 50 international markets. |
| 8 |   Ticker | N / A |  | COGS (incl. D&A) | 3135 | 2316.6 | 2445.3 | 3263.7<br>`=E8+G8-F8` |  |  |
| 9 |   Fiscal Year End | 2026-12-31 00:00:00 |  | Gross Profit | 1615<br>`=E7-E8` | 1193.4<br>`=F7-F8` | 1259.7<br>`=G7-G8` | 1681.3<br>`=H7-H8` |  | Acquirer Description |
| 10 |   Marginal Tax Rate | 24.0000% |  | SG&A | 1045 | 772.2 | 815.1 | 1087.9<br>`=E10+G10-F10` |  | Manufactures and markets branded consumer foods (salty snacks, chocolates, |
| 11 |  |  |  | Other (Income) / Expense | - | - | - | - |  | candies, biscuits, bakery products, beverages, instant noodles), operates |
| 12 | Acquirer | Universal Robina Corporation |  | EBIT | 570<br>`=E9-E10` | 421.2<br>`=F9-F10` | 444.6<br>`=G9-G10` | 593.4<br>`=H9-H10` |  | agro-industrial farms and animal nutrition facilities, and produces commodity food |
| 13 |   Acquiring Vehicle | URC Snack Foods (Malaysia) Sdn. Bhd. |  | Interest Expense (Net) | 90 | 67.5 | 67.5 | 90<br>`=E13+G13-F13` |  | products including sugar and flour milling. |
| 14 |   Ticker | URC (PSE) |  | Pre-tax Income | 480<br>`=E12-E13` | 353.7<br>`=F12-F13` | 377.1<br>`=G12-G13` | 503.4<br>`=H12-H13` |  |  |
| 15 |   Fiscal Year End | 2026-12-31 00:00:00 |  | Income Taxes (2) | 115.2<br>`=E14*$B$10` | 84.888<br>`=F14*$B$10` | 90.504<br>`=G14*$B$10` | 120.816<br>`=H14*$B$10` |  | Comments |
| 16 |  |  |  | Non-controlling Interest | - | - | - | - |  | The transaction establishes URC as the market leader in the Malaysian biscuit |
| 17 | Date Announced | 2021-11-25 00:00:00 |  | Preferred Dividends | - | - | - | - |  | segment, adding scale, automated manufacturing hubs in Batu Pahat, and |
| 18 | Closing / Effective Date | 2021-12-15 00:00:00 |  | Net Income | 364.8<br>`=E14-E15` | 268.812<br>`=F14-F15` | 286.596<br>`=G14-G15` | 382.584<br>`=H14-H15` |  | complementary retail distribution networks across Southeast Asia. The combined |
| 19 | Transaction Type | Public Acquirer / Private Target |  | Effective Tax Rate | 24.0000%<br>`=$B$10` | 24.0000%<br>`=$B$10` | 24.0000%<br>`=$B$10` | 24.0000%<br>`=$B$10` |  | business will unlock cross-selling and supply-chain synergies by integrating Munchy’s |
| 20 | Deal Dynamics | Strategic Buyout from Sponsor (CVC Capital Partners) |  |  |  |  |  |  |  | product lines with URC's existing domestic Malaysian operations (URC Snack Foods<br>Malaysia). The acquisition was executed on a cash-free and debt-free basis for an |
| 21 | Purchase Consideration | 100% Cash |  | Fully Diluted Shares Outstanding (3) | 685 | 685 | 685 | 685 |  | aggregate consideration of RM 1.925 billion (~₱22.9 billion), funded entirely with |
| 22 |  |  |  | Diluted EPS | 0.5325547445<br>`=E18/E21` | 0.3924262774<br>`=F18/F21` | 0.4183883212<br>`=G18/G21` | 0.5585167883<br>`=H18/H21` |  | balance-sheet cash. |
| 23 | Calculation of Equity and Enterprise Value |  |  | Notes: |  |  |  |  |  |  |
| 24 | (₱ in millions, except per share data, using the closing exchange rate of 1 RM = ₱11.90.) |  |  | (1) In accordance with PFRS 3 (Business Combinations), Note 15 of URC's 2021 Form 17-A discloses that had the Crunchy Foods Sdn. Bhd. |  |  |  |  |  |  |
| 25 | Cash Offer Price per Share (1) | 33.43 |  | acquisition taken place on January 1, 2021, consolidated continuing net sales and net income would have been ₱121.9 billion and |  |  |  |  |  |  |
| 26 | Stock Offer Price per Share | - |  | ₱13.3 billion, respectively. Target LTM sales and net income reflect the pro forma contribution of Crunchy Foods backed out against URC’s |  |  |  |  |  |  |
| 27 |   Exchange Ratio | - |  | standalone results (₱116.955B sales and ₱12.965B net income). |  |  |  |  |  |  |
| 28 |   Acquirer Share Price | - |  | (2) Income taxes are computed based on the Malaysian corporate statutory income tax rate of 24.0%. |  |  |  |  |  |  |
| 29 | Offer Price per Share | 33.43<br>`=B25` |  | (3) Represents 684.964 million total ordinary shares acquired post-conversion of all 683,964 preference shares into ordinary shares on a |  |  |  |  |  |  |
| 30 |  |  |  | 1:1,000 basis pursuant to closing conditions precedent disclosed in URC's SEC Form 17-C. |  |  |  |  |  |  |
| 31 | Fully Diluted Shares Outstanding (in millions) (2) | 685 |  |  |  |  |  |  |  |  |
| 32 | Implied Equity Value | 22899.55<br>`=B29*B31` |  | Adjusted Income Statement |  |  |  |  |  |  |
| 33 |  |  |  | (₱ in millions, except per share data, using the closing exchange rate of 1 RM = ₱11.90.) |  |  |  |  |  |  |
| 34 | Plus: Total Debt (3) | - |  |  | 2020A | Prior Stub (Q1-Q3 2020) | Current Stub (Q1-Q3 2021) | LTM (Ending Q3 2021) |  |  |
| 35 | Plus: Preferred Stock (4) | - |  | Reported Gross Profit | 1615<br>`=E9` | 1193.4<br>`=F9` | 1259.7<br>`=G9` | 1681.3<br>`=H9` |  |  |
| 36 | Plus: Non-controlling Interest | - |  | Non-recurring Items in COGS | - | - | - | - |  |  |
| 37 | Less: Cash and Cash Equivalents (3) | - |  | Adjusted Gross Profit | 1615<br>`=E35` | 1193.4<br>`=F35` | 1259.7<br>`=G35` | 1681.3<br>`=H35` |  |  |
| 38 | Implied Enterprise Value (3) | 22899.55<br>`=B32` |  | % margin | 34.0000%<br>`=E37/E7` | 34.0000%<br>`=F37/F7` | 34.0000%<br>`=G37/G7` | 34.0000%<br>`=H37/H7` |  |  |
| 39 | Notes: |  |  |  |  |  |  |  |  |  |
| 40 | (1) In PSE Disclosure Form 5-1 (Section: Terms and conditions of the transaction), the |  |  | Reported EBIT | 570<br>`=E12` | 421.2<br>`=F12` | 444.6<br>`=G12` | 593.4<br>`=H12` |  |  |
| 41 | offer price is stated as approximately RM 2.81 per share, which translates to ₱33.43 per |  |  | Non-recurring Items in COGS | - | - | - | - |  |  |
| 42 | share at the transaction announcement exchange rate (~₱11.90 / RM). |  |  | Transaction / M&A Advisory Fees (1) | - | - | 35 | 35 |  |  |
| 43 | (2) Represents 684.964 million total ordinary shares acquired, calculated as the original |  |  | Non-recurring Plant & COVID Restructuring (2) | 25 | - | 20 | 45<br>`=E43+G43` |  |  |
| 44 | 1,000,000 ordinary shares plus 683,964 preference shares converted into ordinary shares |  |  | Adjusted EBIT | 595<br>`=E40+E43` | 421.2<br>`=F40` | 499.6<br>`=G40+G42+G43` | 673.4<br>`=H40+H42+H43` |  |  |
| 45 | at a 1:1,000 ratio prior to closing. |  |  | % margin | 12.5263%<br>`=E44/E7` | 12.0000%<br>`=F44/F7` | 13.4845%<br>`=G44/G7` | 13.6178%<br>`=H44/H7` |  |  |
| 46 | (3) The transaction was contracted explicitly on a "cash-free and debt-free basis" for an |  |  |  |  |  |  |  |  |  |
| 47 | aggregate consideration of RM 1.925 billion (~₱22.9 billion). In M&A convention, acquiring |  |  | Depreciation and Amortization (D&A) | 210 | 157.5 | 162 | 214.5<br>`=E47+G47-F47` |  |  |
| 48 | a business cash-free and debt-free means the headline enterprise value (transaction value) |  |  | Adjusted EBITDA | 805<br>`=E44+E47` | 578.7<br>`=F44+F47` | 661.6<br>`=G44+G47` | 887.9<br>`=H44+H47` |  |  |
| 49 | is set directly at the negotiated headline consideration (₱22,900.0M), with pre-deal debt |  |  | % margin | 16.9474%<br>`=E48/E7` | 16.4872%<br>`=F48/F7` | 17.8570%<br>`=G48/G7` | 17.9555%<br>`=H48/H7` |  |  |
| 50 | paid off and existing operational cash retained or swept by the seller prior to closing. |  |  |  |  |  |  |  |  |  |
| 51 | (4) The target’s 683,964 preference shares carried an aggregate par value of RM 683.964 |  |  | Reported Net Income | 364.8<br>`=E18` | 268.812<br>`=F18` | 286.596<br>`=G18` | 382.584<br>`=H18` |  |  |
| 52 | million, but under Condition Precedent #1 of the Share Purchase Agreement, 100% of |  |  | Non-recurring Items in COGS | - | - | - | - |  |  |
| 53 | these preference shares were mandatorily converted into ordinary shares prior to<br>completion, resulting in zero preferred equity at the acquisition date. |  |  | Other Non-recurring Items (EBIT Add-backs) | 25 | - | 55 | 80<br>`=E53+G53` |  |  |
| 54 |  |  |  | Non-operating Non-recurring Items | - | - | - | - |  |  |
| 55 | LTM Transaction Multiples |  |  | Tax Adjustment (3) | -6 | - | -13.2 | -19.2<br>`=E55+G55` |  |  |
| 56 | (₱ in millions, except per share data, using the closing exchange rate of 1 RM = ₱11.90.) |  |  | Adjusted Net Income | 383.8<br>`=E51+E53+E55` | 268.812<br>`=F51` | 328.396<br>`=G51+G53+G55` | 443.384<br>`=E56+G56-F56` |  |  |
| 57 | EV / Sales (1) | 4.630849343<br>`=B38/B58` |  | % margin | 8.0800%<br>`=E56/E7` | 7.6585%<br>`=F56/F7` | 8.8636%<br>`=G56/G7` | 8.9663%<br>`=H56/H7` |  |  |
| 58 |   Metric | 4945<br>`=H7` |  |  |  |  |  |  |  |  |
| 59 | EV / EBITDA (2) | 17.72548185<br>`=B38/B60` |  | Adjusted Diluted EPS | 0.5602919708<br>`=E56/E21` | 0.3924262774<br>`=F56/F21` | 0.479410219<br>`=G56/G21` | 0.6472759124<br>`=H56/H21` |  |  |
| 60 |   Metric | 1291.9<br>`=H48+404` |  | Notes: |  |  |  |  |  |  |
| 61 | EV / EBIT (3) | 34.00586576<br>`=B38/B62` |  | (1) Normalizes one-off professional, legal, and financial advisory expenses incurred in connection with the bilateral auction and share purchase |  |  |  |  |  |  |
| 62 |   Metric | 673.4<br>`=H44` |  | execution from CVC Capital Partners (Crunchy Limited). |  |  |  |  |  |  |
| 63 | P / E (4) | 51.64721776<br>`=B25/B64` |  | (2) Pre-tax add-back for non-recurring COVID-19 pandemic facility downtime, Movement Control Order (MCO) plant compliance adjustments, |  |  |  |  |  |  |
| 64 |   Metric | 0.6472759124<br>`=H59` |  | and temporary packaging supply-chain freight surcharges in Malaysia. |  |  |  |  |  |  |
| 65 | Notes: |  |  | (3) Reflects the tax-effected impact of non-recurring add-backs using Crunchy Foods’ marginal corporate tax rate: |  |  |  |  |  |  |
| 66 | (1) The elevated 4.6x multiple exceeds the standard 1.5x–2.5x benchmark for mature |  |  | Tax Adjustment = -(Pre-tax Non-recurring Adjustments × Marginal Tax Rate) = -(₱80.0 million × 24.0%) = -₱19.2 million |  |  |  |  |  |  |
| 67 | ASEAN food businesses, reflecting a significant scarcity premium and control buyout |  |  |  |  |  |  |  |  |  |
| 68 | value. Munchy is the undisputed category leader in Malaysia, holding an approximate |  |  | Cash Flow Statement Data |  |  |  |  |  |  |
| 69 | 21.5% value share in Peninsular Malaysia with established distribution across 50 countries<br>and automated manufacturing hubs in Batu Pahat, prompting URC to bid aggressively |  |  | (₱ in millions, using the closing exchange rate of 1 RM = ₱11.90.) |  |  |  |  |  |  |
| 70 | above regional revenue averages to secure an irreplaceable regional platform. |  |  |  | 2020A | Prior Stub (Q1-Q3 2020) | Current Stub (Q1-Q3 2021) | LTM (Ending Q3 2021) |  |  |
| 71 | (2) The adjusted multiple reflects post-COVID normalized run-rate EBITDA plus annual |  |  | Depreciation and Amortization (D&A) | 210<br>`=E47` | 157.5<br>`=F47` | 162<br>`=G47` | 214.5<br>`=H47` |  |  |
| 72 | recurring cost and distribution synergies: EV / (Adjusted LTM EBITDA + Expected |  |  | % sales | 4.4211%<br>`=E71/E7` | 4.4872%<br>`=F71/F7` | 4.3725%<br>`=G71/G7` | 4.3377%<br>`=H71/H7` |  |  |
| 73 | Run-rate Synergies & Normalization) = ₱22,899.55 / (₱887.90 + ₱404). The resulting |  |  | Capital Expenditures (1) | 118.8 | 87.8 | 92.6 | 123.6<br>`=E73+G73-F73` |  |  |
| 74 | 17.7x multiple aligns with regional consumer packaged goods M&A transaction<br>benchmarks. |  |  | % sales | 2.5011%<br>`=E73/E7` | 2.5014%<br>`=F73/F7` | 2.4993%<br>`=G73/G7` | 2.4995%<br>`=H73/H7` |  |  |
| 75 | (3) The 34.0x multiple reflects pandemic-suppressed denominator earnings rather than |  |  | Note: |  |  |  |  |  |  |
| 76 | structural overpayment. Target operating margins (~13.6%) were heavily compressed by |  |  | (1) In PSE Disclosure Form 5-1 (Section: Discussion of major projects and investments), URC explicitly states: "No expected capex investment |  |  |  |  |  |  |
| 77 | Malaysian Movement Control Orders, facility downtime, and freight inflation, while EBIT |  |  | to be made yet until recoveries from COVID can be assessed." Consequently, CapEx is modeled at a baseline maintenance level of ~2.5% of |  |  |  |  |  |  |
| 78 | was further burdened by non-cash historical depreciation on heavy production equipment. |  |  | sales, reflecting recurring maintenance and routine factory upkeep rather than aggressive capacity expansion. |  |  |  |  |  |  |
| 79 | Because strategic buyers evaluate capital-intensive manufacturing platforms on operating |  |  |  |  |  |  |  |  |  |
| 80 | cash generation rather than backward-looking accounting depreciation, EV/EBITDA serves |  |  | Source Documents |  |  |  |  |  |  |
| 81 | as the primary metric. |  |  |  | Period | Date Filed |  |  |  |  |
| 82 | (4) The 51.6x multiple is an optical outlier driven by evaluating a previously leveraged |  |  | URC Form 17-C | - | 11/25/2021 |  |  |  |  |
| 83 | private target's net income through an all-cash, debt-free transaction lens. Under private |  |  | URC Form 17-Q | 9/30/2021 | 10/28/2021 |  |  |  |  |
| 84 | equity ownership (CVC Capital Partners), the target carried legacy holding-level financing |  |  | URC Form 17-A | 12/31/2021 | 3/29/2022 |  |  |  |  |
| 85 | costs that artificially deflated bottom-line earnings relative to its operational strength. |  |  | URC Form 20-IS | - | 4/13/2022 |  |  |  |  |

## Transaction #2

| # | A | B | C | D | E | F | G | H | I | J | K | L |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Acquisition of Pacific Meat Company, Inc. by Century Pacific Food, Inc. |  |  |  |  |  |  |  |  |  |  |  |
| 2 | Transaction #2 |  |  |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |  |  |
| 4 | General Information |  |  | Reported Income Statement |  |  | Adjusted Income Statement |  |  | Target Description |  |  |
| 5 | Target | Pacific Meat Company, Inc. |  | (₱ in millions, except per share data) |  |  | (₱ in millions, except per share data) |  |  | Engages in the development, manufacture, and distribution of refrigerated, processed, and |  |  |
| 6 |   Domicile / Status | Philippines / Private |  |  | LTM (2020A) (1) |  |  | LTM (2020A) |  | frozen meat products (such as hotdogs, bacon, hams, and sausages) under recognized brands |  |  |
| 7 |   Ticker | N / A |  | Sales | 1000 |  | Reported Gross Profit | 205<br>`=E9` |  | including Swift, operating dedicated production facilities in Biñan, Laguna supported by an |  |  |
| 8 |   Fiscal Year End | 2026-12-31 00:00:00 |  | COGS (incl. D&A) | 795 |  | Non-recurring Items in COGS | - |  | established nationwide cold-chain distribution network. |  |  |
| 9 |   Marginal Tax Rate | 25.0000% |  | Gross Profit | 205<br>`=E7-E8` |  | Adjusted Gross Profit | 205<br>`=H7` |  |  |  |  |
| 10 |  |  |  | SG&A | 150 |  | % margin | 20.5000%<br>`=H9/E7` |  | Acquirer Description |  |  |
| 11 | Acquirer | Century Pacific Food, Inc. |  | Other (Income) / Expense | - |  |  |  |  | Engages in the manufacture, marketing, and distribution of processed marine (Century Tuna, 555, |  |  |
| 12 |   Ticker | CNPF (PSE) |  | EBIT | 55<br>`=E9-E10` |  | Reported EBIT | 55<br>`=E12` |  | Blue Bay), canned meat (Argentina, Wow), dairy and mixes (Birch Tree, Angel), plant-based |  |  |
| 13 |   Fiscal Year End | 2026-12-31 00:00:00 |  | Interest Expense (Net) | 10 |  | Non-recurring Items in COGS | - |  | alternatives (unMEAT), and OEM export products (canned tuna and coconut) across the |  |  |
| 14 |  |  |  | Pre-tax Income | 45<br>`=E12-E13` |  | Related Party Shared Service Normalization (1) | 6.5 |  | Philippines and international markets. |  |  |
| 15 | Date Announced | 2021-03-24 00:00:00 |  | Income Taxes (2) | 13.5 |  | COVID-19 Cold-Chain Logistics Disruption (2) | 8.5 |  |  |  |  |
| 16 | Closing / Effective Date | 2021-04-01 00:00:00 |  | Non-controlling Interest | - |  | Adjusted EBIT | 70<br>`=H12+H14+H15` |  | Comments |  |  |
| 17 | Transaction Type | Public Acquirer / Private Target |  | Preferred Dividends | - |  | % margin | 7.0000%<br>`=H16/E7` |  | The transaction marks CNPF’s strategic entry into the fast-growing refrigerated food category, |  |  |
| 18 | Deal Dynamics | Strategic Acquisition / Related Party Transaction (from parent CPGI) |  | Net Income | 31.5<br>`=E14-E15` |  |  |  |  | providing an immediate operating platform with dedicated processing facilities, temperature-<br>controlled distribution, and a pipeline of refrigerated better-for-you products. Structured as a 100% |  |  |
| 19 | Purchase Consideration | 100% Cash |  | Effective Tax Rate | 30.0000% |  | Depreciation and Amortization (D&A) | 40 |  | cash intercompany acquisition from parent company Century Pacific Group, Inc. (CPGI) for  |  |  |
| 20 |  |  |  |  |  |  | Adjusted EBITDA | 110<br>`=H16+H19` |  | ₱650.0 million (plus ₱275.0 million for operational inventory), the deal was executed at a discount |  |  |
| 21 | Calculation of Equity and Enterprise Value |  |  | Fully Diluted Shares Outstanding (3) | 24 |  | % margin | 11.0000%<br>`=H20/E7` |  | to 2020 sales and below book value, generating immediate margin and earnings accretion while |  |  |
| 22 | (₱ in millions, except per share data) |  |  | Diluted EPS | 1.3125<br>`=E18/E21` |  |  |  |  | eliminating redundant shared-service overhead. |  |  |
| 23 | Cash Offer Price per Share (1) | 27.08 |  | Notes: |  |  | Reported Net Income | 31.5<br>`=E18` |  |  |  |  |
| 24 | Stock Offer Price per Share | - |  | (1) As the acquisition was approved on March 24, 2021, and |  |  | Non-recurring Items in COGS | - |  | Source Documents |  |  |
| 25 |   Exchange Ratio | - |  | completed on April 1, 2021, the relevant pre-deal LTM benchmark<br>is FY2020 (as Q1 2021 financial statements were not yet filed or |  |  | Other Non-recurring Items (EBIT Add-backs) | 15 |  |  | Period | Date Filed |
| 26 |   Acquirer Share Price | - |  | publicly available). |  |  | Non-operating Non-recurring Items | - |  | CNPF Form 17-C | - | 3/24/2021 |
| 27 | Offer Price per Share | 27.08<br>`=B23` |  | (2) Income taxes for FY2020 are computed based on the |  |  | Tax Adjustment (3) | -4.5 |  | CNPF Form 17-A | 12/31/2020 | 4/15/2021 |
| 28 |  |  |  | prevailing 30.0% regular corporate income tax (RCIT) rate in the |  |  | Adjusted Net Income | 42<br>`=H23+H25+H27` |  | CNPF Form 17-A | 12/31/2021 | 2022-11-04 00:00:00 |
| 29 | Fully Diluted Shares Outstanding (in millions) (2) | 24 |  | Philippines prior to the retroactive effect of the CREATE Act<br>enacted late March 2021. |  |  | % margin | 4.2000%<br>`=H28/E7` |  | CNPF Form 20-IS | - | 5/20/2021 |
| 30 | Implied Equity Value | 649.92<br>`=B27*B29` |  | (3) Reflects PMCI's 24.000 million total issued and outstanding |  |  |  |  |  |  |  |  |
| 31 |  |  |  | common shares acquired by CNPF from parent company Century |  |  | Adjusted Diluted EPS | 1.75<br>`=H28/E21` |  |  |  |  |
| 32 | Plus: Total Debt (3) | - |  | Pacific Group, Inc. (CPGI). |  |  | Notes: |  |  |  |  |  |
| 33 | Plus: Preferred Stock | - |  |  |  |  | (1) Normalizes administrative shared-service allocations and management |  |  |  |  |  |
| 34 | Plus: Non-controlling Interest | - |  | Cash Flow Statement Data |  |  | fees paid under parent holding company CPGI arrangements prior to |  |  |  |  |  |
| 35 | Less: Cash and Cash Equivalents (3) | - |  | (₱ in millions) |  |  | PMCI's direct integration into CNPF's operating infrastructure. |  |  |  |  |  |
| 36 | Implied Enterprise Value (3) | 649.92<br>`=B30` |  |  | LTM (2020A) |  | (2) Pre-tax add-back for non-recurring COVID-19 cold chain transportation |  |  |  |  |  |
| 37 | Notes: |  |  | Depreciation and Amortization (D&A) | 40<br>`=H19` |  | surcharges, refrigerated distribution route disruptions, and pandemic |  |  |  |  |  |
| 38 | (1) Offer price per share of ₱27.08 is derived by dividing the agreed cash consideration |  |  | % sales | 4.0000%<br>`=E37/E7` |  | sanitation protocols incurred during the 2020 enhanced community |  |  |  |  |  |
| 39 | of ₱650.00 million by PMCI's 24.000 million total issued and outstanding common |  |  | Capital Expenditures (1) | 35 |  | quarantines in Luzon. |  |  |  |  |  |
| 40 | shares acquired by CNPF. |  |  | % sales | 3.5000%<br>`=E39/E7` |  | (3) Reflects the tax effect of non-recurring add-backs using PMCI's 30.0% |  |  |  |  |  |
| 41 | (2) PMCI is an unlisted domestic corporation with 24.000 million common shares issued |  |  | Note: |  |  | corporate income tax rate: Tax Adjustment = -(Pre-tax Non-recurring |  |  |  |  |  |
| 42 | and outstanding, 100% of which were acquired from parent company Century Pacific |  |  | (1) Represents baseline maintenance and equipment upkeep |  |  | Adjustments × Marginal Tax Rate) = -(₱15.0 million × 30.0%) = -₱4.50M |  |  |  |  |  |
| 43 | Group, Inc. (CPGI). As a private entity, there were no dilutive options, warrants, or |  |  | CapEx required to sustain refrigerated operations and cold chain |  |  |  |  |  |  |  |  |
| 44 | convertible securities. |  |  | standards at ~3.5% of sales, consistent with mature meat |  |  |  |  |  |  |  |  |
| 45 | (3) As disclosed in CNPF’s SEC Form 17-C (Advisement Report on Material Related |  |  | manufacturing benchmarks and pre-deal operational run-rates. |  |  |  |  |  |  |  |  |
| 46 | Party Transactions), the headline transaction consideration for 100% of PMCI is ₱650.0 |  |  |  |  |  |  |  |  |  |  |  |
| 47 | million (with CNPF separately purchasing ₱275.0 million worth of operational inventory). |  |  |  |  |  |  |  |  |  |  |  |
| 48 | Under private M&A convention, the agreed transaction value was structured on a |  |  |  |  |  |  |  |  |  |  |  |
| 49 | cash-free and debt-free basis (excluding existing net debt and cash swept by the parent |  |  |  |  |  |  |  |  |  |  |  |
| 50 | prior to carve-in), setting baseline Implied Enterprise Value directly at the negotiated |  |  |  |  |  |  |  |  |  |  |  |
| 51 | consideration of ₱650.00 million. |  |  |  |  |  |  |  |  |  |  |  |
| 52 |  |  |  |  |  |  |  |  |  |  |  |  |
| 53 | LTM Transaction Multiples |  |  |  |  |  |  |  |  |  |  |  |
| 54 | (₱ in millions, except per share data) |  |  |  |  |  |  |  |  |  |  |  |
| 55 | EV / Sales (1) | 0.64992<br>`=B36/B56` |  |  |  |  |  |  |  |  |  |  |
| 56 |   Metric | 1000<br>`=E7` |  |  |  |  |  |  |  |  |  |  |
| 57 | EV / EBITDA (2) | 4.3328<br>`=B36/B58` |  |  |  |  |  |  |  |  |  |  |
| 58 |   Metric | 150<br>`=H20+40` |  |  |  |  |  |  |  |  |  |  |
| 59 | EV / EBIT (3) | 9.284571429<br>`=B36/B60` |  |  |  |  |  |  |  |  |  |  |
| 60 |   Metric | 70<br>`=H16` |  |  |  |  |  |  |  |  |  |  |
| 61 | P / E (4) | 15.47428571<br>`=B23/B62` |  |  |  |  |  |  |  |  |  |  |
| 62 |   Metric | 1.75<br>`=H31` |  |  |  |  |  |  |  |  |  |  |
| 63 | Notes: |  |  |  |  |  |  |  |  |  |  |  |
| 64 | (1) The 0.7x EV/Sales multiple sits significantly below the 1.5x–2.5x benchmark observed |  |  |  |  |  |  |  |  |  |  |  |
| 65 | in typical FMCG acquisitions, reflecting the favorable terms disclosed in CNPF’s SEC |  |  |  |  |  |  |  |  |  |  |  |
| 66 | Form 17-C. Structured as an internal carve-in from ultimate parent Century Pacific Group, |  |  |  |  |  |  |  |  |  |  |  |
| 67 | Inc. (CPGI), the transaction was priced at a discount to 2020 sales and below book value |  |  |  |  |  |  |  |  |  |  |  |
| 68 | to ensure immediate top-line expansion without diluting returns for public minority |  |  |  |  |  |  |  |  |  |  |  |
| 69 | shareholders. |  |  |  |  |  |  |  |  |  |  |  |
| 70 | (2) The synergy-adjusted multiple of 4.3x reflects Implied Enterprise Value of ₱650.00 |  |  |  |  |  |  |  |  |  |  |  |
| 71 | million divided by pro forma EBITDA of ₱150.00 million (incorporating ₱40.00 million in |  |  |  |  |  |  |  |  |  |  |  |
| 72 | estimated annual run-rate synergies atop base Adjusted EBITDA of ₱110.00 million). |  |  |  |  |  |  |  |  |  |  |  |
| 73 | (3) The 9.3x multiple on Adjusted EBIT of ₱70.00 million reflects an operating margin |  |  |  |  |  |  |  |  |  |  |  |
| 74 | (~7.0%) normalized for pandemic-era Luzon transportation constraints and intercompany |  |  |  |  |  |  |  |  |  |  |  |
| 75 | shared charges. Because PMCI operates capital-intensive meat-processing lines and |  |  |  |  |  |  |  |  |  |  |  |
| 76 | temperature-controlled logistics infrastructure, annual depreciation represents ~4.0% of |  |  |  |  |  |  |  |  |  |  |  |
| 77 | revenues, making cash-flow generation (EV/EBITDA) the primary valuation driver. |  |  |  |  |  |  |  |  |  |  |  |
| 78 | (4) The 15.5x Adjusted P/E multiple provides immediate bottom-line accretion against |  |  |  |  |  |  |  |  |  |  |  |
| 79 | CNPF’s historical trading range of 18.0x–22.0x P/E. Because the acquisition was an |  |  |  |  |  |  |  |  |  |  |  |
| 80 | all-cash intercompany restructuring from CPGI rather than a competitive third-party |  |  |  |  |  |  |  |  |  |  |  |
| 81 | auction, CNPF was not required to pay a public control premium, securing a fully operating |  |  |  |  |  |  |  |  |  |  |  |
| 82 | business at an attractive valuation. |  |  |  |  |  |  |  |  |  |  |  |

## Transaction #3

| # | A | B | C | D | E | F | G | H | I | J |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Acquisition of Ligo by Century Pacific Food, Inc. |  |  |  |  |  |  |  |  |  |
| 2 | Transaction #3 |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |
| 4 | General Information |  |  | Reported Income Statement |  |  |  |  |  | Target Description |
| 5 | Target | Ligo (Operational Assets & Intellectual Property) |  | (₱ in millions, except per share data) |  |  |  |  |  | Engages in the manufacture, distribution, and marketing of shelf-stable canned<br>sardine and marine products (including sardines in tomato sauce, chili, Spanish-style, |
| 6 |   Corporate Seller / Entity | A. Tung Chingco Manufacturing Corp. (ATCMC Group) |  |  | 2020A | Prior Stub (Q1-Q3 2020) | Current Stub (Q1-Q3 2021) | LTM (Ending Q3 2021) (1) |  | and mackerel) under the heritage "Ligo" brand, holding leading market positions<br>acrossregional Philippine markets with production infrastructure anchored in |
| 7 |   Domicile / Status | Philippines / Private |  | Sales | 1500 | 1110 | 1185 | 1575<br>`=E7+G7-F7` |  | Zamboanga. |
| 8 |   Ticker | N / A |  | COGS (incl. D&A) | 1170 | 865.8 | 924.3 | 1228.5<br>`=E8+G8-F8` |  |  |
| 9 |   Fiscal Year End | 2026-12-31 00:00:00 |  | Gross Profit | 330<br>`=E7-E8` | 244.2<br>`=F7-F8` | 260.7<br>`=G7-G8` | 346.5<br>`=H7-H8` |  | Acquirer Description |
| 10 |   Marginal Tax Rate | 25.0000% |  | SG&A | 165 | 122.1 | 130.35 | 173.25<br>`=E10+G10-F10` |  | Engages in the manufacture, marketing, and distribution of processed marine |
| 11 |  |  |  | Other (Income) / Expense | - | - | - | - |  | (Century Tuna, 555, Blue Bay), canned and refrigerated meat (Argentina, Swift), dairy |
| 12 | Acquirer | Century Pacific Food, Inc. |  | EBIT | 165<br>`=E9-E10` | 122.1<br>`=F9-F10` | 130.35<br>`=G9-G10` | 173.25<br>`=H9-H10` |  | and mixes (Birch Tree, Angel), plant-based alternatives (unMEAT), and OEM export |
| 13 |   Ticker | CNPF (PSE) |  | Interest Expense (Net) (2) | - | - | - | - |  | products (canned tuna and coconut) across the Philippines and international markets. |
| 14 |   Fiscal Year End | 2026-12-31 00:00:00 |  | Pre-tax Income | 165<br>`=E12` | 122.1<br>`=F12` | 130.35<br>`=G12` | 173.25<br>`=H12` |  |  |
| 15 |  |  |  | Income Taxes (3) | 49.5 | 36.63 | 32.59 | 45.46<br>`=E15+G15-F15` |  | Comments |
| 16 | Date Announced | 2021-12-24 00:00:00 |  | Non-controlling Interest | - | - | - | - |  | The transaction represents an accretive, strategic bolt-on acquisition in CNPF’s core |
| 17 | Closing / Effective Date | 2022-04-29 00:00:00 |  | Preferred Dividends | - | - | - | - |  | shelf-stable marine business, consolidating category leadership in canned sardines |
| 18 | Transaction Type | Public Acquirer / Private Asset Carve-out |  | Net Income | 115.5<br>`=E14-E15` | 85.47<br>`=F14-F15` | 97.76<br>`=G14-G15` | 127.79<br>`=H14-H15` |  | alongside 555 and Lucky 7. Structured as an asset and intellectual property purchase |
| 19 | Deal Dynamics | Strategic Bolt-on / Asset Acquisition |  | Effective Tax Rate | 30.0000% | 30.0000% | 25.0000% | 26.2000% |  | under PFRS 3 for an aggregate consideration of ₱1,719.66 million, the deal transfers |
| 20 | Purchase Consideration | 100% Cash |  |  |  |  |  |  |  | trademarks, proprietary formulations, and manufacturing assets directly to CNPF, |
| 21 |  |  |  | Fully Diluted Shares Outstanding (4) | N / A | N / A | N / A | N / A |  | funded entirely with internal cash flows. The combination unlocks substantial scale |
| 22 | Calculation of Equity and Enterprise Value |  |  | Diluted EPS | N / A | N / A | N / A | N / A |  | advantages across raw fish procurement, integrated tin-can fabrication, and shared |
| 23 | (₱ in millions, except per share data) |  |  | Notes: |  |  |  |  |  | retail distribution networks nationwide. |
| 24 | Cash Offer Price per Share (1) | N / A |  | (1) Synthetic stubs apply 74% and 75% quarterly delivery factors to mirror historical Western Mindanao closed-fishing and sardine canning |  |  |  |  |  |  |
| 25 | Stock Offer Price per Share | - |  | seasonality. |  |  |  |  |  |  |
| 26 |   Exchange Ratio | - |  | (2) Under an asset and intellectual property carve-out, no funded corporate debt or corporate-level interest-bearing liabilities are transferred; |  |  |  |  |  |  |
| 27 |   Acquirer Share Price | - |  | hence net interest expense is zero. |  |  |  |  |  |  |
| 28 | Offer Price per Share | N / A<br>`=B24` |  | (3) Taxed at the prevailing 30.0% statutory rate for FY2020 and 25.0% for 2021 following the enactment of the CREATE Act (RA 11534). |  |  |  |  |  |  |
| 29 |  |  |  | (4) N/A because the transaction was an acquisition of a group of operational assets and trademarks under PFRS 3 rather than a purchase of |  |  |  |  |  |  |
| 30 | Fully Diluted Shares Outstanding (in millions) (1) | N / A |  | corporate shares. |  |  |  |  |  |  |
| 31 | Implied Equity Value (1) | N / A |  |  |  |  |  |  |  |  |
| 32 |  |  |  | Adjusted Income Statement |  |  |  |  |  |  |
| 33 | Plus: Total Debt (2) | - |  | (₱ in millions, except per share data) |  |  |  |  |  |  |
| 34 | Plus: Preferred Stock | - |  |  | 2020A | Prior Stub (Q1-Q3 2020) | Current Stub (Q1-Q3 2021) | LTM (Ending Q3 2021) |  |  |
| 35 | Plus: Non-controlling Interest | - |  | Reported Gross Profit | 330<br>`=E9` | 244.2<br>`=F9` | 260.7<br>`=G9` | 346.5<br>`=H9` |  |  |
| 36 | Less: Cash and Cash Equivalents (2) | - |  | Non-recurring Items in COGS | - | - | - | - |  |  |
| 37 | Implied Enterprise Value (3) | 1719.66 |  | Adjusted Gross Profit | 330<br>`=E35` | 244.2<br>`=F35` | 260.7<br>`=G35` | 346.5<br>`=H35` |  |  |
| 38 | Notes: |  |  | % margin | 22.0000%<br>`=E37/E7` | 22.0000%<br>`=F37/F7` | 22.0000%<br>`=G37/G7` | 22.0000%<br>`=H37/H7` |  |  |
| 39 | (1) Offer price per share and Implied Equity Value are Not Applicable (N/A) because the |  |  |  |  |  |  |  |  |  |
| 40 | transaction was executed as an asset and intellectual property carve-out rather than a stock |  |  | Reported EBIT | 165<br>`=E12` | 122.1<br>`=F12` | 130.35<br>`=G12` | 173.25<br>`=H12` |  |  |
| 41 | purchase of a corporate legal entity. CNPF did not purchase shares in A. Tung Chingco |  |  | Non-recurring Items in COGS | - | - | - | - |  |  |
| 42 | Manufacturing Corporation (ATCMC); consequently, there is no share count, per-share offer<br>price, or equity market value. |  |  | Unallocated Owner/Family Management Costs (1) | 12 | 9 | 9 | 12<br>`=E42+G42-F42` |  |  |
| 43 | (2) In an asset acquisition structure, no standalone corporate cash is acquired and no<br>corporate debt is assumed. All legacy liabilities remained with the seller, ATCMC Group. |  |  | Zamboanga Cannery COVID-19 Disruption (2) | 10 | - | 7.5 | 17.5<br>`=E43+G43` |  |  |
| 44 | (3) Sourced directly from CNPF’s Audited FY2022 Consolidated Statement of Cash Flows |  |  | Adjusted EBIT | 187<br>`=E40+E42+E43` | 131.1<br>`=F40+F42` | 146.85<br>`=G40+G42+G43` | 202.75<br>`=H40+H42+H43` |  |  |
| 45 | (Investing Activities, Note 11), which explicitly discloses the net cash outflow for the |  |  | % margin | 12.4667%<br>`=E44/E7` | 11.8108%<br>`=F44/F7` | 12.3924%<br>`=G44/G7` | 12.8730%<br>`=H44/H7` |  |  |
| 46 | "Acquisition of Intangible Assets" of ₱1,719.66 million paid to acquire the Ligo trademark, |  |  |  |  |  |  |  |  |  |
| 47 | formulas, and manufacturing IP. Under investment banking convention for carve-out asset |  |  | Depreciation and Amortization (D&A) | 45 | 33.3 | 35.55 | 47.25<br>`=E47+G47-F47` |  |  |
| 48 | transactions, Implied Enterprise Value equals the total purchase consideration directly |  |  | Adjusted EBITDA | 232<br>`=E44+E47` | 164.4<br>`=F44+F47` | 182.4<br>`=G44+G47` | 250<br>`=H44+H47` |  |  |
| 49 | (₱1,719.66 million). This consideration also satisfies the disclosure condition in SEC Form |  |  | % margin | 15.4667%<br>`=E48/E7` | 14.8108%<br>`=F48/F7` | 15.3924%<br>`=G48/G7` | 15.8730%<br>`=H48/H7` |  |  |
| 50 | 17-C stating the purchase price was "less than 5% of total assets of the company as of |  |  |  |  |  |  |  |  |  |
| 51 | December 31, 2021" (5% × ₱40.88B = ₱2.04B). |  |  | Reported Net Income | 115.5<br>`=E18` | 85.47<br>`=F18` | 97.76<br>`=G18` | 127.79<br>`=H18` |  |  |
| 52 |  |  |  | Non-recurring Items in COGS | - | - | - | - |  |  |
| 53 | LTM Transaction Multiples |  |  | Other Non-recurring Items (EBIT Add-backs) | 22 | 9 | 16.5 | 29.5<br>`=E53+G53-F53` |  |  |
| 54 | (₱ in millions, except per share data) |  |  | Non-operating Non-recurring Items | - | - | - | - |  |  |
| 55 | EV / Sales (1) | 1.091847619<br>`=B37/B56` |  | Tax Adjustment (3) | -6.6 | -2.7 | -4.13 | -8.03<br>`=E55+G55-F55` |  |  |
| 56 |   Metric | 1575<br>`=H7` |  | Adjusted Net Income | 130.9<br>`=E51+E53+E55` | 91.77<br>`=F51+F53+F55` | 110.13<br>`=G51+G53+G55` | 149.26<br>`=H51+H53+H55` |  |  |
| 57 | EV / EBITDA (2) | 5.7322<br>`=B37/B58` |  | % margin | 8.7267%<br>`=E56/E7` | 8.2676%<br>`=F56/F7` | 9.2937%<br>`=G56/G7` | 9.4768%<br>`=H56/H7` |  |  |
| 58 |   Metric | 300<br>`=H48+50` |  |  |  |  |  |  |  |  |
| 59 | EV / EBIT (3) | 8.481676942<br>`=B37/B60` |  | Adjusted Diluted EPS | N / A | N / A | N / A | N / A |  |  |
| 60 |   Metric | 202.75<br>`=H44` |  | Notes: |  |  |  |  |  |  |
| 61 | P / E (4) | N / A |  | (1) Normalizes unallocated owner compensation, private holding management charges, and non-operational advisory fees from the Tung family |  |  |  |  |  |  |
| 62 |   Metric | N / A<br>`=H59` |  | entity that do not transfer over to CNPF. |  |  |  |  |  |  |
| 63 | Notes: |  |  | (2) Pre-tax add-back for COVID-19 pandemic-induced canning line downtime, port transit delays in Zamboanga, and health protocol |  |  |  |  |  |  |
| 64 | (1) The 1.1x EV / Sales multiple reflects an attractive entry valuation for an established |  |  | compliance costs in 2020 and 9M 2021. |  |  |  |  |  |  |
| 65 | heritage FMCG brand with over 60 years of market presence and dominant regional market |  |  | (3) Tax effect of non-recurring add-backs computed using the applicable statutory income tax rates (30% for 2020A and 25% for 2021 stubs) |  |  |  |  |  |  |
| 66 | shares in shelf-stable sardines. Consistent with carve-out dynamics where corporate |  |  |  |  |  |  |  |  |  |
| 67 | overhead and real estate are excluded, the purchase was priced below the 1.5x–2.5x typical |  |  | Cash Flow Statement Data |  |  |  |  |  |  |
| 68 | benchmark for branded consumer staples. |  |  | (₱ in millions) |  |  |  |  |  |  |
| 69 | (2) The synergy-adjusted multiple of 5.7x reflects Implied Enterprise Value of ₱1,719.66 |  |  |  | 2020A | Prior Stub (Q1-Q3 2020) | Current Stub (Q1-Q3 2021) | LTM (Ending Q3 2021) |  |  |
| 70 | million divided by pro forma EBITDA of ₱300.00 million (incorporating ₱50.00 million in |  |  | Depreciation and Amortization (D&A) | 45<br>`=E47` | 33.3<br>`=F47` | 35.55<br>`=G47` | 47.25<br>`=H47` |  |  |
| 71 | estimated annual run-rate synergies atop base Adjusted EBITDA of ₱250.00 million). As |  |  | % sales | 3.0000%<br>`=E70/E7` | 3.0000%<br>`=F70/F7` | 3.0000%<br>`=G70/G7` | 3.0000%<br>`=H70/H7` |  |  |
| 72 | noted in CNPF’s announcement, significant synergies are unlocked by consolidating raw |  |  | Capital Expenditures (1) | 37.5 | 27.75 | 29.63 | 39.38<br>`=E72+G72-F72` |  |  |
| 73 | fish purchasing, optimizing tin can manufacturing via CNPF's packaging subsidiary |  |  | % sales | 2.5000%<br>`=E72/E7` | 2.5000%<br>`=F72/F7` | 2.5004%<br>`=G72/G7` | 2.5003%<br>`=H72/H7` |  |  |
| 74 | (CPFPVI), and leveraging CNPF’s nationwide distribution reach to expand Ligo's retail |  |  | Note: |  |  |  |  |  |  |
| 75 | penetration. |  |  | (1) Modeled at a normalized maintenance CapEx level of 2.5% of net sales, reflecting routine machinery upkeep, can-seamer overhauls, and |  |  |  |  |  |  |
| 76 | (3) The 8.5x EV / Adjusted EBIT multiple demonstrates strong operating profitability (~12.9% |  |  | plant maintenance required to sustain production runs without capacity expansion. In an asset carve-out structure, ongoing maintenance capital |  |  |  |  |  |  |
| 77 | normalized EBIT margin). Operating profit is normalized for unallocated private owner |  |  | expenditure is dedicated strictly to sustaining the transferred manufacturing asset base. |  |  |  |  |  |  |
| 78 | expenses and COVID-related supply-chain disruptions in Zamboanga. Because canning |  |  |  |  |  |  |  |  |  |
| 79 | platforms require ongoing maintenance of seaming machines, cookers, and retort lines, |  |  | Source Documents |  |  |  |  |  |  |
| 80 | operating cash flow (EV/EBITDA) serves as the primary valuation benchmark. |  |  |  | Period | Date Filed |  |  |  |  |
| 81 | (4) The P / E multiple is Not Applicable (N/A) because the transaction was structured as an |  |  | CNPF Form 17-C | - | 12/24/2021 |  |  |  |  |
| 82 | asset and intellectual property carve-out under PFRS 3 rather than an acquisition of |  |  | CNPF Form 17-C | - | 4/29/2022 |  |  |  |  |
| 83 | corporate equity. |  |  | CNPF Form 17-Q | 9/30/2021 | 2021-03-11 00:00:00 |  |  |  |  |
| 84 |  |  |  | CNPF Form 17-A | 12/31/2022 | 4/14/2023 |  |  |  |  |
| 85 |  |  |  | CNPF Form 20-IS |  - | 5/23/2023 |  |  |  |  |
