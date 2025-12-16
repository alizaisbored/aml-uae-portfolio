# AML Cheatsheet — Aliza Crypto Investigations

## 1. Quick KYC / CDD / EDD lines
- **KYC (Know Your Customer):** Verify full legal name, government ID, date of birth, residential address, contact details, and source of funds.  
- **CDD (Customer Due Diligence):** Identify beneficial owners, business purpose, expected transaction behavior, and counterparties; check sanctions lists and PEP status.  
- **EDD (Enhanced Due Diligence):** For high-risk customers/cases: gather corporate documents, UBO verification, provenance of funds, and corroborating documentation (bank statements, corporate filings).

## 2. Top 10 FATF Virtual-Asset Red Flags (paraphrased)
> Note: For legal/court use, replace these paraphrases with the exact FATF phrases from the official FATF PDF (link in this sheet). :contentReference[oaicite:4]{index=4}

1. Transactions that are inconsistent with the customer's profile (sudden large transfers).  
2. Rapid conversion between fiat and crypto across multiple platforms.  
3. Use of jurisdictions with weak AML controls in routing or chain flows.  
4. Use of mixers/tumblers or services intended to obfuscate origin.  
5. Structuring: many small transfers to avoid thresholds or reporting.  
6. Frequent self-transfers among many wallets (circular movement).  
7. Sudden change in counterparties or use of anonymous/temporary accounts.  
8. Use of P2P or OTC channels to move large volumes quickly.  
9. Funds linked to darknet marketplaces or known illicit addresses.  
10. Reluctance or inability to provide KYC documentation, or inconsistent documents.

*(To paste verbatim: open the FATF PDF, find the “red flag” section, copy each indicator line exactly and replace the matching numbered bullet above.)* :contentReference[oaicite:5]{index=5}

## 3. UAE Regulatory Notes — VARA & ADGM (quick)
- **VARA (Dubai Virtual Assets Regulatory Authority):** VARA issues the Virtual Assets and Related Activities Regulations (2023) covering licensing scope, permitted activities, and obligations for VASPs in Dubai. See VARA Rulebook and guidance for licensing and compliance details. :contentReference[oaicite:6]{index=6}  
- **ADGM AML Rulebook (Abu Dhabi Global Market):** ADGM maintains an AML & Sanctions Rulebook that sets out customer due diligence, suspicious activity reporting, and record-keeping obligations for firms operating in ADGM. Review AML chapters for reporting requirements and risk-based approach guidance. :contentReference[oaicite:7]{index=7}

## 4. Intake checklist — 4 quick questions to ask a client
1. **Exact wallet addresses / transaction hashes involved** (copy-paste address strings).  
2. **Timeline & urgency** — when did the transactions happen and how fast do you need a report? (48h, 3–5 days, litigation timeline)  
3. **KYC availability** — do you have client identification / corporate docs for the wallet owners?  
4. **Legal constraints / holds** — any court orders, preservation notices, or deadlines we must follow?

## 5. Suggested extra resources
- **TRM Academy** — extra training modules and certifications to supplement tracing skills. :contentReference[oaicite:8]{index=8}  
- FATF Virtual Assets Red Flag Indicators (official PDF) — use for exact legal wording. :contentReference[oaicite:9]{index=9}

## 6. Notes on evidence handling
- **Hash raw evidence** (e.g., TX data, screenshots) using SHA256; store hashes in an offline log. Maintain a chain-of-custody note for each file. Retain raw evidence hashed for **90 days** (default retention).

## 7. Acceptance / Proof
- Chainalysis screenshot saved to: `assets/certs/chainalysis.png`
- This cheat sheet file: `AML-cheatsheet.md` (committed)

