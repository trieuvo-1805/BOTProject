# Financial risk ratio frameworks for infrastructure / BOT / project-finance holding companies (applied to CII)

Research notes, compiled 2026-11-15. Scope: rating-agency metrics and thresholds, the standard ratio catalog (liquidity, leverage, coverage, refinancing, earnings quality, cash flow), composite distress models and how well they work in Vietnam, Vietnamese regulatory thresholds, and early-warning dashboard design. Coverage is limited: the primary Moody's, S&P and Fitch methodology PDFs are paywalled or returned 403, so most agency thresholds come from published rating reports and older criteria copies. Each is flagged.

---

## 1. Rating agency methodologies (toll roads / infrastructure / project finance): key metrics and thresholds

### Takeaway
All three agencies anchor toll-road and project-finance credit on cash flow available for debt service. The core metrics are DSCR (average and minimum), the coverage ratios over the debt and project life (LLCR/PLCR), and leverage as Net debt / CFADS (Fitch) or FFO/Debt and Debt/EBITDA (S&P and Moody's corporate-style approaches). For a BBB toll asset, the published evidence points to average DSCR of about 1.3–1.9x, minimum PLCR of about 1.4–2.1x, and net debt/CFADS of about 7–8x. Investment-grade public toll systems face a downgrade line of about 2.0x DSCR. A holding company like CII should be assessed on the corporate tables (FFO/Debt, Debt/EBITDA) on a consolidated basis, plus a project-level DSCR for each BOT SPV.

### Cited Findings
**S&P corporate financial-risk table (applies to holding companies; the base for CII at group level)**
- The S&P "Financial Risk Indicative Ratios (Corporates)" table, from *Criteria Methodology: Business Risk/Financial Risk Matrix Expanded* (27 May 2009):
  | Financial risk profile | FFO/Debt (%) | Debt/EBITDA (x) | Debt/Capital (%) |
  |---|---|---|---|
  | Minimal | >60 | <1.5 | <25 |
  | Modest | 45–60 | 1.5–2 | 25–35 |
  | Intermediate | 30–45 | 2–3 | 35–45 |
  | Significant | 20–30 | 3–4 | 45–50 |
  | Aggressive | 12–20 | 4–5 | 50–60 |
  | Highly leveraged | <12 | >5 | >60 |

  Source: [S&P 2009 criteria copy filed at Missouri PSC](https://www.efis.psc.mo.gov/Document/Display/44676). The same document states that "FFO to debt of more than 60% and debt to EBITDA of only 1.5x would, in most cases, indicate minimal" financial risk, and that the matrix outcomes "are not meant to be precise indications". The current 2013 corporate methodology replaced the Debt/Capital column and added volatility-adjusted tables (see the next row and Gaps).
- For regulated utilities and **transportation infrastructure**, S&P uses the "low" or "medial" volatility cash-flow/leverage tables of its Corporate Methodology. These tables allow higher leverage for a given financial-risk category than the standard table. FFO/Debt and Debt/EBITDA remain the two core ratios. — [S&P criteria copy (elenia.fi, 2016)](https://www.elenia.fi/files/96497973a1ab772e1e29975bc7101b4c8f255722/rating-method-criteria-for-sed-24-february-2016.pdf); [S&P How We Rate Non-Financial Corporates](https://sandpglobal-spglobal-live.cphostaccess.com/ratings/_division-assets/pdfs/041019_howweratenonfinancialcorporateentities.pdf)

**S&P project finance (applies to BOT SPVs)**
- In its operations phase, S&P derives the preliminary stand-alone credit profile (SACP) from the operations-phase business assessment (OPBA, scored 1–12) and the **minimum forecast DSCR** (Table 1, "Deriving the Preliminary Operations Phase SACP"). S&P uses the minimum DSCR because it captures the riskiest point in the project's life. The current criteria are the *General Project Finance Rating Methodology* (14 Dec 2022), which replaced the 2014 PF Operations Methodology. — [S&P RFC process summary, Dec 2022](https://www.spglobal.com/ratings/en/research/articles/221214-rfc-process-summary-rfc-process-summary-project-finance-rating-methodology-12557351); [S&P RFC Aug 2022](https://www.spglobal.com/ratings/en/research/articles/220809-criteria-infrastructure-request-for-comment-request-for-comment-project-finance-rating-methodology-12362204)

**Fitch (Infrastructure & Project Finance Rating Criteria, 14 Nov 2025; Transportation Infrastructure Rating Criteria, 7 Jan 2025)**
- **Puerto Rico Toll Roads, rated BBB:** minimum PLCR of 2.1x and leverage (net debt / CFADS) of 7–8x through 2030 "meet expectations for a 'BBB' rating". — [News is my Business](https://newsismybusiness.com/fitch-assigns-bbb-rating-to-puerto-rico-toll-roads-project)
- **Plenary Roads Denver, rated BBB-:** an average DSCR of 1.88x with a 1.3x minimum was consistent with BBB-category managed-lanes projects. — [Business Wire/Fitch 2016](https://businesswire.com/news/home/20161202005743/en/Fitch-Affirms-Plenary-Roads-Denver-LLCs-PABs)
- **Kentucky toll bonds, upgraded to BBB+:** the upgrade drivers were a 10-year average rating-case DSCR above 1.8x and year-5 leverage at or below 7x. — [Bond Buyer](https://www.bondbuyer.com/news/fitch-raises-kentucky-toll-revenue-bonds-tifia-loan-to-bbb-plus)
- **Nouvelle Autoroute 30 (availability PPP), BBB+:** an average DSCR of 1.3x and minimum PLCR of 1.4x are consistent with BBB+ "under Fitch's indicative rating guidance for APs and toll roads". — [Investing.com/Fitch 2018](https://m.ca.investing.com/news/economy-news/correction-fitch-expects-to-rate-nouvelle-autoroute-30-financement-inc-quebec-bbb-1147854?ampMode=1)
- **ENA Master Trust (Panama toll roads), BBB:** an average DSCR of about 2.6–2.8x is "above the indicative range" for the category. — [Fitch press release via ENA](https://ena.com.pa/wp-content/uploads/2023/09/Fitch-Affirms-ENA-Master-Trust-at-BBB-Outlook-Remains-Stable.pdf)
- **Investment-grade public toll systems:** for Florida's Turnpike and the Maryland Transportation Authority, a 10-year average rating-case DSCR that falls below 2.0x for a sustained period is a negative rating sensitivity. — [Fitch FDOT Mar 2026](https://floridasturnpike.com/wp-content/uploads/2026/07/Fitch_Florida_Department_of_Transportation_FL-10_Mar_2026.pdf); [Fitch MDTA Sep 2025](https://www.mdta.maryland.gov/sites/default/files/Files/RatingReports/Fitch%20Rating%20Report%20September%202025.pdf)
- **Low end:** a Panama toll concession with rating-case minimum and average DSCR of 0.9x and 1.2x is described as "in line with" criteria guidance for its (sub-investment-grade) rating. — [Fitch via ENA](https://ena.com.pa/wp-content/uploads/2023/09/Fitch-Affirms-ENA-Nortes-Notes-Outlook-Stable.pdf)
- **Weak credit:** in North Tarrant Express, leverage was about 25x CFADS in 2016, falling to 18x in 2017, at BBB-. That rating was supported by long-dated debt and back-ended amortization. — [Benzinga/Fitch](https://www.benzinga.com/pressreleases/11/12/b2213704/fitch-affirms-north-tarrant-express-mobility-partners-llc-revs-at-bbb-o)

**Moody's**
- Moody's rates US public toll roads under *Publicly Managed Toll Roads and Parking Facilities* (May 2023). Concession and PPP assets fall under *Operational Privately Financed Public Infrastructure (PFI/PPP/P3) Projects* (June 2021). — [Moody's rating actions, e.g., NTTA 2025](https://www.ntta.org/sites/default/files/2025-09/Rating_Action-Moodys.pdf); [Moody's PFI doc](https://ratings.moodys.com/api/rmc-documents/72487) (403, not readable)
- A Moody's 2020 stress analysis found that privately managed concession toll roads could absorb a revenue drop of more than 50% before DSCR reached 1.0x. This is a stress result, not a rating threshold. — [Moody's sector in-depth 2020 via CDFA](https://www.cdfa.net/cdfa/cdfaweb.nsf/0/A72B84BACF46BF2E882585580069C524/$file/Moody's%20Sector%20In-Depth%20-%20US%20Toll%20Roads%20-%20Strong%20resiliency%20and%20liquidity%20offset%20some%20of%20coronavirus's%20credit%20negative%20effects.pdf)

### Inferences
- **Metric definitions** (standard project-finance usage, consistent with the agency reports above):
  - **DSCR** = CFADS(t) / (principal + interest due)(t). CFADS = revenue − cash opex − maintenance capex − tax ± working-capital change.
  - **LLCR** = NPV of CFADS over the remaining loan life, discounted at the cost of debt / outstanding debt.
  - **PLCR** = the same NPV taken over the remaining concession life / outstanding debt.
  - **Net debt / CFADS** = net debt / CFADS (Fitch's leverage measure).
- **Indicative bands for a BOT toll asset in Vietnam** (my synthesis of the cases above, not a published grid):

  | Metric | Comfortable | Watch | Weak |
  |---|---|---|---|
  | Average DSCR | ≥1.5x | 1.2–1.5x | <1.2x |
  | Minimum DSCR | ≥1.3x | 1.1–1.3x | <1.1x (1.0x is the default line) |
  | Minimum PLCR | ≥1.6–2.0x | — | — |
  | Net debt / CFADS | ≤8x | 8–12x | >15x |

  For Vietnamese BOT projects, toll-collection and toll-rate risk is government-driven (station relocation, toll freezes). This argues for higher cushions than in US/EU cases.
- **CII at group level (consolidated VAS):** use S&P-style FFO/Debt and Debt/EBITDA. For transportation infrastructure, the medial-volatility table is more lenient than the standard table above. Two VAS adjustments are needed:
  - EBITDA under VAS must be reconstructed as operating profit + depreciation and amortization (from the cash-flow statement). Financial income such as divestment gains must be excluded.
  - FFO ≈ CFO before working-capital changes − interest paid − tax paid. Under VAS, interest paid sits in CFO (indirect method).

### Gaps
- I could not access the exact numeric cells of S&P's current (2013) low- and medial-volatility tables or of S&P's PF Table 1 (minimum DSCR ranges by OPBA). Both are paywalled.
- I could not retrieve Moody's PFI/toll-road scorecard grids, which assign factor weights and DSCR/leverage thresholds per Aaa–Caa (document returned 403).
- I could not access Fitch's indicative matrix for toll roads (DSCR/leverage by midpoint rating). Only individual-case statements were found.
- I found no Vietnamese agency methodology (VIS Rating, Saigon Ratings, FiinRatings) with published toll-road thresholds in this session.

---

## 2. Standard ratio catalog (liquidity, leverage, coverage, refinancing, earnings quality, cash flow) for VAS statements

### Takeaway
Infrastructure holding companies need the classic ratios adapted in two ways. First, measure refinancing exposure: the share of short-term borrowings and the bond-maturity wall. Second, separate recurring toll and operating cash flow from one-off gains such as divestment of subsidiaries, revaluation gains and transfer of BOT rights. CII's profit history relies heavily on such financial gains. The numeric thresholds below are conventional analyst rules of thumb unless a source is given. Where this session found no primary citation, the rule is marked as conventional or as a gap.

### Cited Findings
- **Leverage (S&P):** Debt/Capital, FFO/Debt and Debt/EBITDA thresholds are given in the Section 1 table. — [S&P 2009](https://www.efis.psc.mo.gov/Document/Display/44676)
- **Leverage and Vietnamese distress:** in a 2023 study of 350 non-financial listed firms, a one-unit increase in the degree of financial leverage (DFL) raised the odds of bankruptcy risk (Z-score distress) about 3.94 times (p<0.05). Equity self-financing (EC, equity ratio) reduced the probability. ROE strongly reduced risk (odds ratio 0.0097). Revenue decline lowered the Z-score by about 0.632. — [Nguyễn Thị Thu Trang et al., Tạp chí Kinh tế-Luật và Ngân hàng, No. 286–287, Jan–Feb 2026](https://hvnh.edu.vn/medias/tapchi/vi/01.2026/system/archivedate/a18bad76_2895.vi-%20S%E1%BB%91%20286.287-%20Th%C3%A1ng%201.2.2026-%20Nguy%E1%BB%85n%20Th%E1%BB%8B%20Thu%20Trang%20v%C3%A0%20c%E1%BB%99ng%20s%E1%BB%B1-%20R%E1%BB%A7i%20ro%20ph%C3%A1%20s%E1%BA%A3n%20c%E1%BB%A7a%20c%C3%A1c%20doanh%20nghi%E1%BB%87p%20nhi%C3%AAm%20y%E1%BA%BFt.pdf)
- **Vietnamese leverage cap:** total liabilities / equity ≤5x (see Section 4). — [tinnhanhchungkhoan](https://www.tinnhanhchungkhoan.vn/tu-ngay-172025-phat-hanh-trai-phieu-phai-co-no-phai-tra-khong-qua-5-lan-von-chu-so-huu-post371362.html)
- **Credit-rating trigger:** under Decree 65/2022, an issuer whose outstanding bonds exceed 100% of equity must obtain a credit rating. This makes **outstanding bonds / equity** a natural refinancing and governance indicator. — [Báo Đầu tư](https://baodautu.vn/doanh-nghiep-phat-hanh-trai-phieu-phai-xep-hang-tin-nhiem-neu-du-no-trai-phieu-lon-hon-100-von-chu-so-huu-d173729.html)

### Inferences
Practical catalog for CII. VAS line names are in Vietnamese. Thresholds are conventional unless a source is cited above.

| Group | Indicator | Formula (VAS consolidated) | Interpretation / typical threshold |
|---|---|---|---|
| Liquidity | Current ratio | Current assets / Current liabilities | <1.0 red, 1.0–1.2 amber, >1.2 green |
| | Quick ratio | (Current assets − Inventories) / Current liabilities | <0.5 red; >1.0 green. Real-estate inventory at CII subsidiaries distorts this ratio. |
| | Cash ratio | (Cash + Short-term financial investments) / Current liabilities | <0.2 red; >0.5 green |
| | Cash / short-term debt | (Cash + ST deposits) / (ST borrowings + current portion of LT debt and bonds) | <0.5 red; ≥1.0 green. This is the key refinancing buffer. |
| Leverage | D/E (interest-bearing) | (ST + LT borrowings + bonds) / Equity | >2.0 amber; >3.0 red for a holding company |
| | Liabilities / Equity | Total liabilities / Equity | Legal cap 5x for issuers (Section 4); >4x red |
| | Debt / Assets | Interest-bearing debt / Total assets | >50% amber; >60% red |
| | Debt / Capital | Debt / (Debt + Equity) | S&P bands: >50% aggressive; >60% highly leveraged |
| | Net debt / EBITDA | (Debt − Cash) / EBITDA | S&P bands: >4x aggressive; >5x highly leveraged. Infrastructure assets tolerate higher values (Fitch net debt/CFADS of 7–8x at BBB for a single asset). |
| | FFO / Debt | FFO / Debt | <12% highly leveraged; 12–20% aggressive |
| Coverage | EBITDA interest coverage | EBITDA / Interest expense (include capitalized interest if disclosed) | <1.5x red; 1.5–3x amber; >3x green |
| | ICR (EBIT) | EBIT / Interest expense | <1.0x means operating profit does not cover interest |
| | DSCR (group) | (CFO before interest + interest paid) / (interest paid + scheduled principal) | <1.0x red; 1.0–1.2x amber; ≥1.2–1.3x green. Per-SPV DSCR is in Section 1. |
| | CFO / Debt | CFO / Total debt | <10% weak |
| Refinancing | ST debt share | ST borrowings incl. current portion / Total borrowings | >40% amber; >50% red |
| | Bond maturity concentration | Bonds maturing in the next 12 (and 24) months / Total bonds; also / (Cash + undrawn facilities) | >30% of bonds in one year, or coverage <1x, red |
| | Bonds / Equity | Outstanding bonds / Equity | >100% triggers the mandatory rating under Decree 65 |
| Earnings quality | One-off share of profit | (Financial income from divestments/revaluation + other income) / Profit before tax | >50% red. This is relevant for CII, which records gains from selling stakes and BOT rights. |
| | Accrual ratio | (Net income − CFO) / Average total assets | Persistently >10% is a warning sign (Sloan-type accruals) |
| | Receivables quality | (Receivables, including "other receivables" and receivables from BT/BOT counterparties) / Total assets; DSO | Rising "phải thu khác" is a known VAS red flag |
| Cash flow | FCF | CFO − Capex (purchase of fixed assets and BOT construction in progress) | Persistently negative and funded by debt: amber/red |
| | CFO / Net income | CFO / Net income | <0.5 over 3 years: weak earnings quality |
| | Interest paid / CFO | — | >50% means debt service crowds out operations |

### Gaps
- I found no authoritative Vietnamese source that publishes industry-specific threshold tables for current ratio, ICR or similar for infrastructure firms. The thresholds above are conventional practice, and the report writer should present them as such.
- No source was found on CII-specific bond maturity schedules. Those come from CII's financial-statement notes and HNX disclosures, which are outside this scope.

---

## 3. Composite distress models and their applicability in Vietnam

### Takeaway
Altman's Z'' (1983/1995, non-manufacturing and emerging markets) is the most-used and most defensible composite model for Vietnamese listed non-financials. Even so, Vietnamese studies report clearly lower accuracy than in the original US samples, and wide dispersion for asset-heavy sectors (real estate). Ohlson's O-score, Merton/KMV distance-to-default and Beneish's M-score add value as cross-checks. Each needs local recalibration, and each has data limits under VAS and in the shallow HOSE market.

### Cited Findings
- **Original Altman Z (1968):** zones are Z<1.81 distress, 1.81–2.99 grey, Z>2.99 safe. The model was built on 66 US manufacturing firms from 1946–65. — [HVNH 2026 paper (above)](https://hvnh.edu.vn/medias/tapchi/vi/01.2026/system/archivedate/a18bad76_2895.vi-%20S%E1%BB%91%20286.287-%20Th%C3%A1ng%201.2.2026-%20Nguy%E1%BB%85n%20Th%E1%BB%8B%20Thu%20Trang%20v%C3%A0%20c%E1%BB%99ng%20s%E1%BB%B1-%20R%E1%BB%A7i%20ro%20ph%C3%A1%20s%E1%BA%A3n%20c%E1%BB%A7a%20c%C3%A1c%20doanh%20nghi%E1%BB%87p%20nhi%C3%AAm%20y%E1%BA%BFt.pdf)
- **Altman Z'' (1983 revision):**
  - Formula: Z'' = 6.56·X1 + 3.26·X2 + 6.72·X3 + 1.05·X4, where X1 = Working capital/Total assets, X2 = Retained earnings/Total assets, X3 = EBIT/Total assets, and X4 = Book equity/Book total liabilities.
  - Zones: Z''<1.1 distress, 1.1–2.6 grey, >2.6 safe.
  - Altman considered Z'' more suitable for emerging markets than the original Z.
  - The HVNH study used both Z and Z'' on 350 HOSE non-financial firms in 2023. Its logit model classified 78.57% of firms correctly (sensitivity 78.22%, specificity 78.71%).
  - [Same source](https://hvnh.edu.vn/medias/tapchi/vi/01.2026/system/archivedate/a18bad76_2895.vi-%20S%E1%BB%91%20286.287-%20Th%C3%A1ng%201.2.2026-%20Nguy%E1%BB%85n%20Th%E1%BB%8B%20Thu%20Trang%20v%C3%A0%20c%E1%BB%99ng%20s%E1%BB%B1-%20R%E1%BB%A7i%20ro%20ph%C3%A1%20s%E1%BA%A3n%20c%E1%BB%A7a%20c%C3%A1c%20doanh%20nghi%E1%BB%87p%20nhi%C3%AAm%20y%E1%BA%BFt.pdf)
- **Real estate:** Z-scores for HOSE/HNX real-estate firms in 2019–2023 ranged from −2.57 to 7.62 (mean 2.71). The authors question the model's fit for real estate. — [Tạp chí Công Thương](https://tapchicongthuong.vn/du-bao-rui-ro-pha-san-cua-cac-doanh-nghiep-bat-dong-san-niem-yet-tren-thi-truong-chung-khoan-viet-nam-thong-qua-he-so-z-score-128084.htm)
- **Model comparison, plastics sector (2012–2023, HOSE/HNX/UPCoM):** the study tested Z (1968, 1983, 1995), S-score, X-score (Zmijewski), O-score (Ohlson) and G-score. X-score and Taffler Z had high Type I error (66.7%). G-score had the lowest Type II error. Source details come from the search-result snippet only. — [Tạp chí NC Tài chính Kế toán (HVTC)](https://tapchitckt.hvtc.edu.vn/DesktopModules/SubPortal/TapChiNCTCKT/Service/TraVeFilePDF.aspx?ID=1561)
- **Textiles:** Z-score accuracy on Vietnamese listed textile firms was only 57.6%, well below Altman's original. The authors recommend recalibration (search snippet). — [vjol.info.vn](https://vjol.info.vn/index.php/DHM-KTQTKD/article/download/82829/70593)
- **Logistics (40 listed firms, 2012–2022):** leverage significantly reduces the Z-score (snippet). — [vjol / Viện KT VN & TG](https://vjol.info.vn/tcvienkinhteVNvathegioi/article/download/142272/116149/)

### Inferences
- **For CII, use Z'' rather than Z.** The original Z includes Sales/Total assets, and BOT holding companies are structurally asset-heavy with low asset turnover, so Z penalizes them mechanically.
- **Z'' also has biases for CII:**
  - X1 (working capital) is distorted by real-estate inventory and short-term bonds.
  - X2 (retained earnings) is distorted by gains taken to equity and by stock dividends.
  - X3 (EBIT/TA) is inflated by one-off financial gains if EBIT is not cleaned. Recommendation: compute X3 on recurring EBIT, excluding gains on divestments.
  - X4 uses book equity, which includes large non-controlling interests at CII. Report X4 both with and without NCI.
- **Ohlson O-score** (1980, nine-variable logit including size, TL/TA, WC/TA, CL/CA, NI/TA, FFO/TL, a negative-equity dummy, two-year-loss dummy and ΔNI) gives a probability of default. A probability above 0.5 is conventionally read as distress. Its coefficients are US-estimated, and the plastics study above tested it on Vietnamese data. Coefficients and the cutoff are from standard literature, not verified in this session.
- **Merton/KMV distance-to-default:** DD = [ln(V/D) + (μ − σ²/2)T] / (σ·√T). Asset value V and volatility σ are backed out of equity market capitalization and equity volatility. The default point D = ST debt + ½ LT debt (KMV convention). Limitations for CII: price limits (±7% on HOSE), low free float and episodic illiquidity bias equity volatility. VAS also gives no clean maturity profile of BOT project debt. Treat DD as a relative trend indicator, not a calibrated PD.
- **Beneish M-score** (8 variables: DSRI, GMI, AQI, SGI, DEPI, SGAI, LVGI, TATA; the conventional manipulation cutoff is about −1.78, with −2.22 in an earlier version) is a red-flag test for earnings manipulation, not for default. It is relevant for CII given its heavy related-party transactions and one-off gains. The coefficients and cutoff are from standard literature and were not re-verified in this session.

### Gaps
- I did not find a Vietnamese study that tested Merton/KMV DD or Beneish M specifically on HOSE infrastructure firms in this session.
- Full-text accuracy figures for the O-score in Vietnam were not extracted (snippets only).
- I found no published Z'' recalibration specific to Vietnamese BOT/infrastructure firms.

---

## 4. Vietnamese regulatory thresholds (corporate bonds, credit rating, listing warnings)

### Takeaway
The hard legal lines are as follows:
- Liabilities (including the new bond) of no more than 5x equity, under the amended Enterprise Law effective 1 Jul 2025 for private placements by non-public companies, and under Decree 245/2025 for public offerings.
- A mandatory credit rating when outstanding bonds exceed 100% of equity (Decree 65/2022). For public offerings, a rating is now mandatory in general.
- Compulsory delisting if the company loses money for 3 consecutive years, if accumulated losses exceed paid-in capital, or if equity is negative (Decree 155/2020, Art. 120).

### Cited Findings
- **Decree 65/2022/NĐ-CP** (16 Sep 2022) amended Decree 153/2020 on private corporate bonds. It requires a credit rating when an issuer's outstanding bonds exceed 100% of equity (with other conditions). — [Báo Đầu tư](https://baodautu.vn/doanh-nghiep-phat-hanh-trai-phieu-phai-xep-hang-tin-nhiem-neu-du-no-trai-phieu-lon-hon-100-von-chu-so-huu-d173729.html); [Thời báo Tài chính](https://thoibaotaichinhvietnam.vn/nghi-dinh-652022nd-cp-ve-phat-hanh-trai-phieu-doanh-nghiep-rieng-le-co-nhung-diem-moi-nao-112944.html); [Mayer Brown](https://www.mayerbrown.com/pt/insights/publications/2022/10/new-decree-on-corporate-bonds-in-vietnam-five-key-takeaways)
- **Replacement decree:** LuatVietnam lists Decree 65/2022 as replaced by Decree 200/2026/NĐ-CP, which also replaces Decree 153/2020. — [LuatVietnam](https://luatvietnam.vn/chung-khoan/nghi-dinh-65-2022-nd-cp-229828-d1.html); [Doanh nghiệp hội nhập](https://doanhnghiephoinhap.vn/chinh-phu-bo-sung-nguyen-tac-phat-hanh-trai-phieu-70269.html)
- **5x cap for private placements:** under the amended Enterprise Law (passed 17 Jun 2025, effective 1 Jul 2025), a non-public company issuing private bonds must have "nợ phải trả (bao gồm giá trị trái phiếu dự kiến phát hành) không vượt quá 5 lần vốn chủ sở hữu" (liabilities, including the planned bond value, of no more than 5x equity). This is measured on the audited financial statements of the year before issuance. Exempt are state-owned enterprises, issuers of bonds for real-estate projects, credit institutions, insurers, and securities and fund-management companies. — [tinnhanhchungkhoan](https://www.tinnhanhchungkhoan.vn/tu-ngay-172025-phat-hanh-trai-phieu-phai-co-no-phai-tra-khong-qua-5-lan-von-chu-so-huu-post371362.html); [The Leader](https://theleader.vn/luat-doanh-nghiep-sua-doi-siet-phat-hanh-trai-phieu-rieng-le-d40732.html); [Nhà Đầu tư](https://nhadautu.vn/doanh-nghiep-chua-dai-chung-no-qua-5-lan-von-khong-duoc-phat-hanh-trai-phieu-d97011.html)
- **Market impact:** in 2024, 13 private-bond issuers had debt/equity above 5x. VIS Rating estimated that about 25% of non-public issuers exceed the ratio or have negative equity. — [search summary of SGGP / diendandoanhnghiep](https://www.sggp.org.vn/quy-mo-no-cua-doanh-nghiep-phat-hanh-trai-phieu-khong-duoc-vuot-qua-5-lan-von-chu-so-huu-post817255.html)
- **Public offerings (Decree 245/2025/NĐ-CP, amending Decree 155/2020):**
  - An independent credit rating is required (exceptions: bonds of credit institutions, or bonds fully guaranteed by them). The previous rule required a rating only if bonds raised in 12 months exceeded VND 500bn and 50% of equity, or outstanding bonds exceeded 100% of equity.
  - Liabilities, including the planned bonds, may not exceed 5x equity on the latest audited financial statements, with the same exemptions as above. Bonds issued to restructure debt are excluded from the cap.
  - For multi-tranche offerings, each tranche may not exceed equity.
  - [Luật sư Việt Nam (lsvn.vn)](https://lsvn.vn/quy-dinh-moi-ve-dieu-kien-chao-ban-trai-phieu-ra-cong-chung-a163158.html)
- **Compulsory delisting (Decree 155/2020, Art. 120.1):**
  - Losses for 3 consecutive years, or accumulated losses exceeding paid-in charter capital, or negative equity on the latest audited annual financial statements.
  - Also an auditor's qualified, adverse or disclaimer opinion for 3 consecutive years, or late annual reports for 3 consecutive years.
  - [hethongphapluat – Art. 120](https://hethongphapluat.com/nghi-dinh-155-2020-nd-cp-huong-dan-luat-chung-khoan/dieu-120); [Thư viện pháp luật Q&A](https://thuvienphapluat.vn/hoi-dap-phap-luat/truong-hop-nao-cac-cong-ty-dai-chung-bi-huy-bo-niem-yet-co-phieu-138018888.html)
- **Listing regulation:** HOSE's warning/control/suspension statuses are set out in the exchange's listing regulation (Quy chế niêm yết, Decision 17/QĐ-HĐTV). — [MBS copy](https://mbs.com.vn/files/uploads/2025/04/17_qd-hdtv_quy-che-niem-yet-va-giao-dich-ck-niem-yet.pdf)

### Inferences
- **CII is a public, listed company,** so the 5x cap reaches it through the public-offering rules (Decree 245/2025) and through Decree 200/2026 for private placements. Whether the Enterprise Law's private-placement cap also applies to public companies depends on Decree 200/2026's text, which I did not read. The real-estate exemption could matter for CII's real-estate subsidiaries, but not for its BOT/holding bonds.
- **Dashboard red lines that follow from the law:**
  - Liabilities/Equity of 5x is the legal limit. Use 4x as the red internal line and 3x as amber.
  - Outstanding bonds/Equity above 100% is the historical rating trigger.
  - Accumulated losses / paid-in capital approaching 100%, or two consecutive loss years, are delisting precursors.
- **Decree 08/2023/NĐ-CP (5 Mar 2023),** from memory and not re-verified in this session:
  - It suspended until 31 Dec 2023 several Decree 65 provisions: the professional-individual-investor definition, the mandatory-rating requirement and the distribution timeline.
  - It allowed issuers, with bondholder approval, to extend bond terms by up to 2 years and to repay in other assets.
  - Consequence for analysis: extended maturities from 2023 can hide refinancing stress, so track "extended/restructured bonds / total bonds" as an indicator.

### Gaps
- The full text of Decree 200/2026/NĐ-CP (the current private-placement decree) was not reviewed. Its exact conditions (D/E cap applicability to public companies, rating triggers, loss conditions) need checking on thuvienphapluat.vn.
- The provisions of Decree 08/2023 were not verified against primary text in this session.
- I found no SSC circular publishing a "financial health warning" ratio list. The SSC and exchange warnings are event-based (losses, audit opinions, late reporting), not ratio-based.

---

## 5. Building a risk dashboard / early-warning system (traffic lights and weighting)

### Takeaway
Best practice is a scorecard in the rating-agency style:
- 5–7 factor groups (liquidity, refinancing, leverage, coverage, cash-flow and earnings quality, legal or covenant headroom, and a composite model).
- Each indicator mapped to green, amber or red bands taken from agency tables or legal limits.
- Weights that favor coverage and refinancing for a project-finance holding company.
- Any hard legal breach (such as D/E above 5x, or a delisting trigger) overrides the weighted score.

### Cited Findings
- Agencies combine weighted scorecard factors with qualitative overlays, and their matrix outcomes "are not meant to be precise indications". Analysts may adjust by a notch. — [S&P 2009](https://www.efis.psc.mo.gov/Document/Display/44676)
- S&P's PF approach takes the **minimum** DSCR, not the average, as the anchor because it captures the riskiest period. — [S&P RFC 2022](https://www.spglobal.com/ratings/en/research/articles/220809-criteria-infrastructure-request-for-comment-request-for-comment-project-finance-rating-methodology-12362204)
- The Vietnamese logit study showed that combining leverage (DFL), ROE, size and equity ratio gives about 79% correct classification of Z-defined distress. This supports a multi-factor weighted approach over a single ratio. — [HVNH 2026](https://hvnh.edu.vn/medias/tapchi/vi/01.2026/system/archivedate/a18bad76_2895.vi-%20S%E1%BB%91%20286.287-%20Th%C3%A1ng%201.2.2026-%20Nguy%E1%BB%85n%20Th%E1%BB%8B%20Thu%20Trang%20v%C3%A0%20c%E1%BB%99ng%20s%E1%BB%B1-%20R%E1%BB%A7i%20ro%20ph%C3%A1%20s%E1%BA%A3n%20c%E1%BB%A7a%20c%C3%A1c%20doanh%20nghi%E1%BB%87p%20nhi%C3%AAm%20y%E1%BA%BFt.pdf)

### Inferences
Suggested CII early-warning scorecard. The weights are my proposal, not a published standard.

| Factor (weight) | Indicators | Green | Amber | Red |
|---|---|---|---|---|
| Coverage (25%) | EBITDA/Interest; group DSCR; minimum DSCR of key BOT SPVs | >3x; ≥1.3x; ≥1.3x | 1.5–3x; 1.0–1.3x; 1.1–1.3x | <1.5x; <1.0x; <1.1x |
| Refinancing and liquidity (25%) | Cash / ST debt; ST debt share; bonds due in 12m / (cash + undrawn lines); current ratio | ≥1.0; <30%; <0.5; >1.2 | 0.5–1.0; 30–50%; 0.5–1.0; 1.0–1.2 | <0.5; >50%; >1.0; <1.0 |
| Leverage (20%) | Net debt/EBITDA; FFO/Debt; Liabilities/Equity; Bonds/Equity | <4x; >20%; <3x; <0.7 | 4–6x; 12–20%; 3–4x; 0.7–1.0 | >6x; <12%; >4x (legal cap 5x); >1.0 |
| Cash-flow and earnings quality (15%) | CFO/NI (3-year); one-off share of PBT; accrual ratio; FCF | >0.8; <20%; <5%; positive | 0.5–0.8; 20–50%; 5–10%; negative but funded | <0.5; >50%; >10%; negative and debt-funded |
| Composite models (15%) | Altman Z'' (cleaned EBIT); M-score; DD trend | >2.6; < −2.22; rising | 1.1–2.6; −2.22 to −1.78; flat | <1.1; > −1.78; falling |

Scoring method:
- Score each indicator 3 (green), 2 (amber) or 1 (red). Average within each factor, then weight across factors.
- Overall score above 2.4 is green, 1.8–2.4 amber, below 1.8 red.
- Hard overrides that force red:
  - Liabilities/Equity at or above 5x.
  - Two consecutive loss years, or accumulated losses at or above 70% of charter capital (a precursor to the Art. 120 delisting trigger).
  - Any bond payment delay or term extension without restructuring.
  - Qualified audit opinion.
- Run the scorecard quarterly on consolidated VAS statements, using trailing-12-month (LTM) flows. Also compute it on the parent-only statements (công ty mẹ), because a holding company's debt service depends on dividends and cash up-streamed from SPVs that are often ring-fenced by project lenders.

### Gaps
- I found no published Vietnamese supervisory early-warning system (for example from SBV or SSC) with explicit ratio weights.
- I found no backtest of the weights above on Vietnamese infrastructure firms. They should be presented as expert judgment.
