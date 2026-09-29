# Capital Structure & EBIT–EPS Analysis Calculator

A modern, comprehensive financial calculator and educational learning suite specifically crafted for **B.Com, M.Com, ACCA, and MBA commerce and finance students**.

---

## 🌟 Key Features

1. **EBIT–EPS Analysis & Comparison**
   - Compare multiple financing alternatives (Debt, Equity, Preference Shares, Hybrid Mix).
   - Real-time step-by-step Income Statement breakdown: EBIT → Interest → PBT → Tax → PAT → Preference Dividend → EAOS → Shares → EPS.
   - Display substituted mathematical formulas with the user's exact numbers inserted.

2. **EBIT–EPS Indifference Point**
   - Exact algebraic solution for:
     $$\frac{(EBIT - I_1)(1 - T) - PD_1}{N_1} = \frac{(EBIT - I_2)(1 - T) - PD_2}{N_2}$$
   - Clear educational rules explaining when each plan generates higher EPS (Below, At, and Above the indifference point).
   - Verification check showing equal EPS for both plans at the indifference operating profit.

3. **Interactive High-DPI EBIT–EPS Chart**
   - Pure SVG interactive chart with zero external dependencies.
   - Hover crosshair tracking showing exact EBIT and corresponding EPS for Plan A and Plan B.
   - Distinct glowing marker and callout tag for the Indifference Point.
   - Customizable EBIT viewport (Min EBIT, Max EBIT, Auto-scale).

4. **Capital Structure Analysis & Visualization**
   - Analyze Equity, Preference, Long-Term Debt, Short-Term Debt, and Other Borrowings.
   - Interactive Donut chart showing percentages and total capital employed.
   - Standard ratios: Debt Ratio, Equity Ratio, Debt-to-Equity (D/E), Equity-to-Debt.

5. **Debt vs Equity Financing Simulator**
   - Interactive slider to test incremental funding mixes (e.g. 40% Debt / 60% Equity).
   - Side-by-side comparison between 100% Debt, 100% Equity, and the Custom Mix.
   - Explains the trade-off between equity dilution and contractual debt interest tax shield.

6. **Financial Leverage & Solvency Analysis**
   - Degree of Financial Leverage (DFL) using basic and expanded preference dividend formulas.
   - Interest Coverage Ratio (ICR) with safe zero-interest handling ("No interest expense — coverage ratio is not meaningful").
   - Risk rating benchmarks (<1.5x Critical, 1.5–3.0x Moderate, >3.0x Comfortable).

7. **Scenario & Sensitivity Analysis**
   - Scenario testing: Low (Pessimistic), Expected (Base Case), High (Optimistic) EBIT.
   - 2D Sensitivity table stress-testing EPS across varying EBIT and interest rates.

8. **Advanced Calculations Repository**
   - Detailed formulas, variable definitions, and step-by-step worked examples for all 9 key corporate finance concepts.

9. **Global Multi-Currency Support**
   - ₹ INR (with Indian grouping `₹10,00,000.00` and Lakhs/Crores notations)
   - $ USD, € EUR, £ GBP

10. **Academic Report Export & History**
    - Print / Save as PDF formatted as a student assignment lab report.
    - Export to Excel (.xls) and CSV.
    - Persistent calculation history with LocalStorage.

---

## 🚀 How to Run

### Option 1: Direct Browser Launch
Simply double-click `launch.bat` or open `index.html` in any web browser (Chrome, Edge, Opera, Firefox).

### Option 2: Local Web Server
Run `serve.ps1` in PowerShell:
```powershell
powershell -ExecutionPolicy Bypass -File .\serve.ps1
```
This will start a local server at `http://localhost:8085/` and automatically open your default browser.

---

## 📚 Curriculum Alignment
Designed to cover corporate finance and financial management syllabi of:
- **ACCA Financial Management (FM / AFM)**
- **B.Com & BBA Corporate Finance / Financial Management**
- **M.Com & MBA Advanced Financial Management**
- **CMA & CA Inter Strategic Financial Management**
