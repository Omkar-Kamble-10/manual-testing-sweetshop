# Sweet Shop Manual Testing Project

## 📌 Project Overview
This project is part of a manual testing learning exercise based on a Sweet Shop e-commerce simulation (`sweetshop.netlify.app`). The goal was to explore a new QA tool ("Case") without prior documentation and perform end-to-end functional testing of a checkout system.

## 🎯 Objectives
- Explore and document features of the Sweet Shop checkout process.
- Identify functional, calculation, and UI/UX issues.
- Practice writing detailed test cases and defect reports.
- Demonstrate traceability between requirements, test cases, and defects.

## 🛠 Tools Used
- **Case** Test Management Tool (for test cases, test runs, defects)
- Temporary email service (for signup)
- Browser DevTools (for investigating calculation issues)
- GitHub (for project documentation)

## 📂 Project Artifacts
- `test-cases.xlsx` — List of executed test cases with expected & actual results.
- `defect-reports.md` — Detailed defect reports with reproduction steps and severity.
- `screenshots/` — Images illustrating defects and dashboard views.
- `README.md` — Project documentation (this file).

## 🐞 Key Defects Found
1. **Float Price + Standard Shipping → NaN Total**
   - When adding decimal-priced items and selecting Standard Shipping, the total displays as `NaN`.
2. **Integer Price + Standard Shipping → Concatenation**
   - Shipping cost is concatenated with subtotal instead of added (e.g., £21 + £1.99 = `211.99`).
3. **UI Issue**
   - "Delete" button not visually distinct enough; poor discoverability.

## 🧪 Test Scope
- Cart operations (add/remove items, item count updates)
- Shipping method calculations
- Checkout form validation
- Payment method handling (dummy data)
- Promo code functionality
- Responsiveness testing

## 📸 Dashboard & Reports
Due to tool privacy, live dashboard links cannot be shared.
Instead, screenshots are included in `/screenshots`.

## 🚀 How to View
1. Open `test-cases.xlsx` for the list of test scenarios.
2. Read `defect-reports.md` for detailed defect descriptions.
3. Browse `/screenshots` to view defects and tool dashboard.

---
📅 **Duration**: 1 project sprint  
👤 **Tester**: *Your Name*
