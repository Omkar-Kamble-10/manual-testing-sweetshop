# Defect Reports

## 1. Float Price + Standard Shipping → NaN Total
**Severity:** Critical  
**Steps to Reproduce:**
1. Open sweetshop.netlify.app
2. Add an item priced at £2.95 to the basket
3. Open basket and select "Standard Shipping"
**Expected:** Total = subtotal + £1.99  
**Actual:** Total displays as NaN

---

## 2. Integer Price + Standard Shipping → Concatenation Bug
**Severity:** Major  
**Steps to Reproduce:**
1. Add items totaling £21
2. Select "Standard Shipping"
**Expected:** £22.99  
**Actual:** Displays "211.99"
