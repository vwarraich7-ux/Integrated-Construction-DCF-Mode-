# Integrated 3-Statement Forecasting & DCF Valuation Engine

An institutional-grade, fully integrated financial forecasting model and intrinsic corporate valuation engine built for medium-scale operations. This project demonstrates dynamic multi-statement linkages, flexible scenario architecture, and rigorous cash flow discounting mechanics.

## 🛠️ Model Architecture & Features

### 1. Integrated 3-Statement Core
* **Income Statement:** Automated top-line scaling derived from variable volume growth assumptions, cascading through structured operational expenses, regional tax structures, and debt service calculations.
* **Balance Sheet & Cash Flow Linkages:** Hardwired accounting integrity where changes in operating working capital and fixed assets dynamically reconcile to cash balances without balance sheet circularity.

### 2. Operational Schedules & Drivers
* **Capital Asset Management:** Tracks heavy equipment and machinery CAPEX injections alongside depreciation roll-forward schedules.
* **Working Capital Engine:** Models operational cash cycles including progress billings (Accounts Receivable), materials on hand (Inventory), and subcontractor obligations (Accounts Payable).

### 3. Discounted Cash Flow (DCF) Valuation Engine
* **Unlevered Free Cash Flow (UFCF):** Derives true economic cash yields by computing Net Operating Profit After Taxes (NOPAT), adding back non-cash charges, and netting out capital expenditures and working capital shifts.
* **Present Value Sizing:** Applies time-value discounting principles utilizing an adjustable Weighted Average Cost of Capital (WACC) matrix.
* **Terminal Value Rollup:** Captures long-term enterprise values utilizing the Gordon Growth Method, smoothly translating operational value to implied corporate equity valuations.

## 📈 Scenario Analysis & Flex Engine
The workbook includes an independent `Assumptions` core, enabling instantaneous macro toggles. Adjusting core baseline parameters—such as contract volume growth rates or target operational margins—will immediately recalculate the entire three-statement architecture and update the intrinsic asset valuation in real-time.

---
*Note: Designed for professional portfolio evaluation. Built entirely using advanced native cell logic and structured formula matrices.*
