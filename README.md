# **Internal Audit & Risk Assessment of Flipkart Checkout Process**

A consulting-style Governance, Risk & Compliance (GRCS) project evaluating the end-to-end checkout workflow of a leading e-commerce platform.
This project demonstrates skills in internal audit, risk assessment, control analysis, and compliance documentation.

---

## **1. Project Objective**

To assess the effectiveness of controls across the entire checkout lifecycle of Flipkart, identify operational, financial, security, and compliance risks, and recommend targeted improvements aligned with industry audit standards.

---

## **2. Scope of Assessment**

The project covers 12 key components of the checkout process:

* Product Listing Page (PLP)
* Product Details Page (PDP)
* Add to Cart
* Cart Summary
* Login & Authentication
* Address Validation & Pincode Mapping
* Delivery Options / SLA
* Payments & Payment Gateway
* Order Confirmation & Invoicing
* Backend Logging & Reconciliation
* Seller & Marketplace Controls
* Delivery Operations
* Returns, Refunds & Post-Order
* Data Security & API Integrity

Total Risks Assessed: **39**

---

## **3. Deliverables in Repository**

### **/Process-Flow/**

* `flipkart_checkout_process_flow.pdf`
  Visual representation of the complete “As-Is” checkout journey.

### **/Risk-Assessment/**

* `risk_identification_table.xlsx`
  All identified risks with likelihood & impact scoring.
* `risk_register.pdf`
  Formalized PDF version for audit documentation.

### **/Control-Gap-Analysis/**

* `control_gap_matrix.xlsx`
  Mapping of risks → existing controls → gaps → recommended controls.

### **/Audit-Checklist/**

* `checkout_internal_audit_checklist.xlsx`
  Auditor-ready checklist aligned to internal audit standards.

### **/Risk-Heatmap/**

* `risk_heatmap.xlsx`
* `risk_heatmap.pdf`
  Likelihood vs Impact matrix for all risks.

- `recommendations_and_sop_improvements.xlsx`
  39 actionable recommendations mapped to owners and priorities.

 - `executive_summary.pdf`
  One-page management summary.
---

## **4. Key Findings (Summary)**

### **High-Risk Gaps**

* Price mismatches across PLP → PDP → Cart
* Duplicate payments due to partial idempotency
* Incorrect GST/HSN mapping
* Delayed payment reconciliation
* API tampering risks due to weak request validation
* Missing or inconsistent logging
* Seller assignment & compliance weaknesses

### **Medium-Risk Gaps**

* Promo engine miscalculations
* Address validation failures
* Wallet/Gift card inconsistencies
* Return policy misclassification
* Courier & delivery mapping inconsistencies

### **Low-Risk Gaps**

* Minor PDP content inaccuracies
* Cosmetic quantity duplication issues

---

## **5. Skills Demonstrated**

* Risk identification & classification
* Internal audit methodology
* Control design evaluation
* Compliance verification (GST, PCI-DSS, KYC)
* SOP drafting & process improvement
* Data-driven decision-making
* Professional documentation for consulting contexts

---

## **6. Tools & Methods Used**

* Microsoft Excel (risk register, gap analysis, checklist)
* PDF documentation for audit-ready deliverables
* Process mapping and workflow documentation
* Likelihood–Impact risk scoring
* Control effectiveness evaluation
* Audit reporting structure (Executive Summary format)

---

## **7. Why This Project Matters**

This repository showcases the ability to think like a **GRCS consultant**, not just a student building a project.
Anyone reviewing your portfolio gets proof that you can:

* Break down a complex business process
* Identify real operational & financial risks
* Evaluate existing controls intelligently
* Recommend improvements with business reasoning
* Produce clean, audit-ready documentation
---

## **8. How to Navigate This Repository**

Each folder corresponds to a distinct deliverable that mirrors real internal audit documentation.
Start with:

1. **Process-Flow** → understand the process
2. **Risk-Assessment** → see the risks
3. **Control-Gap-Analysis** → understand where controls fail
4. **Audit-Checklist** → what an auditor tests
5. **Risk-Heatmap** → overall risk profile
6. **Recommendations** → what should be fixed
