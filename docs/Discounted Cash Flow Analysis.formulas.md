# Discounted Cash Flow Analysis.xlsx

Formula cells render as the value, then `=formula`. Percent-formatted cells are shown as %.


## DCF

| # | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P | Q | R | S |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Monde Nissin Corporation (MONDE) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 2 | Discounted Cash Flow Analysis |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 3 | (₱ in millions, fiscal year ending December 31) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 4 |  | Historical Period |  |  | CAGR | Bridge Yr. | Projection Period |  |  |  |  | CAGR |  |  |  |  |  |  |  |
| 5 |  | 2023 | 2024 | 2025 | '23 - '25 | 2026 | 2027 | 2028 | 2029 | 2030 | 2031 | '26 - '31 |  | Enterprise Value: Sensitivity Analysis |  |  |  |  |  |
| 6 | Sales | 80169.5 | 83120.1 | 86483 | 3.8630%<br>`=(D6/B6)^(1/2)-1` | 90755 | 95707 | 100088 | 104091.52 | 107734.72 | 110966.76 | 4.1033%<br>`=(K6/F6)^(1/5)-1` |  |  | Exit Multiple |  |  |  |  |
| 7 |    % growth | N/A | 3.6805%<br>`=(C6/B6)^(1/1)-1` | 4.0458%<br>`=(D6/C6)^(1/1)-1` |  | 4.9397%<br>`=(F6/D6)^(1/1)-1` | 5.4564%<br>`=(G6/F6)^(1/1)-1` | 4.5775%<br>`=(H6/G6)^(1/1)-1` | 4.0000%<br>`=(I6/H6)^(1/1)-1` | 3.5000%<br>`=(J6/I6)^(1/1)-1` | 3.0000%<br>`=(K6/J6)^(1/1)-1` |  |  | WACC | 5.6 | 6.1 | 6.6 | 7.1 | 7.6 |
| 8 | EBITDA | 14944 | 13415.7 | 14833.9 | -0.3691%<br>`=(D8/B8)^(1/2)-1` | 16987 | 17757 | 19005 | 19777.3888<br>`=I6*I9` | 20469.5968<br>`=J6*J9` | 21083.6844<br>`=K6*K9` | 4.4157%<br>`=(K8/F8)^(1/5)-1` |  | 10.5000% | 113475.11 | 119874.01 | 126272.91 | 132671.8 | 139070.7 |
| 9 |    % margin | 18.6405%<br>`=B8/B6` | 16.1401%<br>`=C8/C6` | 17.1524%<br>`=D8/D6` |  | 18.7174%<br>`=F8/F6` | 18.5535%<br>`=G8/G6` | 18.9883%<br>`=H8/H6` | 19.0000% | 19.0000% | 19.0000% |  |  | 11.0000% | 111408.16 | 117664.23 | 123920.3 | 130176.37 | 136432.44 |
| 10 | Depreciation & Amortization | 2772 | 2687.9 | 2826.7 | 0.9818%<br>`=(D10/B10)^(1/2)-1` | 3443 | 3262 | 3277 | 3435.02016<br>`=I6*I11` | 3555.24576<br>`=J6*J11` | 3661.90308<br>`=K6*K11` | 1.2404%<br>`=(K10/F10)^(1/5)-1` |  | 11.5000% | 109506.44 | 115631.33 | 121756.21 | 127881.1 | 134005.98 |
| 11 |    % sales | 3.4577%<br>`=B10/B6` | 3.2338%<br>`=C10/C6` | 3.2685%<br>`=D10/D6` |  | 3.7937%<br>`=F10/F6` | 3.4083%<br>`=G10/G6` | 3.2741%<br>`=H10/H6` | 3.3000% | 3.3000% | 3.3000% |  |  | 12.0000% | 107427.44 | 113409.17 | 119390.89 | 125372.62 | 131354.34 |
| 12 | EBIT | 12172<br>`=B8-B10` | 10727.8<br>`=C8-C10` | 12007.2<br>`=D8-D10` | -0.6793%<br>`=(D12/B12)^(1/2)-1` | 13544<br>`=F8-F10` | 14495<br>`=G8-G10` | 15728<br>`=H8-H10` | 16342.36864<br>`=I8-I10` | 16914.35104<br>`=J8-J10` | 17421.78132<br>`=K8-K10` | 5.1645%<br>`=(K12/F12)^(1/5)-1` |  | 12.5000% | 105510.64 | 111360.62 | 117210.59 | 123060.56 | 128910.54 |
| 13 |    % margin | 15.1828%<br>`=B12/B6` | 12.9064%<br>`=C12/C6` | 13.8839%<br>`=D12/D6` |  | 14.9237%<br>`=F12/F6` | 15.1452%<br>`=G12/G6` | 15.7142%<br>`=H12/H6` | 15.7000%<br>`=I12/I6` | 15.7000%<br>`=J12/J6` | 15.7000%<br>`=K12/K6` |  |  |  |  |  |  |  |  |
| 14 | Taxes (25%) | 3043<br>`=B12*0.25` | 2681.95<br>`=C12*0.25` | 3001.8<br>`=D12*0.25` |  | 3386<br>`=F12*0.25` | 3623.75<br>`=G12*0.25` | 3932<br>`=H12*0.25` | 4085.59216<br>`=I12*0.25` | 4228.58776<br>`=J12*0.25` | 4355.44533<br>`=K12*0.25` |  |  | Valuation Range |  | ₱113,409.17 - ₱130,176.37 |  |  |  |
| 15 | NOPAT | 9129<br>`=B12-B14` | 8045.85<br>`=C12-C14` | 9005.4<br>`=D12-D14` | -0.6793%<br>`=(D15/B15)^(1/2)-1` | 10158<br>`=F12-F14` | 10871.25<br>`=G12-G14` | 11796<br>`=H12-H14` | 12256.77648<br>`=I12-I14` | 12685.76328<br>`=J12-J14` | 13066.33599<br>`=K12-K14` | 5.1645%<br>`=(K15/F15)^(1/5)-1` |  |    Exit Multiple Range |  | 6.1x - 7.1x |  |  |  |
| 16 | Plus: D&A | 2772<br>`=B10` | 2687.9<br>`=C10` | 2826.7<br>`=D10` |  | 3443<br>`=F10` | 3262<br>`=G10` | 3277<br>`=H10` | 3435.02016<br>`=I10` | 3555.24576<br>`=J10` | 3661.90308<br>`=K10` |  |  |    WACC Range |  | 11.0% - 12.0% |  |  |  |
| 17 | Less: CapEx | 3641.3 | 4823.1 | 4719.1 |  | 6004 | 5131 | 4783 | 4475.93536<br>`=I6*I18` | 4093.91936<br>`=J6*J18` | 3661.90308<br>`=K6*K18` |  |  |  |  |  |  |  |  |
| 18 |    % sales | 4.5420%<br>`=B17/B6` | 5.8026%<br>`=C17/C6` | 5.4567%<br>`=D17/D6` |  | 6.6156%<br>`=F17/F6` | 5.3612%<br>`=G17/G6` | 4.7788%<br>`=H17/H6` | 4.3000% | 3.8000% | 3.3000% |  |  |  |  |  |  |  |  |
| 19 | Less: Inc./(Dec.) in NWC |  |  |  |  |  | 382.93 | 338.78 | 309.59 | 281.72 | 249.93 |  |  |  |  |  |  |  |  |
| 20 | Unlevered Free Cash Flow |  |  |  |  |  | 8619.32<br>`=G15+G16-G17-G19` | 9951.22<br>`=H15+H16-H17-H19` | 10906.27128<br>`=I15+I16-I17-I19` | 11865.36968<br>`=J15+J16-J17-J19` | 12816.40599<br>`=K15+K16-K17-K19` |  |  |  |  |  |  |  |  |
| 21 |    WACC |  |  |  |  |  | 11.4715% | 11.4715% | 11.4715% | 11.4715% | 11.4715% |  |  |  |  |  |  |  |  |
| 22 |    Discount Period (mid-year convention) |  |  |  |  |  | 0.5 | 1.5 | 2.5 | 3.5 | 4.5 |  |  |  |  |  |  |  |  |
| 23 |    Discount Factor |  |  |  |  |  | 0.947148652<br>`=(1)/(1+G21)^(G22)` | 0.8496781231<br>`=(1)/(1+H21)^(H22)` | 0.7622382308<br>`=(1)/(1+I21)^(I22)` | 0.6837967282<br>`=(1)/(1+J21)^(J22)` | 0.6134275959<br>`=(1)/(1+K21)^(K22)` |  |  |  |  |  |  |  |  |
| 24 | Present Value of Free Cash Flow |  |  |  |  |  | 8163.777319<br>`=G20*G23` | 8455.333932<br>`=H20*H23` | 8313.176925<br>`=I20*I23` | 8113.500966<br>`=J20*J23` | 7861.937115<br>`=K20*K23` |  |  |  |  |  |  |  |  |
| 25 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 26 | Enterprise Value |  |  | Implied Equity Value and Share Price |  |  |  |  | Implied Perpetuity Growth Rate |  |  |  |  |  |  |  |  |  |  |
| 27 | Cumulative Present Value of FCF | 40907.72626<br>`=SUM(G24:K24)` |  | Enterprise Value |  |  | 121756.2133<br>`=B36` |  | Terminal Value (EMM) |  | 139152.317<br>`=B31` |  |  |  |  |  |  |  |  |
| 28 |  |  |  | Less: Total Debt |  |  | 5170.1 |  | WACC |  | 11.4715%<br>`=K21` |  |  |  |  |  |  |  |  |
| 29 | Terminal Yr. EBITDA | 21083.6844<br>`=K8` |  | Less: Preferred Stock |  |  | - |  | FCF (Terminal Year) |  | 12816.40599<br>`=K20` |  |  |  |  |  |  |  |  |
| 30 |    Exit Multiple (1) | 6.6 |  | Less: Noncontrolling Interest |  |  | 120.6 |  | Implied Perpetuity Growth Rate |  | 1.5923%<br>`=((K27*K28)-(K29*(1+K28)^0.5))/(K27+(K29*(1+K28)^0.5))` |  |  |  |  |  |  |  |  |
| 31 | Terminal Value (EMM) | 139152.317<br>`=B29*B30` |  | Plus: Cash and Cash Equivalents |  |  | 14379.9 |  |  |  |  |  |  |  |  |  |  |  |  |
| 32 |    Discount Factor (2) | 0.5810071205<br>`=(1)/(1+K21)^(5)` |  | Implied Equity Value |  |  | 130845.4133<br>`=G27-G28-G30+G31` |  | Implied EV / EBITDA |  |  |  |  |  |  |  |  |  |  |
| 33 | Present Value of Terminal Value | 80848.48704<br>`=B31*B32` |  |    Fully Diluted Shares Outstanding |  |  | 17968.61 |  | Enterprise Value |  | 121756.2133<br>`=B36` |  |  |  |  |  |  |  |  |
| 34 |    % of Enterprise Value | 66.4019%<br>`=B33/B36` |  | Implied Share Price |  |  | 7.281888432<br>`=G32/G33` |  | LTM EBITDA |  | 16147.9 |  |  |  |  |  |  |  |  |
| 35 |  |  |  |  |  |  |  |  | Implied EV / EBITDA |  | 7.540064856<br>`=K33/K34` |  |  |  |  |  |  |  |  |
| 36 | Enterprise Value | 121756.2133<br>`=B27+B33` |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 37 | (1) The median of the peer group's LTM EV/EBITDA |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 38 | multiples. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 39 | (2) 0.5 isn't deducted from n = 5 because EMM |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 40 | assumes the business is sold at the exact end of the |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 41 | final year. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |

## Supporting Calculations

| # | A | B | C | D | E | F | G | H | I | J |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Working Capital Projections |  |  |  |  |  |  |  |  |  |
| 2 | (₱ in millions, fiscal year ending December 31) |  |  |  |  |  |  |  |  |  |
| 3 |  | Historical Period |  |  | Bridge Yr. | Projection Period |  |  |  |  |
| 4 |  | 2023 | 2024 | 2025 | 2026 | 2027 | 2028 | 2029 | 2030 | 2031 |
| 5 | Sales | 80169.5 | 83120.1 | 86483 | 90755 | 95707 | 100088 | 104091.52 | 107734.72 | 110966.76 |
| 6 | COGS (excl. D&A) | 52669.7 | 51742.5 | 54837.9 | 57546.72727<br>`=E5*E7` | 60686.73491<br>`=F5*F7` | 63464.67786<br>`=G5*G7` | 66003.26497<br>`=H5*H7` | 68313.37722<br>`=I5*I7` | 70362.77752<br>`=J5*J7` |
| 7 |    % sales | 65.6979%<br>`=B6/B5` | 62.2503%<br>`=C6/C5` | 63.4089%<br>`=D6/D5` | 63.4089%<br>`=D7` | 63.4089%<br>`=E7` | 63.4089%<br>`=F7` | 63.4089%<br>`=G7` | 63.4089%<br>`=H7` | 63.4089%<br>`=I7` |
| 8 |  |  |  |  |  |  |  |  |  |  |
| 9 | Current Assets |  |  |  |  |  |  |  |  |  |
| 10 | Accounts Receivable | 6410.14 | 7709.72 | 8400.98 | 8815.963136<br>`=(E5/365)*E27` | 9297.00164<br>`=(F5/365)*F27` | 9722.573063<br>`=(G5/365)*G27` | 10111.47599<br>`=(H5/365)*H27` | 10465.37733<br>`=(I5/365)*I27` | 10779.3385<br>`=(J5/365)*J27` |
| 11 | Inventory | 9186.53 | 8920.79 | 8971.75 | 9414.927457<br>`=(E6/365)*E28` | 9928.648142<br>`=(F6/365)*F28` | 10383.13326<br>`=(G6/365)*G28` | 10798.45859<br>`=(H6/365)*H28` | 11176.40431<br>`=(I6/365)*I28` | 11511.69628<br>`=(J6/365)*J28` |
| 12 | Prepaid Expenses and Other Current Assets | 1099.67 | 1326.15 | 1756.24 | 1842.992972<br>`=E5*E29` | 1943.554938<br>`=F5*F29` | 2032.52141<br>`=G5*G29` | 2113.822267<br>`=H5*H29` | 2187.805981<br>`=I5*I29` | 2253.440128<br>`=J5*J29` |
| 13 |    Total Current Assets | 16696.34<br>`=SUM(B10:B12)` | 17956.66<br>`=SUM(C10:C12)` | 19128.97<br>`=SUM(D10:D12)` | 20073.88356<br>`=SUM(E10:E12)` | 21169.20472<br>`=SUM(F10:F12)` | 22138.22774<br>`=SUM(G10:G12)` | 23023.75685<br>`=SUM(H10:H12)` | 23829.58763<br>`=SUM(I10:I12)` | 24544.4749<br>`=SUM(J10:J12)` |
| 14 |  |  |  |  |  |  |  |  |  |  |
| 15 | Current Liabilities |  |  |  |  |  |  |  |  |  |
| 16 | Accounts Payable | 4961.12 | 6309.88 | 6143.84 | 6447.327211<br>`=(E6/365)*E32` | 6799.122312<br>`=(F6/365)*F32` | 7110.352993<br>`=(G6/365)*G32` | 7394.767113<br>`=(H6/365)*H32` | 7653.583735<br>`=(I6/365)*I32` | 7883.191133<br>`=(J6/365)*J32` |
| 17 | Accrued Liabilities | 1539.02 | 2077.09 | 2418.84 | 2538.323418<br>`=E5*E33` | 2676.825733<br>`=F5*F33` | 2799.357769<br>`=G5*G33` | 2911.33208<br>`=H5*H33` | 3013.228613<br>`=I5*I33` | 3103.625426<br>`=J5*J33` |
| 18 | Other Current Liabilities | 5184.18 | 4163.35 | 3878.7 | 4070.29611<br>`=E5*E34` | 4292.389729<br>`=F5*F34` | 4488.87441<br>`=G5*G34` | 4668.429386<br>`=H5*H34` | 4831.824271<br>`=I5*I34` | 4976.778928<br>`=J5*J34` |
| 19 |    Total Current Liabilities | 11684.32<br>`=SUM(B16:B18)` | 12550.32<br>`=SUM(C16:C18)` | 12441.38<br>`=SUM(D16:D18)` | 13055.94674<br>`=SUM(E16:E18)` | 13768.33777<br>`=SUM(F16:F18)` | 14398.58517<br>`=SUM(G16:G18)` | 14974.52858<br>`=SUM(H16:H18)` | 15498.63662<br>`=SUM(I16:I18)` | 15963.59549<br>`=SUM(J16:J18)` |
| 20 |  |  |  |  |  |  |  |  |  |  |
| 21 | Net Working Capital | 5012.02<br>`=B13-B19` | 5406.34<br>`=C13-C19` | 6687.59<br>`=D13-D19` | 7017.936825<br>`=E13-E19` | 7400.866946<br>`=F13-F19` | 7739.642565<br>`=G13-G19` | 8049.228267<br>`=H13-H19` | 8330.951009<br>`=I13-I19` | 8580.879416<br>`=J13-J19` |
| 22 |    % sales | 6.2518%<br>`=B21/B5` | 6.5043%<br>`=C21/C5` | 7.7328%<br>`=D21/D5` | 7.7328%<br>`=E21/E5` | 7.7328%<br>`=F21/F5` | 7.7328%<br>`=G21/G5` | 7.7328%<br>`=H21/H5` | 7.7328%<br>`=I21/I5` | 7.7328%<br>`=J21/J5` |
| 23 | ΔNWC |  | 394.32<br>`=C21-B21` | 1281.25<br>`=D21-C21` | 330.3468252<br>`=E21-D21` | 382.9301213<br>`=F21-E21` | 338.7756182<br>`=G21-F21` | 309.5857026<br>`=H21-G21` | 281.7227419<br>`=I21-H21` | 249.9284065<br>`=J21-I21` |
| 24 |  |  |  |  |  |  |  |  |  |  |
| 25 | Assumptions |  |  |  |  |  |  |  |  |  |
| 26 | Current Assets |  |  |  |  |  |  |  |  |  |
| 27 | Days Sales Outstanding | 29.18442924<br>`=(B10/B5)*365` | 33.85520229<br>`=(C10/C5)*365` | 35.45619023<br>`=(D10/D5)*365` | 35.45619023<br>`=D27` | 35.45619023<br>`=E27` | 35.45619023<br>`=F27` | 35.45619023<br>`=G27` | 35.45619023<br>`=H27` | 35.45619023<br>`=I27` |
| 28 | Days Inventory Held | 63.66247482<br>`=(B11/B6)*365` | 62.92870174<br>`=(C11/C6)*365` | 59.71579419<br>`=(D11/D6)*365` | 59.71579419<br>`=D28` | 59.71579419<br>`=E28` | 59.71579419<br>`=F28` | 59.71579419<br>`=G28` | 59.71579419<br>`=H28` | 59.71579419<br>`=I28` |
| 29 | Prepaid Expenses and Other Current Assets (% of sales) | 1.3717%<br>`=B12/B5` | 1.5955%<br>`=C12/C5` | 2.0307%<br>`=D12/D5` | 2.0307%<br>`=D29` | 2.0307%<br>`=E29` | 2.0307%<br>`=F29` | 2.0307%<br>`=G29` | 2.0307%<br>`=H29` | 2.0307%<br>`=I29` |
| 30 |  |  |  |  |  |  |  |  |  |  |
| 31 | Current Liabilities |  |  |  |  |  |  |  |  |  |
| 32 | Days Payable Outstanding | 34.38046543<br>`=(B16/B6)*365` | 44.51091849<br>`=(C16/C6)*365` | 40.89328001<br>`=(D16/D6)*365` | 40.89328001<br>`=D32` | 40.89328001<br>`=E32` | 40.89328001<br>`=F32` | 40.89328001<br>`=G32` | 40.89328001<br>`=H32` | 40.89328001<br>`=I32` |
| 33 | Accrued Liabilities (% of sales) | 1.9197%<br>`=B17/B5` | 2.4989%<br>`=C17/C5` | 2.7969%<br>`=D17/D5` | 2.7969%<br>`=D33` | 2.7969%<br>`=E33` | 2.7969%<br>`=F33` | 2.7969%<br>`=G33` | 2.7969%<br>`=H33` | 2.7969%<br>`=I33` |
| 34 | Other Current Liabilities (% of sales) | 6.4665%<br>`=B18/B5` | 5.0088%<br>`=C18/C5` | 4.4849%<br>`=D18/D5` | 4.4849%<br>`=D34` | 4.4849%<br>`=E34` | 4.4849%<br>`=F34` | 4.4849%<br>`=G34` | 4.4849%<br>`=H34` | 4.4849%<br>`=I34` |
| 35 |  |  |  |  |  |  |  |  |  |  |
| 36 | Cost of Debt Calculation |  |  |  |  |  |  |  |  |  |
| 37 | (₱ in millions) |  |  |  |  |  |  |  |  |  |
| 38 |  | Amount | Interest Expense | Instrument Yield |  |  |  |  |  |  |
| 39 | Lease Liabilities | 2557.3 | 173.9 | 6.8000% |  |  |  |  |  |  |
| 40 | Loans Payable (Bank Facilities/Term Loans) | 1638.4 | 146.3 | 8.9300% |  |  |  |  |  |  |
| 41 | Acceptances and Trust Receipts Payable (Trade Finance) | 1040 | 62 | 5.9600% |  |  |  |  |  |  |
| 42 |    Total Debt | 5235.7<br>`=SUM(B39:B41)` |  |  |  |  |  |  |  |  |
| 43 |  |  |  |  |  |  |  |  |  |  |
| 44 | Overall Pre-tax Cost of Debt | 7.2997%<br>`=((B39/B42)*D39)+((B40/B42)*D40)+((B41/B42)*D41)` |  |  |  |  |  |  |  |  |
| 45 | Overall After-tax Cost of Debt (t = 25%) | 5.4748%<br>`=B44*(1-0.25)` |  |  |  |  |  |  |  |  |
| 46 |  |  |  |  |  |  |  |  |  |  |
| 47 | Cost of Equity Calculation |  |  |  |  |  |  |  |  |  |
| 48 | Comparables: | Raw Beta | D/E Ratio | Unlevered Beta |  |  |  |  |  |  |
| 49 | Universal Robina (URC) | 0.82 | 19.9700% | 0.7131830141<br>`=(B49)/(1+C49*(1-0.25))` |  |  |  |  |  |  |
| 50 | Century Pacific (CNPF) | 0.74 | 12.6600% | 0.6758299466<br>`=(B50)/(1+C50*(1-0.25))` |  |  |  |  |  |  |
| 51 | San Miguel F&B (FB) | 0.38 | 34.2100% | 0.3024093269<br>`=(B51)/(1+C51*(1-0.25))` |  |  |  |  |  |  |
| 52 |  |  |  |  |  |  |  |  |  |  |
| 53 | Peer Group Median Unlevered Beta | 0.6758299466<br>`=D50` |  |  |  |  |  |  |  |  |
| 54 |    Target Re-levered Beta (1) | 0.7770523768<br>`=B53*(1+C49*(1-0.25))` |  |  |  |  |  |  |  |  |
| 55 |  |  |  |  |  |  |  |  |  |  |
| 56 | Risk-free Rate (2) | 7.2300% |  |  |  |  |  |  |  |  |
| 57 | Equity Risk Premium (3) | 7.0000% |  |  |  |  |  |  |  |  |
| 58 | Size Premium (4) | 0.0000% |  |  |  |  |  |  |  |  |
| 59 | Cost of Equity | 12.6694%<br>`=B56+(B54*B57)+B58` |  |  |  |  |  |  |  |  |
| 60 | Notes: |  |  |  |  |  |  |  |  |  |
| 61 | (1) Derived from the peer median, re-levered to Monde's target capital structure. |  |  |  |  |  |  |  |  |  |
| 62 | (2) The yield on the Philippine 10-Year Government Bond as of August 14, 2026. |  |  |  |  |  |  |  |  |  |
| 63 | (3) The standard baseline market risk premium (MRP) applied to Philippine equities in 2026. |  |  |  |  |  |  |  |  |  |
| 64 | (4) Given Monde Nissin's ~$2.2B USD equity capitalization, a size premium is excluded, as the company |  |  |  |  |  |  |  |  |  |
| 65 | operates well above small-cap risk thresholds. |  |  |  |  |  |  |  |  |  |
| 66 |  |  |  |  |  |  |  |  |  |  |
| 67 | WACC Calculation |  |  |  |  |  |  |  |  |  |
| 68 | Target Capital Structure (1): |  |  |  |  |  |  |  |  |  |
| 69 |    Debt Portion | 16.6500% |  |  |  |  |  |  |  |  |
| 70 |    Equity Portion | 83.3500% |  |  |  |  |  |  |  |  |
| 71 |  |  |  |  |  |  |  |  |  |  |
| 72 | Cost of Debt (After-tax) | 5.4748%<br>`=B45` |  |  |  |  |  |  |  |  |
| 73 | Cost of Equity | 12.6694%<br>`=B59` |  |  |  |  |  |  |  |  |
| 74 |  |  |  |  |  |  |  |  |  |  |
| 75 | WACC | 11.4715%<br>`=(B70*B73)+(B69*B72)` |  |  |  |  |  |  |  |  |
| 76 | Note: |  |  |  |  |  |  |  |  |  |
| 77 | (1) Reflects the median capital structure of Monde Nissin’s comparable peers |  |  |  |  |  |  |  |  |  |
| 78 | (URC, CNPF, and FB). The peer median was utilized to represent an optimal |  |  |  |  |  |  |  |  |  |
| 79 | target capital structure, as Monde Nissin's current debt weighting falls |  |  |  |  |  |  |  |  |  |
| 80 | significantly below the peer group range. |  |  |  |  |  |  |  |  |  |

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

## Comparable #1

| # | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Universal Robina Corporation (URC) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 2 | Comparable #1 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 4 | General Information |  |  | Reported Income Statement |  |  |  |  |  |  |  | Balance Sheet Data |  |  |  |  |
| 5 | Company Name | Universal Robina Corporation |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  | (₱ in millions) |  |  |  |  |
| 6 | Ticker | URC |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  | 2025A | Q2 2026 |  |  |
| 7 | Stock Exchange | Philippine Stock Exchange (PSE) |  | Sales | 157752.18 | 161867.24 | 168009.18 | 85886.44 | 89338.84 | 171461.58<br>`=G7+I7-H7` |  | Cash and Cash Equivalents | 11226.61 | 13175.58 |  |  |
| 8 | Fiscal Year Ending | 2026-12-31 00:00:00 |  | COGS (incl. D&A) | 115010.46 | 117837.94 | 123699.93 | 62371.23 | 64559.28 | 125887.98<br>`=G8+I8-H8` |  | Accounts Receivable | 22244.39 | 19553.6 |  |  |
| 9 | Marginal Tax Rate | 25.0000% |  | Gross Profit | 42741.72<br>`=E7-E8` | 44029.3<br>`=F7-F8` | 44309.25<br>`=G7-G8` | 23515.21<br>`=H7-H8` | 24779.56<br>`=I7-I8` | 45573.6<br>`=J7-J8` |  | Inventories | 37886.49 | 42953.39 |  |  |
| 10 |  |  |  | SG&A | 25353.11 | 27377.27 | 28179.5 | 14093.55 | 15389.58 | 29475.53<br>`=G10+I10-H10` |  | Prepaids and Other Current Assets | 6160.65 | 4665.88 |  |  |
| 11 | Selected Market Data |  |  | EBIT | 17388.61<br>`=E9-E10` | 16652.03<br>`=F9-F10` | 16129.75<br>`=G9-G10` | 9421.66<br>`=H9-H10` | 9389.98<br>`=I9-I10` | 16098.07<br>`=J9-J10` |  | Total Current Assets | 77518.14<br>`=SUM(M7:M10)` | 80348.45<br>`=SUM(N7:N10)` |  |  |
| 12 | (In ₱ millions, except per share data. Stock Data is as of August 14, 2026.) |  |  | Other Expense / (Income) | 359.5 | -109.61 | 1499.82 | 465.51 | -148.93 | 885.38<br>`=G12+I12-H12` |  |  |  |  |  |  |
| 13 | Current Price | 62.1 |  | Net Finance Costs / (Income) | 1347.7 | 1350.05 | 1195.82 | 625.03 | 545.06 | 1115.85<br>`=G13+I13-H13` |  | Property, Plant and Equipment, net | 70605.21 | 71803.6 |  |  |
| 14 | % of 52-week High | 72.8873%<br>`=B13/B15` |  | Pre-tax Income | 15681.41<br>`=E11-E12-E13` | 15411.59<br>`=F11-F12-F13` | 13434.11<br>`=G11-G12-G13` | 8331.12<br>`=H11-H12-H13` | 8993.85<br>`=I11-I12-I13` | 14096.84<br>`=J11-J12-J13` |  | Goodwill and Intangible Assets | 27938.2 | 28864.5 |  |  |
| 15 | 52-week High Price | 85.2 |  | Income Taxes | 2976.82 | 3057.96 | 2631.08 | 1648.77 | 1791.98 | 2774.29<br>`=G15+I15-H15` |  | Other Assets | 6987.93 | 5836.07 |  |  |
| 16 | 52-week Low Price | 55.9 |  | Non-controlling Interest | 613.31 | 692.09 | 607.14 | 407.26 | 291.87 | 491.75<br>`=G16+I16-H16` |  | Total Assets | 183049.48<br>`=M11+SUM(M13:M15)` | 186852.62<br>`=N11+SUM(N13:N15)` |  |  |
| 17 | Dividend Per Share (MRQ) | 2.1 |  | Net Income | 12091.28<br>`=E14-E15-E16` | 11661.54<br>`=F14-F15-F16` | 10195.89<br>`=G14-G15-G16` | 6275.09<br>`=H14-H15-H16` | 6910<br>`=I14-I15-I16` | 10830.8<br>`=J14-J15-J16` |  |  |  |  |  |  |
| 18 |  |  |  | Effective Tax Rate | 19.0000% | 19.8000% | 19.6000% | 19.8000% | 19.9000% | 19.7000% |  | Accounts Payable & Accrued Liabilities | 28416.78 | 28268.57 |  |  |
| 19 | Fully Diluted Shares Outstanding | 2134.78<br>`=J20` |  |  |  |  |  |  |  |  |  | Other Current Liabilities | 323.86 | 495.61 |  |  |
| 20 | Equity Value | 132569.838<br>`=B13*B19` |  | Weighted Avg. Diluted Shares | 2178.61 | 2163.56 | 2137.79 | 2140.71 | 2137 | 2134.78 |  | Total Current Liabilities (excl. debt) | 28740.64<br>`=M18+M19` | 28764.18<br>`=N18+N19` |  |  |
| 21 |  |  |  | Diluted EPS | 5.549997475<br>`=E17/E20` | 5.389977629<br>`=F17/F20` | 4.769359946<br>`=G17/G20` | 2.931312508<br>`=H17/H20` | 3.233504913<br>`=I17/I20` | 5.073497035<br>`=J17/J20` |  |  |  |  |  |  |
| 22 | Plus: Total Debt | 26478.18<br>`=N22` |  |  |  |  |  |  |  |  |  | Total Debt | 26146.15 | 26478.18 |  |  |
| 23 | Plus: Preferred Stock | - |  | Adjusted Income Statement |  |  |  |  |  |  |  | Other Long-Term Liabilities | 2778.41 | 2879.14 |  |  |
| 24 | Plus: Non-controlling Interest | 1783.39<br>`=N26` |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  | Total Liabilities | 57665.2<br>`=M20+M22+M23` | 58121.5<br>`=N20+N22+N23` |  |  |
| 25 | Less: Cash and Cash Equivalents | 13175.58<br>`=N7` |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  |  |  |  |  |
| 26 | Enterprise Value | 147655.828<br>`=B20+B22+B24-B25` |  | Reported Gross Profit | 42741.72<br>`=E9` | 44029.3<br>`=F9` | 44309.25<br>`=G9` | 23515.21<br>`=H9` | 24779.56<br>`=I9` | 45573.6<br>`=J9` |  | Non-controlling Interest | 1487.01 | 1783.39 |  |  |
| 27 |  |  |  | Non-recurring Items in COGS | - | - | - | - | - | - |  | Preferred Stock | - | - |  |  |
| 28 | LTM ROI Ratios |  |  | Adjusted Gross Profit | 42741.72<br>`=E26` | 44029.3<br>`=F26` | 44309.25<br>`=G26` | 23515.21<br>`=H26` | 24779.56<br>`=I26` | 45573.6<br>`=J26` |  | Shareholder's Equity | 123897.27 | 126947.73 |  |  |
| 29 | Return on Invested Capital | 8.5526%<br>`=(J34*(1-B9))/((M28+N28+M22+N22+M26+N26-M7-N7)/2)` |  | % margin | 27.0942%<br>`=E28/E7` | 27.2009%<br>`=F28/F7` | 26.3731%<br>`=G28/G7` | 27.3794%<br>`=H28/H7` | 27.7366%<br>`=I28/I7` | 26.5795%<br>`=J28/J7` |  | Total Liabilities and Equity | 183049.48<br>`=M24+M26+M28` | 186852.62<br>`=N24+N26+N28` |  |  |
| 30 | Return on Equity | 8.8876%<br>`=J46/((M28+N28)/2)` |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 31 | Return on Assets | 6.0270%<br>`=J46/((M16+N16)/2)` |  | Reported EBIT | 17388.61<br>`=E11` | 16652.03<br>`=F11` | 16129.75<br>`=G11` | 9421.66<br>`=H11` | 9389.98<br>`=I11` | 16098.07<br>`=J11` |  | Balance Check | 0<br>`=M16-M29` | 0<br>`=N16-N29` |  |  |
| 32 | Dividend Yield | 13.5266%<br>`=(B17*4)/B13` |  | Non-recurring Items in COGS | - | - | - | - | - | - |  |  |  |  |  |  |
| 33 |  |  |  | Other Non-recurring Items (Operating) | - | - | - | - | - | - |  | Growth Rates |  |  |  |  |
| 34 | LTM Credit Statistics |  |  | Adjusted EBIT | 17388.61<br>`=E31` | 16652.03<br>`=F31` | 16129.75<br>`=G31` | 9421.66<br>`=H31` | 9389.98<br>`=I31` | 16098.07<br>`=J31` |  |  | Sales | EBITDA | FCF/Share | EPS |
| 35 | Leverage Ratios |  |  | % margin | 11.0227%<br>`=E34/E7` | 10.2875%<br>`=F34/F7` | 9.6005%<br>`=G34/G7` | 10.9699%<br>`=H34/H7` | 10.5105%<br>`=I34/I7` | 9.3887%<br>`=J34/J7` |  | Historical |  |  |  |  |
| 36 | Debt / Total Capitalization | 17.0597%<br>`=N22/(N28+N22+N26)` |  |  |  |  |  |  |  |  |  | 1-year | 3.7944%<br>`=((G7/F7)^(1/1))-1` | 2.1586%<br>`=((G38/F38)^(1/1))-1` | -61.9428%<br>`=((G62/F62)^(1/1))-1` | -3.1085%<br>`=((G49/F49)^(1/1))-1` |
| 37 | Total Debt / EBITDA | 1.179753714<br>`=N22/J38` |  | Depreciation and Amortization (D&A) | 6361.33 | 4968.71 | 5957.69 | 2840.67 | 3228.73 | 6345.75<br>`=G37+I37-H37` |  | 2-year CAGR | 3.1998%<br>`=((G7/E7)^(1/2))-1` | -3.5635%<br>`=((G38/E38)^(1/2))-1` | 180.6515%<br>`=((G62/E62)^(1/2))-1` | -3.3460%<br>`=((G49/E49)^(1/2))-1` |
| 38 | Net Debt / EBITDA | 0.5927065892<br>`=(N22-N7)/J38` |  | Adjusted EBITDA | 23749.94<br>`=E34+E37` | 21620.74<br>`=F34+F37` | 22087.44<br>`=G34+G37` | 12262.33<br>`=H34+H37` | 12618.71<br>`=I34+I37` | 22443.82<br>`=J34+J37` |  | Estimated |  |  |  |  |
| 39 |  |  |  | % margin | 15.0552%<br>`=E38/E7` | 13.3571%<br>`=F38/F7` | 13.1466%<br>`=G38/G7` | 14.2774%<br>`=H38/H7` | 14.1246%<br>`=I38/I7` | 13.0897%<br>`=J38/J7` |  | 1-year | 4.8008%<br>`=((F71/G7)^(1/1))-1` | 7.9980%<br>`=((F73/G38)^(1/1))-1` | 49.9434%<br>`=((F79/G62)^(1/1))-1` | 8.0598%<br>`=((F77/G49)^(1/1))-1` |
| 40 | Coverage Ratios (1) |  |  |  |  |  |  |  |  |  |  | 2-year CAGR | 4.6653%<br>`=((G71/G7)^(1/2))-1` | 5.2360%<br>`=((G73/G38)^(1/2))-1` | 39.4751%<br>`=((G79/G62)^(1/2))-1` | 7.8203%<br>`=((G77/G49)^(1/2))-1` |
| 41 | EBITDA / Interest Expense | 16.31067862<br>`=J38/1376.02` |  | Reported Net Income | 12091.28<br>`=E17` | 11661.54<br>`=F17` | 10195.89<br>`=G17` | 6275.09<br>`=H17` | 6910<br>`=I17` | 10830.8<br>`=J17` |  | Long-term (1) |  |  |  | 8.9000% |
| 42 | (EBITDA - CapEx) / Interest Expense | 11.57339283<br>`=(J38-J58)/1376.02` |  | Non-recurring Items in COGS | - | - | - | - | - | - |  | Note: |  |  |  |  |
| 43 | EBIT / Interest Expense | 11.69900874<br>`=J34/1376.02` |  | Other Non-recurring Items (Operating) | -<br>`=E33` | -<br>`=F33` | -<br>`=G33` | -<br>`=H33` | -<br>`=I33` | -<br>`=J33` |  | (1) Sourced directly from equity research consensus estimates for URC's expected long-term earnings trajectory. |  |  |  |  |
| 44 | Note: |  | (1) | Non-operating Non-recurring Items | -178.68 | -281.82 | 1027.6 | 289.98 | -311.13 | 426.49<br>`=G44+I44-H44` |  |  |  |  |  |  |
| 45 | (1) Calculated using the LTM finance costs as the denominator. |  | (2) | Tax Adjustment | 43.39 | 68.26 | -263.49 | -73.07 | 80.12 | -110.3<br>`=G45+I45-H45` |  |  |  |  |  |  |
| 46 |  |  |  | Adjusted Net Income | 11955.99<br>`=E41+E44+E45` | 11447.98<br>`=F41+F44+F45` | 10960<br>`=G41+G44+G45` | 6492<br>`=H41+H44+H45` | 6678.99<br>`=I41+I44+I45` | 11146.99<br>`=J41+J44+J45` |  |  |  |  |  |  |
| 47 |  |  |  | % margin | 7.5790%<br>`=E46/E7` | 7.0725%<br>`=F46/F7` | 6.5235%<br>`=G46/G7` | 7.5588%<br>`=H46/H7` | 7.4760%<br>`=I46/I7` | 6.5012%<br>`=J46/J7` |  |  |  |  |  |  |
| 48 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 49 |  |  |  | Adjusted Diluted EPS | 5.487898247<br>`=E46/E20` | 5.291269944<br>`=F46/F20` | 5.126789816<br>`=G46/G20` | 3.032638704<br>`=H46/H20` | 3.125404773<br>`=I46/I20` | 5.221610658<br>`=J46/J20` |  |  |  |  |  |  |
| 50 |  |  |  | Notes: |  |  |  |  |  |  |  |  |  |  |  |  |
| 51 |  |  |  | (1) Normalizes one-off and non-operational charges/gains presented below EBIT, including asset impairment losses (e.g., Polypropylene Packaging plant closure and typhoon damage), net results from discontinued China operations, one-off foreign exchange gains/losses, mark-to-market valuations on FVTPL financial assets, and one-off fixed asset disposal gains. |  |  |  |  |  |  |  |  |  |  |  |  |
| 52 |  |  |  | (2) Reflects the net income tax impact associated with non-operating adjustments to arrive at recurring Core Net Income attributable to equity holders of the parent. |  |  |  |  |  |  |  |  |  |  |  |  |
| 53 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 54 |  |  |  | Cash Flow Statement Data |  |  |  |  |  |  |  |  |  |  |  |  |
| 55 |  |  |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  |  |  |  |  |  |
| 56 |  |  |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  |  |  |  |  |
| 57 |  |  |  | Cash From Operations (CFO) | 9086.94 | 18981.22 | 11273.62 | 3302.79 | 9303.81 | 17274.64<br>`=G57+I57-H57` |  |  |  |  |  |  |
| 58 |  |  |  | Capital Expenditures (CapEx) | 8454.22 | 5976.57 | 6383.36 | 2826.56 | 2961.8 | 6518.6<br>`=G58+I58-H58` |  |  |  |  |  |  |
| 59 |  |  |  | % sales | 5.3592%<br>`=E58/E7` | 3.6923%<br>`=F58/F7` | 3.7994%<br>`=G58/G7` | 3.2910%<br>`=H58/H7` | 3.3152%<br>`=I58/I7` | 3.8018%<br>`=J58/J7` |  |  |  |  |  |  |
| 60 |  |  |  | Free Cash Flow (FC) | 632.72<br>`=E57-E58` | 13004.65<br>`=F57-F58` | 4890.26<br>`=G57-G58` | 476.23<br>`=H57-H58` | 6342.01<br>`=I57-I58` | 10756.04<br>`=J57-J58` |  |  |  |  |  |  |
| 61 |  |  |  | % margin | 0.4011%<br>`=E60/E7` | 8.0341%<br>`=F60/F7` | 2.9107%<br>`=G60/G7` | 0.5545%<br>`=H60/H7` | 7.0988%<br>`=I60/I7` | 6.2731%<br>`=J60/J7` |  |  |  |  |  |  |
| 62 |  |  |  | FCF / Share | 0.2904237105<br>`=E60/E20` | 6.010764666<br>`=F60/F20` | 2.287530581<br>`=G60/G20` | 0.2224635752<br>`=H60/H20` | 2.967716425<br>`=I60/I20` | 5.038477033<br>`=J60/J20` |  |  |  |  |  |  |
| 63 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 64 |  |  |  | Depreciation and Amortization (D&A) | 6403.09 | 4987.52 | 5958.17 | 2840.67<br>`=H37` | 3228.73<br>`=I37` | 6346.23<br>`=G64+I64-H64` |  |  |  |  |  |  |
| 65 |  |  |  | % sales | 4.0590%<br>`=E64/E7` | 3.0812%<br>`=F64/F7` | 3.5463%<br>`=G64/G7` | 3.3075%<br>`=H64/H7` | 3.6140%<br>`=I64/I7` | 3.7013%<br>`=J64/J7` |  |  |  |  |  |  |
| 66 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 67 |  |  |  | Trading Multiples |  |  |  |  |  |  |  |  |  |  |  |  |
| 68 |  |  |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  |  |  |  |  |  |
| 69 |  |  |  |  | LTM | 2026E | 2027E | 2028E |  |  |  |  |  |  |  |  |
| 70 |  |  |  | EV / Sales | 0.861159847<br>`=$B$26/E71` | 0.8385962118<br>`=$B$26/F71` | 0.8022549619<br>`=$B$26/G71` | 0.7669755294<br>`=$B$26/H71` |  |  |  |  |  |  |  |  |
| 71 |  |  |  | Metric | 171461.58<br>`=J7` | 176075 | 184051 | 192517 |  |  |  |  |  |  |  |  |
| 72 |  |  |  | EV / EBITDA | 6.578908047<br>`=$B$26/E73` | 6.18998189<br>`=$B$26/F73` | 6.036377417<br>`=$B$26/G73` | 5.663604311<br>`=$B$26/H73` |  |  |  |  |  |  |  |  |
| 73 |  |  |  | Metric | 22443.82<br>`=J38` | 23854 | 24461 | 26071 |  |  |  |  |  |  |  |  |
| 74 |  |  |  | EV / EBIT | 9.172268974<br>`=$B$26/E75` | 8.632319673<br>`=$B$26/F75` | 8.117863984<br>`=$B$26/G75` | 7.57325886<br>`=$B$26/H75` |  |  |  |  |  |  |  |  |
| 75 |  |  |  | Metric | 16098.07<br>`=J34` | 17105 | 18189 | 19497 |  |  |  |  |  |  |  |  |
| 76 |  |  |  | P / E | 11.89288211<br>`=$B$13/E77` | 11.20938628<br>`=$B$13/F77` | 10.41946309<br>`=$B$13/G77` | 9.73354232<br>`=$B$13/H77` |  |  |  |  |  |  |  |  |
| 77 |  |  |  | Metric | 5.221610658<br>`=J49` | 5.54 | 5.96 | 6.38 |  |  |  |  |  |  |  |  |
| 78 |  |  |  | FCF Yield | 8.1135%<br>`=E79/$B$13` | 5.5233%<br>`=F79/$B$13` | 7.1659%<br>`=G79/$B$13` | 7.6812%<br>`=H79/$B$13` |  |  |  |  |  |  |  |  |
| 79 |  |  |  | Metric | 5.038477033<br>`=J62` | 3.43 | 4.45 | 4.77 |  |  |  |  |  |  |  |  |

## Comparable #2

| # | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Century Pacific Food, Inc. (CNPF) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 2 | Comparable #2 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 4 | General Information |  |  | Reported Income Statement |  |  |  |  |  |  |  | Balance Sheet Data |  |  |  |  |
| 5 | Company Name | Century Pacific Food, Inc. |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  | (₱ in millions) |  |  |  |  |
| 6 | Ticker | CNPF |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  | 2025A | Q2 2026 |  |  |
| 7 | Stock Exchange | Philippine Stock Exchange (PSE) |  | Sales | 67124.34 | 75491.91 | 83295.68 | 39714.92 | 45828.68 | 89409.44<br>`=G7+I7-H7` |  | Cash and Cash Equivalents | 2884.54 | 1880.65 |  |  |
| 8 | Fiscal Year Ending | 2026-12-31 00:00:00 |  | COGS (incl. D&A) | 50987.31 | 55787.09 | 62351.29 | 29515.72 | 33966.43 | 66802<br>`=G8+I8-H8` |  | Accounts Receivable | 13378.06 | 14974.04 |  |  |
| 9 | Marginal Tax Rate | 25.0000% |  | Gross Profit | 16137.03<br>`=E7-E8` | 19704.82<br>`=F7-F8` | 20944.39<br>`=G7-G8` | 10199.2<br>`=H7-H8` | 11862.25<br>`=I7-I8` | 22607.44<br>`=J7-J8` |  | Inventories | 21251.68 | 26089.6 |  |  |
| 10 |  |  |  | SG&A | 9238.58 | 11710.49 | 12377.98 | 5505.9 | 6462.95 | 13335.03<br>`=G10+I10-H10` |  | Prepaids and Other Current Assets | 5517.57 | 7740.45 |  |  |
| 11 | Selected Market Data |  |  | Other Expense / (Income) | -33.55 | 387.76 | -86.2 | -202.98 | -208.39 | -91.61<br>`=G11+I11-H11` |  | Total Current Assets | 43031.85<br>`=SUM(M7:M10)` | 50684.74<br>`=SUM(N7:N10)` |  |  |
| 12 | (In ₱ millions, except per share data. Stock Data is as of August 14, 2026.) |  |  | EBIT | 6932<br>`=E9-E10-E11` | 7606.57<br>`=F9-F10-F11` | 8652.61<br>`=G9-G10-G11` | 4896.28<br>`=H9-H10-H11` | 5607.69<br>`=I9-I10-I11` | 9364.02<br>`=J9-J10-J11` |  |  |  |  |  |  |
| 13 | Current Price | 32.85 |  | Net Finance Costs / (Income) | 405.57 | 211.63 | 349.05 | 151.24 | 300.71 | 498.52<br>`=G13+I13-H13` |  | Property, Plant and Equipment, net | 12387.31 | 13244.53 |  |  |
| 14 | % of 52-week High | 79.5400%<br>`=B13/B15` |  | Pre-tax Income | 6526.43<br>`=E12-E13` | 7394.94<br>`=F12-F13` | 8303.56<br>`=G12-G13` | 4745.04<br>`=H12-H13` | 5306.98<br>`=I12-I13` | 8865.5<br>`=J12-J13` |  | Goodwill and Intangible Assets | 6264.81 | 6250.18 |  |  |
| 15 | 52-week High Price | 41.3 |  | Income Taxes | 947.27 | 1057.17 | 1237.83 | 845.95 | 1164.19 | 1556.07<br>`=G15+I15-H15` |  | Other Assets | 3291.69 | 4967.52 |  |  |
| 16 | 52-week Low Price | 24.85 |  | Non-controlling Interest | - | - | - | - | - | - |  | Total Assets | 64975.66<br>`=M11+SUM(M13:M15)` | 75146.97<br>`=N11+SUM(N13:N15)` |  |  |
| 17 | Dividend Per Share (MRQ) | 0.6 |  | Net Income | 5579.16<br>`=E14-E15` | 6337.77<br>`=F14-F15` | 7065.73<br>`=G14-G15` | 3899.09<br>`=H14-H15` | 4142.79<br>`=I14-I15` | 7309.43<br>`=J14-J15` |  |  |  |  |  |  |
| 18 |  |  |  | Effective Tax Rate | 14.5000% | 14.3000% | 14.9000% | 17.8000% | 21.9000% | 17.6000% |  | Accounts Payable & Accrued Liabilities | 15933.87 | 19569.89 |  |  |
| 19 | Fully Diluted Shares Outstanding | 3542.26<br>`=J20` |  |  |  |  |  |  |  |  |  | Other Current Liabilities | 252.6 | 666.94 |  |  |
| 20 | Equity Value | 116363.241<br>`=B13*B19` |  | Weighted Avg. Diluted Shares | 3546.47 | 3546.47 | 3546.47 | 3542.26 | 3542.26 | 3542.26 |  | Total Current Liabilities (excl. debt) | 16186.47<br>`=M18+M19` | 20236.83<br>`=N18+N19` |  |  |
| 21 |  |  |  | Diluted EPS | 1.573158662<br>`=E17/E20` | 1.78706432<br>`=F17/F20` | 1.992327582<br>`=G17/G20` | 1.100735124<br>`=H17/H20` | 1.16953301<br>`=I17/I20` | 2.063493363<br>`=J17/J20` |  |  |  |  |  |  |
| 22 | Plus: Total Debt | 14728.92<br>`=N22` |  |  |  |  |  |  |  |  |  | Total Debt | 9666.52 | 14728.92 |  |  |
| 23 | Plus: Preferred Stock | - |  | Adjusted Income Statement |  |  |  |  |  |  |  | Other Long-Term Liabilities | 133.2 | 261.41 |  |  |
| 24 | Plus: Non-controlling Interest | -<br>`=N26` |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  | Total Liabilities | 25986.19<br>`=M20+M22+M23` | 35227.16<br>`=N20+N22+N23` |  |  |
| 25 | Less: Cash and Cash Equivalents | 1880.65<br>`=N7` |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  |  |  |  |  |
| 26 | Enterprise Value | 129211.511<br>`=B20+B22-B25` |  | Reported Gross Profit | 16137.03<br>`=E9` | 19704.82<br>`=F9` | 20944.39<br>`=G9` | 10199.2<br>`=H9` | 11862.25<br>`=I9` | 22607.44<br>`=J9` |  | Non-controlling Interest | - | - |  |  |
| 27 |  |  |  | Non-recurring Items in COGS | - | - | - | - | - | - |  | Preferred Stock | - | - |  |  |
| 28 | LTM ROI Ratios |  |  | Adjusted Gross Profit | 16137.03<br>`=E26` | 19704.82<br>`=F26` | 20944.39<br>`=G26` | 10199.2<br>`=H26` | 11862.25<br>`=I26` | 22607.44<br>`=J26` |  | Shareholder's Equity | 38989.47 | 39919.81 |  |  |
| 29 | Return on Invested Capital | 14.5129%<br>`=(J34*(1-B9))/((M28+N28+M22+N22-M7-N7)/2)` |  | % margin | 24.0405%<br>`=E28/E7` | 26.1019%<br>`=F28/F7` | 25.1446%<br>`=G28/G7` | 25.6810%<br>`=H28/H7` | 25.8839%<br>`=I28/I7` | 25.2853%<br>`=J28/J7` |  | Total Liabilities and Equity | 64975.66<br>`=M24+M28` | 75146.97<br>`=N24+N28` |  |  |
| 30 | Return on Equity | 18.8968%<br>`=J46/((M28+N28)/2)` |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 31 | Return on Assets | 10.6416%<br>`=J46/((M16+N16)/2)` |  | Reported EBIT | 6932<br>`=E12` | 7606.57<br>`=F12` | 8652.61<br>`=G12` | 4896.28<br>`=H12` | 5607.69<br>`=I12` | 9364.02<br>`=J12` |  | Balance Check | 0<br>`=M16-M29` | 0<br>`=N16-N29` |  |  |
| 32 | Dividend Yield | 7.3059%<br>`=(B17*4)/B13` |  | Non-recurring Items in COGS | - | - | - | - | - | - |  |  |  |  |  |  |
| 33 |  |  | (1) | Other Non-recurring Items (Operating) | - | 190 | - | - | 169.93 | 169.93<br>`=I33` |  | Growth Rates |  |  |  |  |
| 34 | LTM Credit Statistics |  |  | Adjusted EBIT | 6932<br>`=E31` | 7796.57<br>`=F31+F33` | 8652.61<br>`=G31` | 4896.28<br>`=H31` | 5777.62<br>`=I31+I33` | 9533.95<br>`=J31+J33` |  |  | Sales | EBITDA | FCF/Share | EPS |
| 35 | Leverage Ratios |  |  | % margin | 10.3271%<br>`=E34/E7` | 10.3277%<br>`=F34/F7` | 10.3878%<br>`=G34/G7` | 12.3286%<br>`=H34/H7` | 12.6070%<br>`=I34/I7` | 10.6632%<br>`=J34/J7` |  | Historical |  |  |  |  |
| 36 | Debt / Total Capitalization | 26.9520%<br>`=N22/(N28+N22)` |  |  |  |  |  |  |  |  |  | 1-year | 10.3372%<br>`=((G7/F7)^(1/1))-1` | 11.7649%<br>`=((G38/F38)^(1/1))-1` | -92.1140%<br>`=((G62/F62)^(1/1))-1` | 8.6935%<br>`=((G49/F49)^(1/1))-1` |
| 37 | Total Debt / EBITDA | 1.239978212<br>`=N22/J38` |  | Depreciation and Amortization (D&A) | 1700.21 | 1847.44 | 2126.01 | 948.78 | 1167.19 | 2344.42<br>`=G37+I37-H37` |  | 2-year CAGR | 11.3964%<br>`=((G7/E7)^(1/2))-1` | 11.7431%<br>`=((G38/E38)^(1/2))-1` | -74.3409%<br>`=((G62/E62)^(1/2))-1` | 12.5367%<br>`=((G49/E49)^(1/2))-1` |
| 38 | Net Debt / EBITDA | 1.081652617<br>`=(N22-N7)/J38` |  | Adjusted EBITDA | 8632.21<br>`=E34+E37` | 9644.01<br>`=F34+F37` | 10778.62<br>`=G34+G37` | 5845.06<br>`=H34+H37` | 6944.81<br>`=I34+I37` | 11878.37<br>`=J34+J37` |  | Estimated |  |  |  |  |
| 39 |  |  |  | % margin | 12.8600%<br>`=E38/E7` | 12.7749%<br>`=F38/F7` | 12.9402%<br>`=G38/G7` | 14.7175%<br>`=H38/H7` | 15.1539%<br>`=I38/I7` | 13.2854%<br>`=J38/J7` |  | 1-year | 12.3912%<br>`=((F73/G7)^(1/1))-1` | 15.7384%<br>`=((F75/G38)^(1/1))-1` | 978.2195%<br>`=((F81/G62)^(1/1))-1` | 6.9101%<br>`=((F79/G49)^(1/1))-1` |
| 40 | Coverage Ratios (1) |  |  |  |  |  |  |  |  |  |  | 2-year CAGR | 10.2933%<br>`=((G73/G7)^(1/2))-1` | 12.5755%<br>`=((G75/G38)^(1/2))-1` | 297.2013%<br>`=((G81/G62)^(1/2))-1` | 7.2105%<br>`=((G79/G49)^(1/2))-1` |
| 41 | EBITDA / Interest Expense | 22.13553352<br>`=J38/536.62` |  | Reported Net Income | 5579.16<br>`=E17` | 6337.77<br>`=F17` | 7065.73<br>`=G17` | 3899.09<br>`=H17` | 4142.79<br>`=I17` | 7309.43<br>`=J17` |  | Long-term (1) |  |  |  | 8.9000% |
| 42 | (EBITDA - CapEx) / Interest Expense | 10.52275353<br>`=(J38-J58)/536.62` |  | Non-recurring Items in COGS | - | - | - | - | - | - |  | Note: |  |  |  |  |
| 43 | EBIT / Interest Expense | 17.76666915<br>`=J34/536.62` | (1) | Other Non-recurring Items (Operating) | -<br>`=E33` | 190<br>`=F33` | -<br>`=G33` | -<br>`=H33` | 169.93<br>`=I33` | 169.93<br>`=J33` |  | (1) Sourced directly from equity research consensus estimates for CNPF's expected long-term earnings trajectory. |  |  |  |  |
| 44 | Notes: |  |  | Non-operating Non-recurring Items | - | - | - | - | - | - |  |  |  |  |  |  |
| 45 | (1) Calculated using the LTM finance costs as the denominator. |  | (2) | Tax Adjustment | - | -27.17 | - | - | -23.71 | -23.71<br>`=I45` |  |  |  |  |  |  |
| 46 |  |  |  | Adjusted Net Income | 5579.16<br>`=E41` | 6500.6<br>`=F41+F43+F45` | 7065.73<br>`=G41` | 3899.09<br>`=H41` | 4289.01<br>`=I41+I43+I45` | 7455.65<br>`=J41+J43+J45` |  |  |  |  |  |  |
| 47 |  |  |  | % margin | 8.3117%<br>`=E46/E7` | 8.6110%<br>`=F46/F7` | 8.4827%<br>`=G46/G7` | 9.8177%<br>`=H46/H7` | 9.3588%<br>`=I46/I7` | 8.3388%<br>`=J46/J7` |  |  |  |  |  |  |
| 48 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 49 |  |  |  | Adjusted Diluted EPS | 1.573158662<br>`=E46/E20` | 1.832977581<br>`=F46/F20` | 1.992327582<br>`=G46/G20` | 1.100735124<br>`=H46/H20` | 1.210811742<br>`=I46/I20` | 2.104772095<br>`=J46/J20` |  |  |  |  |  |  |
| 50 |  |  |  | Notes: |  |  |  |  |  |  |  |  |  |  |  |  |
| 51 |  |  |  | (1) FY2024A: Adds back ₱190.00M non-cash trademark impairment loss recognized on the Swift brand (included in Other Operating Expenses) in FY2024. And in the current stub and LTM, ₱169.93M in one-off provisions for damaged inventory and facility repairs caused by the June 2026 earthquake at the General Santos manufacturing plant (reconciling reported operating income growth to CNPF's guided +18% YoY core operating income) is added back. |  |  |  |  |  |  |  |  |  |  |  |  |
| 52 |  |  |  | (2) Reflects the tax shield effect associated with operating add-backs based on prevailing effective corporate tax rates (14.3% in FY2024A and ~13.95% effective base in 6M 2026) to align with CNPF’s internally reported +10% YoY core net income growth (landing at ₱4,289.00M for 1H 2026). |  |  |  |  |  |  |  |  |  |  |  |  |
| 53 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 54 |  |  |  | Cash Flow Statement Data |  |  |  |  |  |  |  |  |  |  |  |  |
| 55 |  |  |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  |  |  |  |  |  |
| 56 |  |  |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  |  |  |  |  |
| 57 |  |  |  | Cash From Operations (CFO) | 8310.74 | 7995.63 | 4530.79 | 1842.14 | 95.16 | 2783.81<br>`=G57+I57-H57` |  |  |  |  |  |  |
| 58 |  |  | (1) | Capital Expenditures (CapEx) | 1516.43 | 2323.2 | 4083.46 | 1525.71 | 3673.9 | 6231.65<br>`=G58+I58-H58` |  |  |  |  |  |  |
| 59 |  |  |  | % sales | 2.2591%<br>`=E58/E7` | 3.0774%<br>`=F58/F7` | 4.9024%<br>`=G58/G7` | 3.8417%<br>`=H58/H7` | 8.0166%<br>`=I58/I7` | 6.9698%<br>`=J58/J7` |  |  |  |  |  |  |
| 60 |  |  |  | Free Cash Flow (FC) | 6794.31<br>`=E57-E58` | 5672.43<br>`=F57-F58` | 447.33<br>`=G57-G58` | 316.43<br>`=H57-H58` | -3578.74<br>`=I57-I58` | -3447.84<br>`=J57-J58` |  |  |  |  |  |  |
| 61 |  |  |  | % margin | 10.1220%<br>`=E60/E7` | 7.5140%<br>`=F60/F7` | 0.5370%<br>`=G60/G7` | 0.7968%<br>`=H60/H7` | -7.8090%<br>`=I60/I7` | -3.8562%<br>`=J60/J7` |  |  |  |  |  |  |
| 62 |  |  |  | FCF / Share | 1.915795143<br>`=E60/E20` | 1.599458053<br>`=F60/F20` | 0.126133874<br>`=G60/G20` | 0.08932997578<br>`=H60/H20` | -1.01029851<br>`=I60/I20` | -0.9733447008<br>`=J60/J20` |  |  |  |  |  |  |
| 63 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 64 |  |  |  | Depreciation and Amortization (D&A) | 1700.21<br>`=E37` | 1847.44<br>`=F37` | 2126.01<br>`=G37` | 948.78<br>`=H37` | 1167.19<br>`=I37` | 2344.42<br>`=J37` |  |  |  |  |  |  |
| 65 |  |  |  | % sales | 2.5329%<br>`=E64/E7` | 2.4472%<br>`=F64/F7` | 2.5524%<br>`=G64/G7` | 2.3890%<br>`=H64/H7` | 2.5469%<br>`=I64/I7` | 2.6221%<br>`=J64/J7` |  |  |  |  |  |  |
| 66 |  |  |  | Note: |  |  |  |  |  |  |  |  |  |  |  |  |
| 67 |  |  |  | (1) The significant increase in 2025A and Q1-Q2 2026 reflects CNPF's major capacity expansion in its coconut and meat processing facilities. |  |  |  |  |  |  |  |  |  |  |  |  |
| 68 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 69 |  |  |  | Trading Multiples |  |  |  |  |  |  |  |  |  |  |  |  |
| 70 |  |  |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  |  |  |  |  |  |
| 71 |  |  |  |  | LTM | 2026E | 2027E | 2028E |  |  |  |  |  |  |  |  |
| 72 |  |  |  | EV / Sales | 1.445166316<br>`=$B$26/E73` | 1.380214181<br>`=$B$26/F73` | 1.27520588<br>`=$B$26/G73` | 1.197878044<br>`=$B$26/H73` |  |  |  |  |  |  |  |  |
| 73 |  |  |  | Metric | 89409.44<br>`=J7` | 93617 | 101326 | 107867 |  |  |  |  |  |  |  |  |
| 74 |  |  |  | EV / EBITDA | 10.87788232<br>`=$B$26/E75` | 10.35763615<br>`=$B$26/F75` | 9.459115007<br>`=$B$26/G75` | 8.685904208<br>`=$B$26/H75` |  |  |  |  |  |  |  |  |
| 75 |  |  |  | Metric | 11878.37<br>`=J38` | 12475 | 13660 | 14876 |  |  |  |  |  |  |  |  |
| 76 |  |  |  | EV / EBIT | 13.55277833<br>`=$B$26/E77` | 13.59548727<br>`=$B$26/F77` | 12.09845609<br>`=$B$26/G77` | 11.07970425<br>`=$B$26/H77` |  |  |  |  |  |  |  |  |
| 77 |  |  |  | Metric | 9533.95<br>`=J34` | 9504 | 10680 | 11662 |  |  |  |  |  |  |  |  |
| 78 |  |  |  | P / E | 15.6073905<br>`=$B$13/E79` | 15.42253521<br>`=$B$13/F79` | 14.34497817<br>`=$B$13/G79` | 13.03571429<br>`=$B$13/H79` |  |  |  |  |  |  |  |  |
| 79 |  |  |  | Metric | 2.104772095<br>`=J49` | 2.13 | 2.29 | 2.52 |  |  |  |  |  |  |  |  |
| 80 |  |  |  | FCF Yield | -2.9630%<br>`=E81/$B$13` | 4.1400%<br>`=F81/$B$13` | 6.0578%<br>`=G81/$B$13` | 4.6880%<br>`=H81/$B$13` |  |  |  |  |  |  |  |  |
| 81 |  |  |  | Metric | -0.9733447008<br>`=J62` | 1.36 | 1.99 | 1.54 |  |  |  |  |  |  |  |  |

## Comparable #3

| # | A | B | C | D | E | F | G | H | I | J | K | L | M | N | O | P |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | San Miguel Food and Beverage, Inc. (FB) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 2 | Comparable #3 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 3 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 4 | General Information |  |  | Reported Income Statement |  |  |  |  |  |  |  | Balance Sheet Data |  |  |  |  |
| 5 | Company Name | San Miguel Food and Beverage, Inc. |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  | (₱ in millions) |  |  |  |  |
| 6 | Ticker | FB |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  | 2025A | Q2 2026 |  |  |
| 7 | Stock Exchange | Philippine Stock Exchange (PSE) |  | Sales | 379822 | 400872 | 419060 | 201200 | 205254 | 423114<br>`=G7+I7-H7` |  | Cash and Cash Equivalents | 64506 | 63316 |  |  |
| 8 | Fiscal Year Ending | 2026-12-31 00:00:00 |  | COGS (incl. D&A) | 279222 | 289940 | 298700 | 143084 | 146863 | 302479<br>`=G8+I8-H8` |  | Accounts Receivable | 29891 | 24175 |  |  |
| 9 | Marginal Tax Rate | 25.0000% |  | Gross Profit | 100600<br>`=E7-E8` | 110932<br>`=F7-F8` | 120360<br>`=G7-G8` | 58116<br>`=H7-H8` | 58391<br>`=I7-I8` | 120635<br>`=J7-J8` |  | Inventories | 43659 | 51656 |  |  |
| 10 |  |  |  | SG&A | 52189 | 55140 | 59320 | 28075 | 29580 | 60825<br>`=G10+I10-H10` |  | Prepaids and Other Current Assets | 8206 | 7907 |  |  |
| 11 | Selected Market Data |  |  | EBIT | 48411<br>`=E9-E10` | 55792<br>`=F9-F10` | 61040<br>`=G9-G10` | 30041<br>`=H9-H10` | 28811<br>`=I9-I10` | 59810<br>`=J9-J10` |  | Total Current Assets | 146262<br>`=SUM(M7:M10)` | 147054<br>`=SUM(N7:N10)` |  |  |
| 12 | (In ₱ millions, except per share data. Stock Data is as of August 14, 2026.) |  |  | Other Expense / (Income) | -3152 | 1104 | -1093 | -545 | -372 | -920<br>`=G12+I12-H12` |  |  |  |  |  |  |
| 13 | Current Price | 48.6 |  | Net Finance Costs / (Income) | 1685 | 1021 | 1225 | 744 | 539 | 1020<br>`=G13+I13-H13` |  | Property, Plant and Equipment, net | 136768 | 136289 |  |  |
| 14 | % of 52-week High | 86.5539%<br>`=B13/B15` |  | Pre-tax Income | 49878<br>`=E11-E12-E13` | 53667<br>`=F11-F12-F13` | 60908<br>`=G11-G12-G13` | 29842<br>`=H11-H12-H13` | 28644<br>`=I11-I12-I13` | 59710<br>`=J11-J12-J13` |  | Goodwill and Intangible Assets | 40812 | 40886 |  |  |
| 15 | 52-week High Price | 56.15 |  | Income Taxes | 11773 | 12734 | 14628 | 6878 | 6592 | 14342<br>`=G15+I15-H15` |  | Other Assets | 65465 | 65718 |  |  |
| 16 | 52-week Low Price | 47.8 |  | Non-controlling Interest | 14987 | 15190 | 16152 | 8016 | 7442 | 15578<br>`=G16+I16-H16` |  | Total Assets | 389307<br>`=M11+SUM(M13:M15)` | 389947<br>`=N11+SUM(N13:N15)` |  |  |
| 17 | Dividend Per Share (MRQ) | 1.27 |  | Net Income | 23118<br>`=E14-E15-E16` | 25743<br>`=F14-F15-F16` | 30128<br>`=G14-G15-G16` | 14948<br>`=H14-H15-H16` | 14610<br>`=I14-I15-I16` | 29790<br>`=J14-J15-J16` |  |  |  |  |  |  |
| 18 |  |  |  | Effective Tax Rate | 23.6000% | 23.7000% | 24.0000% | 23.0000% | 23.0000% | 24.0000% |  | Accounts Payable & Accrued Liabilities | 74542 | 71177 |  |  |
| 19 | Fully Diluted Shares Outstanding | 5909.22<br>`=J20` |  |  |  |  |  |  |  |  |  | Other Current Liabilities | 11480 | 9488 |  |  |
| 20 | Equity Value | 287188.092<br>`=B13*B19` |  | Weighted Avg. Diluted Shares | 5909.22 | 5909.22 | 5909.22 | 5909.22 | 5909.22 | 5909.22 |  | Total Current Liabilities (excl. debt) | 86022<br>`=M18+M19` | 80665<br>`=N18+N19` |  |  |
| 21 |  |  |  | Diluted EPS | 3.912191457<br>`=E17/E20` | 4.356412521<br>`=F17/F20` | 5.098473233<br>`=G17/G20` | 2.529606276<br>`=H17/H20` | 2.472407526<br>`=I17/I20` | 5.041274483<br>`=J17/J20` |  |  |  |  |  |  |
| 22 | Plus: Total Debt | 98257<br>`=N22` |  |  |  |  |  |  |  |  |  | Total Debt | 100738 | 98257 |  |  |
| 23 | Plus: Preferred Stock | 300 |  | Adjusted Income Statement |  |  |  |  |  |  |  | Other Long-Term Liabilities | 5804 | 5682 |  |  |
| 24 | Plus: Non-controlling Interest | 67790<br>`=N26` |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  | Total Liabilities | 192564<br>`=M20+M22+M23` | 184604<br>`=N20+N22+N23` |  |  |
| 25 | Less: Cash and Cash Equivalents | 63316<br>`=N7` |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  |  |  |  |  |
| 26 | Enterprise Value | 390219.092<br>`=B20+B22+B23+B24-B25` |  | Reported Gross Profit | 100600<br>`=E9` | 110932<br>`=F9` | 120360<br>`=G9` | 58116<br>`=H9` | 58391<br>`=I9` | 120635<br>`=J9` |  | Non-controlling Interest | 68260 | 67790 |  |  |
| 27 |  |  |  | Non-recurring Items in COGS | - | - | - | - | - | - |  | Preferred Stock | - | - |  |  |
| 28 | LTM ROI Ratios |  |  | Adjusted Gross Profit | 100600<br>`=E26` | 110932<br>`=F26` | 120360<br>`=G26` | 58116<br>`=H26` | 58391<br>`=I26` | 120635<br>`=J26` |  | Shareholder's Equity | 128483 | 137553 |  |  |
| 29 | Return on Invested Capital | 18.9569%<br>`=(J34*(1-B9))/((M28+N28+M22+N22+M26+N26-M7-N7)/2)` |  | % margin | 26.4861%<br>`=E28/E7` | 27.6727%<br>`=F28/F7` | 28.7214%<br>`=G28/G7` | 28.8847%<br>`=H28/H7` | 28.4482%<br>`=I28/I7` | 28.5112%<br>`=J28/J7` |  | Total Liabilities and Equity | 389307<br>`=M24+M26+M28` | 389947<br>`=N24+N26+N28` |  |  |
| 30 | Return on Equity | 21.8767%<br>`=J46/((M28+N28)/2)` |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 31 | Return on Assets | 7.4687%<br>`=J46/((M16+N16)/2)` |  | Reported EBIT | 48411<br>`=E11` | 55792<br>`=F11` | 61040<br>`=G11` | 30041<br>`=H11` | 28811<br>`=I11` | 59810<br>`=J11` |  | Balance Check | 0<br>`=M16-M29` | 0<br>`=N16-N29` |  |  |
| 32 | Dividend Yield | 10.4527%<br>`=(B17*4)/B13` |  | Non-recurring Items in COGS | - | - | - | - | - | - |  |  |  |  |  |  |
| 33 |  |  |  | Other Non-recurring Items (Operating) | - | - | - | - | - | -<br>`=I33` |  | Growth Rates |  |  |  |  |
| 34 | LTM Credit Statistics |  |  | Adjusted EBIT | 48411<br>`=E31` | 55792<br>`=F31` | 61040<br>`=G31` | 30041<br>`=H31` | 28811<br>`=I31` | 59810<br>`=J31` |  |  | Sales | EBITDA | FCF/Share | EPS |
| 35 | Leverage Ratios |  |  | % margin | 12.7457%<br>`=E34/E7` | 13.9177%<br>`=F34/F7` | 14.5659%<br>`=G34/G7` | 14.9309%<br>`=H34/H7` | 14.0368%<br>`=I34/I7` | 14.1357%<br>`=J34/J7` |  | Historical |  |  |  |  |
| 36 | Debt / Total Capitalization | 32.3640%<br>`=N22/(N28+N22+N26)` |  |  |  |  |  |  |  |  |  | 1-year | 4.5371%<br>`=((G7/F7)^(1/1))-1` | 10.2538%<br>`=((G38/F38)^(1/1))-1` | 16.2514%<br>`=((G62/F62)^(1/1))-1` | 10.3018%<br>`=((G49/F49)^(1/1))-1` |
| 37 | Total Debt / EBITDA | 1.231506781<br>`=N22/J38` |  | Depreciation and Amortization (D&A) | 16164 | 16893 | 19098 | 8703 | 9581 | 19976<br>`=G37+I37-H37` |  | 2-year CAGR | 5.0384%<br>`=((G7/E7)^(1/2))-1` | 11.4005%<br>`=((G38/E38)^(1/2))-1` | -6.8631%<br>`=((G62/E62)^(1/2))-1` | 18.8350%<br>`=((G49/E49)^(1/2))-1` |
| 38 | Net Debt / EBITDA | 0.4379339734<br>`=(N22-N7)/J38` |  | Adjusted EBITDA | 64575<br>`=E34+E37` | 72685<br>`=F34+F37` | 80138<br>`=G34+G37` | 38744<br>`=H34+H37` | 38392<br>`=I34+I37` | 79786<br>`=J34+J37` |  | Estimated |  |  |  |  |
| 39 |  |  |  | % margin | 17.0014%<br>`=E38/E7` | 18.1317%<br>`=F38/F7` | 19.1233%<br>`=G38/G7` | 19.2565%<br>`=H38/H7` | 18.7046%<br>`=I38/I7` | 18.8569%<br>`=J38/J7` |  | 1-year | 4.8750%<br>`=((F71/G7)^(1/1))-1` | -6.7821%<br>`=((F73/G38)^(1/1))-1` | -2.3959%<br>`=((F79/G62)^(1/1))-1` | -1.0032%<br>`=((F77/G49)^(1/1))-1` |
| 40 | Coverage Ratios (1) |  |  |  |  |  |  |  |  |  |  | 2-year CAGR | 5.0810%<br>`=((G71/G7)^(1/2))-1` | -1.9380%<br>`=((G73/G38)^(1/2))-1` | 1.1255%<br>`=((G79/G62)^(1/2))-1` | 3.1779%<br>`=((G77/G49)^(1/2))-1` |
| 41 | EBITDA / Interest Expense | 17.69875776<br>`=J38/4508` |  | Reported Net Income | 23118<br>`=E17` | 25743<br>`=F17` | 30128<br>`=G17` | 14948<br>`=H17` | 14610<br>`=I17` | 29790<br>`=J17` |  | Long-term (1) |  |  |  | 11.2000% |
| 42 | (EBITDA - CapEx) / Interest Expense | 14.15039929<br>`=(J38-J58)/4508` |  | Non-recurring Items in COGS | - | - | - | - | - | - |  | Note: |  |  |  |  |
| 43 | EBIT / Interest Expense | 13.2675244<br>`=J34/4508` |  | Other Non-recurring Items (Operating) | - | - | - | - | - | - |  | (1) Sourced directly from equity research consensus estimates for FB's expected long-term earnings trajectory. |  |  |  |  |
| 44 | Notes: |  | (1) | Non-operating Non-recurring Items | -3152 | 1104 | -1093 | -545 | -372 | -920<br>`=G44+I44-H44` |  |  |  |  |  |  |
| 45 | (1) Calculated using the LTM interest expense and other financing charges as the denominator. |  | (2) | Tax Adjustment | 788 | -276 | 273.3 | 136.3 | 93 | 230<br>`=G45+I45-H45` |  |  |  |  |  |  |
| 46 |  |  |  | Adjusted Net Income | 20754<br>`=E41+E44+E45` | 26571<br>`=F41+F44+F45` | 29308.3<br>`=G41+G44+G45` | 14539.3<br>`=H41+H44+H45` | 14331<br>`=I41+I44+I45` | 29100<br>`=J41+J44+J45` |  |  |  |  |  |  |
| 47 |  |  |  | % margin | 5.4641%<br>`=E46/E7` | 6.6283%<br>`=F46/F7` | 6.9938%<br>`=G46/G7` | 7.2263%<br>`=H46/H7` | 6.9821%<br>`=I46/I7` | 6.8776%<br>`=J46/J7` |  |  |  |  |  |  |
| 48 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 49 |  |  |  | Adjusted Diluted EPS | 3.512138658<br>`=E46/E20` | 4.496532537<br>`=F46/F20` | 4.959757802<br>`=G46/G20` | 2.460443172<br>`=H46/H20` | 2.425193173<br>`=I46/I20` | 4.924507803<br>`=J46/J20` |  |  |  |  |  |  |
| 50 |  |  |  | Notes: |  |  |  |  |  |  |  |  |  |  |  |  |
| 51 |  |  |  | (1) Normalizes the aggregate total of "Other Income (Charges) - Net", "Gain (Loss) on Sale of Investments and PPE", and "Equity Net Gain of Associate." This backs out significant non-core items including mark-to-market derivative gains/losses, foreign exchange fluctuations, non-cash impairment losses on PPE/spare parts, one-off casualty losses, and one-time tax credit certificates. |  |  |  |  |  |  |  |  |  |  |  |  |
| 52 |  |  |  | (2) Reflects the tax shield/expense effect of the pre-tax adjustments calculated at SMFB's statutory corporate tax rate of 25.0% to arrive at core recurring net income. |  |  |  |  |  |  |  |  |  |  |  |  |
| 53 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 54 |  |  |  | Cash Flow Statement Data |  |  |  |  |  |  |  |  |  |  |  |  |
| 55 |  |  |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  |  |  |  |  |  |
| 56 |  |  |  |  | 2023A | 2024A | 2025A | Prior Stub (Q1-Q2 2025) | Current Stub (Q1-Q2 2026) | LTM (Ending Q2 2026) |  |  |  |  |  |  |
| 57 |  |  |  | Cash From Operations (CFO) | 71304 | 58143 | 64876 | 38284 | 19860 | 46452<br>`=G57+I57-H57` |  |  |  |  |  |  |
| 58 |  |  |  | Capital Expenditures (CapEx) | 15748 | 16688 | 16684 | 6304 | 5616 | 15996<br>`=G58+I58-H58` |  |  |  |  |  |  |
| 59 |  |  |  | % sales | 4.1462%<br>`=E58/E7` | 4.1629%<br>`=F58/F7` | 3.9813%<br>`=G58/G7` | 3.1332%<br>`=H58/H7` | 2.7361%<br>`=I58/I7` | 3.7805%<br>`=J58/J7` |  |  |  |  |  |  |
| 60 |  |  |  | Free Cash Flow (FC) | 55556<br>`=E57-E58` | 41455<br>`=F57-F58` | 48192<br>`=G57-G58` | 31980<br>`=H57-H58` | 14244<br>`=I57-I58` | 30456<br>`=J57-J58` |  |  |  |  |  |  |
| 61 |  |  |  | % margin | 14.6269%<br>`=E60/E7` | 10.3412%<br>`=F60/F7` | 11.5000%<br>`=G60/G7` | 15.8946%<br>`=H60/H7` | 6.9397%<br>`=I60/I7` | 7.1981%<br>`=J60/J7` |  |  |  |  |  |  |
| 62 |  |  |  | FCF / Share | 9.401579227<br>`=E60/E20` | 7.015308281<br>`=F60/F20` | 8.155391067<br>`=G60/G20` | 5.411881771<br>`=H60/H20` | 2.410470417<br>`=I60/I20` | 5.153979713<br>`=J60/J20` |  |  |  |  |  |  |
| 63 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 64 |  |  |  | Depreciation and Amortization (D&A) | 16164<br>`=E37` | 16893<br>`=F37` | 19098<br>`=G37` | 8703<br>`=H37` | 9581<br>`=I37` | 19976<br>`=J37` |  |  |  |  |  |  |
| 65 |  |  |  | % sales | 4.2557%<br>`=E64/E7` | 4.2141%<br>`=F64/F7` | 4.5573%<br>`=G64/G7` | 4.3255%<br>`=H64/H7` | 4.6679%<br>`=I64/I7` | 4.7212%<br>`=J64/J7` |  |  |  |  |  |  |
| 66 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 67 |  |  |  | Trading Multiples |  |  |  |  |  |  |  |  |  |  |  |  |
| 68 |  |  |  | (In ₱ millions, except per share data.) |  |  |  |  |  |  |  |  |  |  |  |  |
| 69 |  |  |  |  | LTM | 2026E | 2027E | 2028E |  |  |  |  |  |  |  |  |
| 70 |  |  |  | EV / Sales | 0.9222552125<br>`=$B$26/E71` | 0.8878927391<br>`=$B$26/F71` | 0.8433030534<br>`=$B$26/G71` | 0.7867082487<br>`=$B$26/H71` |  |  |  |  |  |  |  |  |
| 71 |  |  |  | Metric | 423114<br>`=J7` | 439489 | 462727 | 496015 |  |  |  |  |  |  |  |  |
| 72 |  |  |  | EV / EBITDA | 4.890821598<br>`=$B$26/E73` | 5.223606709<br>`=$B$26/F73` | 5.063703148<br>`=$B$26/G73` | 4.390601422<br>`=$B$26/H73` |  |  |  |  |  |  |  |  |
| 73 |  |  |  | Metric | 79786<br>`=J38` | 74703 | 77062 | 88876 |  |  |  |  |  |  |  |  |
| 74 |  |  |  | EV / EBIT | 6.524311854<br>`=$B$26/E75` | 6.590870723<br>`=$B$26/F75` | 6.244104906<br>`=$B$26/G75` | 5.85448655<br>`=$B$26/H75` |  |  |  |  |  |  |  |  |
| 75 |  |  |  | Metric | 59810<br>`=J34` | 59206 | 62494 | 66653 |  |  |  |  |  |  |  |  |
| 76 |  |  |  | P / E | 9.869006598<br>`=$B$13/E77` | 9.898167006<br>`=$B$13/F77` | 9.204545455<br>`=$B$13/G77` | 8.632326821<br>`=$B$13/H77` |  |  |  |  |  |  |  |  |
| 77 |  |  | (1) | Metric | 4.924507803<br>`=J49` | 4.91 | 5.28 | 5.63 |  |  |  |  |  |  |  |  |
| 78 |  |  |  | FCF Yield | 10.6049%<br>`=E79/$B$13` | 16.3786%<br>`=F79/$B$13` | 17.1605%<br>`=G79/$B$13` | 18.3333%<br>`=H79/$B$13` |  |  |  |  |  |  |  |  |
| 79 |  |  | (2) | Metric | 5.153979713<br>`=J62` | 7.96 | 8.34 | 8.91 |  |  |  |  |  |  |  |  |
| 80 |  |  |  | Notes: |  |  |  |  |  |  |  |  |  |  |  |  |
| 81 |  |  |  | (1) The 2028E EPS is calculated using an EBIT flow-through, where:<br>• EBIT Growth = (2028E EBIT - 2027E EBIT) / 2027E EBIT = 6.66%<br>• 2028E EPS = 2027E EPS or ₱5.28 × (1 + 0.0666) = ₱5.63 |  |  |  |  |  |  |  |  |  |  |  |  |
| 82 |  |  |  | (2) Calculated using the consensus Cash Flow per share estimates (₱11.01, ₱11.55, and ₱12.35 for years 2026 to 2028, respectively) minus an estimated CapEx per share:<br>• CapEx Assumption: SMFB's historical 3-year average CapEx-to-Sales margin is 4.1% (₱15.7B in 2023, ₱16.7B in 2024, ₱16.7B in 2025).<br>• 2026E: ₱11.01 CFO/Share – [ (₱439,489M Sales × 4.1%) / 5,909.22M shares ] = ₱11.01 – ₱3.05 CapEx/Share = ₱7.96. The same process is done until 2028E. |  |  |  |  |  |  |  |  |  |  |  |  |
