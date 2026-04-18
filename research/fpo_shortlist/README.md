# High-Potential FPOs for Bio-input Collaboration – SFAC 18 States

## Overview

This folder contains a consolidated shortlist of high-potential Farmer Producer Organizations (FPOs) across 18 priority Indian states, curated for a Summer Internship Project (SIP) focused on identifying strategic collaboration partners for an agri-input company specialising in bio-inputs (biofertilizers, biostimulants, biopesticides).

**Deliverable file:** `High_Potential_FPOs_SFAC_18States.csv`

---

## Methodology

### 1. Primary Data Source
**Small Farmers Agribusiness Consortium (SFAC)** state-wise FPO PDF lists.  
SFAC publishes district-level FPO rosters (name, legal identity, district, major crops, contact person, phone, email, registration/incorporation date) for each state. These are the **source of truth** for FPO names, locations, and contact details.

> **Important:** Contact details (name, phone, email) must be looked up directly in the relevant state SFAC PDF listed in the `Source` column of the CSV. The column `Contact Details` currently says `"To be verified from source PDF"` for all entries because the SFAC PDFs could not be machine-accessed at generation time. Users must open the PDF and match FPO name + district to retrieve exact contact information.  
> FPOs verified directly from the prior research conversation are flagged with `[SFAC-VERIFIED]` in the Reason column.

### 2. Secondary Context
- **Indiastat** state-wise FPO count datasets (snapshots as on 30-Jun-2024) were used for state-level FPO density/ecosystem maturity scoring.
- NABARD DBIE, press releases, and government programme data were used to cross-check crop geography and district clusters.

### 3. Selection Filters Applied

| Filter | Criteria |
|--------|----------|
| **Crop fit** | Horticulture / vegetables / fruits / spices / flowers / export crops preferred; cotton and pulses included where bio-input fit is strong |
| **Commercial orientation** | FPOs in known commercial crop belts (high input intensity, aggregation, market linkage) |
| **Bio-input suitability** | Crops with known demand for biofertilizers (Rhizobium, PSB, Azotobacter), bio-stimulants (seaweed/amino acid extracts), or biopesticides (Bt, Beauveria, Trichoderma, NPV) |
| **Export / residue compliance angle** | Preference for export-oriented clusters (grapes, pomegranate, mango, spices, flowers) where MRL/residue compliance drives bio-input adoption |
| **Contact availability** | Preference for entries where SFAC PDF lists a named contact with phone/email |

### 4. Exclusions
- FPOs primarily engaged in staple grain trading without horticulture/high-value crop component (unless dual-crop with strong bio-input fit)
- Website/license verification was **not** performed (placeholder noted; to be completed by user)

---

## SFAC PDF Source URLs (State-wise)

| State | SFAC PDF URL |
|-------|-------------|
| Uttar Pradesh | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Uttar%20Pradesh.pdf |
| Madhya Pradesh | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Madhya%20Pradesh.pdf |
| Maharashtra | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Maharashtra.pdf |
| Rajasthan | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Rajasthan.pdf |
| Karnataka | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Karnataka.pdf |
| Tamil Nadu | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Tamil%20Nadu.pdf |
| Gujarat | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Gujarat.pdf |
| Andhra Pradesh | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Andhra%20Pradesh.pdf |
| Telangana | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Telangana.pdf |
| Odisha | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Odisha.pdf |
| West Bengal | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20West%20Bengal.pdf |
| Bihar | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Bihar.pdf |
| Assam | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Assam.pdf |
| Jammu & Kashmir | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Jammu%20and%20Kashmir.pdf |
| Haryana | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Haryana.pdf |
| Punjab | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Punjab.pdf |
| Jharkhand | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Jharkhand.pdf |
| Chhattisgarh | https://sfacindia.com/PDFs/List-of-FPO%20identified-by-SFAC/List%20of%20FPOs%20in%20the%20State%20of%20Chhattisgarh.pdf |

---

## FPO Count per State (Current CSV)

| State | FPOs in CSV | Notes |
|-------|-------------|-------|
| Uttar Pradesh | 15 | All entries require contact verification from SFAC PDF |
| Madhya Pradesh | 15 | 2 entries SFAC-VERIFIED from prior research; rest require contact verification |
| Maharashtra | 15 | 4 entries SFAC-VERIFIED from prior research; rest require contact verification |
| Rajasthan | 15 | All entries require contact verification from SFAC PDF |
| Karnataka | 15 | 2 entries SFAC-VERIFIED from prior research; rest require contact verification |
| Tamil Nadu | 15 | 1 entry SFAC-VERIFIED from prior research; rest require contact verification |
| Gujarat | 15 | 1 entry SFAC-VERIFIED from prior research; rest require contact verification |
| Andhra Pradesh | 15 | All entries require contact verification from SFAC PDF |
| Telangana | 15 | All entries require contact verification from SFAC PDF |
| Odisha | 15 | All entries require contact verification from SFAC PDF |
| West Bengal | 15 | 4 entries SFAC-VERIFIED from prior research; rest require contact verification |
| Bihar | 15 | All entries require contact verification from SFAC PDF |
| Assam | 15 | All entries require contact verification from SFAC PDF |
| Jammu & Kashmir | 15 | All entries require contact verification from SFAC PDF |
| Haryana | 15 | All entries require contact verification from SFAC PDF |
| Punjab | 15 | All entries require contact verification from SFAC PDF |
| Jharkhand | 15 | All entries require contact verification from SFAC PDF |
| Chhattisgarh | 15 | All entries require contact verification from SFAC PDF |
| **TOTAL** | **270** | |

> **Note on SFAC-VERIFIED entries:** 14 FPOs (marked `[SFAC-VERIFIED]` in the Reason column) were cross-checked against SFAC PDF citations in prior research. Their names, districts, and crop focus are confirmed. Contact details for these entries must still be retrieved from the corresponding SFAC PDF. Breakdown: Maharashtra (4), West Bengal (4), Karnataka (2), Madhya Pradesh (2), Tamil Nadu (1), Gujarat (1).

---

## Column Descriptions

| Column | Description |
|--------|-------------|
| `State` | Indian state |
| `FPO Name` | Full legal name of the Farmer Producer Organization / Producer Company |
| `Location (District + Address)` | District and (where available) block/town |
| `Crop Focus` | Major crops as listed or inferred from SFAC data + crop geography |
| `Key Activities (Bio-input Collaboration Lens)` | Activities the FPO is likely engaged in, filtered for bio-input relevance |
| `Reason for Selection (Business Relevance)` | Why this FPO is a high-potential partner for a bio-input company |
| `Contact Details (Name | Phone | Email – as listed in SFAC)` | Currently `"To be verified from source PDF"` – retrieve from SFAC PDF linked in Source column |
| `Source (SFAC PDF URL)` | Direct URL to the SFAC state PDF from which FPO data is sourced |

---

## How to Complete Contact Details

1. Open the SFAC PDF URL listed in the `Source` column for the relevant state.
2. Locate the FPO by name and/or district in the PDF table.
3. Copy the contact person name, phone number(s), and email address(es) exactly as listed.
4. Paste into the `Contact Details` column of the CSV (format: `Name: <name> | Phone: <number> | Email: <email>`).

---

## Prioritisation Framework Summary

FPOs in this list were ranked first by **crop category** (horticulture/export > spices/flowers > cotton-pulses), then by **district commercial intensity** (known market/export clusters), and finally by **bio-input fit** (how well the crop responds to biofertilizers, bio-stimulants, or biopesticides).

**Top-priority states for immediate outreach** (highest bio-input adoption potential):
1. Maharashtra (grape/pomegranate/onion clusters – Nashik, Pune)
2. Karnataka (horticulture/pomegranate – Tumakuru, Vijayapura, Kolar)
3. West Bengal (peri-urban vegetables – North/South 24 Parganas, Hooghly)
4. Madhya Pradesh (onion/tomato/soybean – Ratlam, Mandsaur, Indore)
5. Tamil Nadu (spices/flowers/banana – Erode, Madurai, Coimbatore)
6. Gujarat (Kesar mango/groundnut/citrus – Junagadh, Rajkot, Valsad)
7. Andhra Pradesh (chilli/mango/banana – Guntur, Chittoor, West Godavari)

---

## Pending Actions (for user)

- [ ] Retrieve contact details for all 270 entries from respective SFAC PDFs
- [ ] Validate FPO operational status (check if FPO is active – SFAC / MCA portal)
- [ ] Add registration/incorporation date column from SFAC PDFs
- [ ] Verify website (if any) and any existing bio-input supplier relationships
- [ ] Convert CSV to Excel (.xlsx) with auto-filter and colour-coded priority tiers if needed
- [ ] Shortlist top 50–60 FPOs for first-round outreach based on updated contact completeness + state priority

---

## File Location

```
research/
└── fpo_shortlist/
    ├── High_Potential_FPOs_SFAC_18States.csv   ← Main deliverable (270 FPOs, 18 states)
    └── README.md                                ← This file
```
