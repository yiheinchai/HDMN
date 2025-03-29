## High-Density Medical Notation (HDMN) Specification - Version 1.0

**1. Purpose & Principles:**

*   **Purpose:** To allow rapid, standardized, and extremely concise recording of key clinical information (Symptoms, Investigations, Management) for personal study, quick review, and knowledge consolidation.
*   **Audience:** Medical students, junior doctors, or clinicians familiar with standard medical terminology and abbreviations.
*   **Core Principles:**
    *   **Brevity:** Prioritize conciseness above all else, using symbols and abbreviations extensively.
    *   **Standardization:** Use consistent syntax and symbols for readability among users familiar with HDMN.
    *   **Information Density:** Pack maximum relevant information into minimum space.
    *   **Context Dependency:** Relies heavily on standard medical abbreviations and the context of the disease/category.
    *   **Focus:** Emphasize discriminating features, key diagnostics, and prioritized management steps.
    *   **Not for Formal Records:** This notation is NOT intended for official patient records, discharge summaries, or legal documentation due to its heavy abbreviation and potential for ambiguity without context.

**2. Core Syntax & Delimiters:**

*   **Primary Separator (;)**: Semicolon separates distinct, top-level points within a category (e.g., different symptoms; different investigation modalities; different management steps/categories).
    *   *Example (Symptoms):* `CP (crushing, retrosternal); SOB; Diaphoresis`
*   **Secondary Separator (,):** Comma separates related items within a primary point (e.g., listing multiple features of a symptom; different findings within one investigation; drugs within the same class or step).
    *   *Example (ECG Findings):* `ECG (ST↑ concave, PR↓ widespread, +/- TWI)`
    *   *Example (Drugs):* `Rx: BB (Bisoprolol, Metoprolol); ACEi (Ramipril)`
*   **Qualifier/Detail Grouping ( ):** Parentheses enclose specific details, qualifiers, explanations, units, timing, or examples related to the preceding item.
    *   *Example (Pain):* `CP (pleuritic, ↓sitting forward)`
    *   *Example (Drug Dose):* `Aspirin (300mg stat, then 75mg OD)`
    *   *Example (Timing):* `PCI (<120min)`
*   **Optional / Also Consider (+/- or ?):** Plus/minus or question mark can indicate less common, optional, or 'consider if...' items. Use sparingly for clarity.
    *   *Example:* `Echo (+/- effusion)` or `Echo (?effusion)`
*   **Prioritization / Sequencing (Numerals):** Use `1.`, `2.`, `3.` for sequential steps, especially in Management. Use `1L:`, `2L:`, `3L:` for first-line, second-line etc. where strict sequence isn't implied.
    *   *Example (Mx):* `1. Lifestyle; 2. BB/CCB; 3. Add Nitrate`

**3. Standard Symbols:**

*   `↑` : Increased, elevated, worsened, more likely
*   `↓` : Decreased, reduced, relieved by, less likely
*   `->`: Leads to, causes, results in
*   `~` : Associated with, often occurs with
*   `R/O`: Rule out
*   `A/F`: Assess for, check for
*   `w/` : With
*   `w/o`: Without
*   `(+)` : Positive for, present
*   `(-)` : Negative for, absent
*   `Hx`: History
*   `Rx`: Treatment / Prescription
*   `Mx`: Management
*   `Sx`: Symptoms
*   `Ix`: Investigations
*   `Dx`: Diagnosis
*   `Δ`: Change / Differential (use contextually, e.g., `Δ murmur` = changed murmur; `ΔDx` = Differential Diagnosis)
*   `@`: At (e.g., `@ apex`)
*   `>` / `<`: Greater than / Less than (Use numerals where possible, e.g. `HR>100`)
*   `≥` / `≤`: Greater than or equal to / Less than or equal to
*   `♀` / `♂`: Female / Male (Use sparingly)

**4. Standard Abbreviations (Non-Exhaustive List - Relies on Medical Context):**

*   **Common Conditions/Sx:** MI, ACS, PE, DVT, HF (CHF), HTN, DM, CKD, AF, VT, VF, SVT, LBBB, RBBB, CP, SOB, LOC, N/V, Palps, Oedema, JVP, HSM (Hepatosplenomegaly), SCD (Sudden Cardiac Death)
*   **Investigations:** ECG, CXR, Echo (TTE/TOE), CT (CTPA), MRI (CMR), Angio (Coronary Angiography), ABG, VBG, FBC, U&E, LFT, TFT, BNP, TnT/I, CRP, ESR, BCx, Trop, Lipids, HbA1c, Mg, K, Ca
*   **ECG Findings:** ST↑, ST↓, TWI, Qwv (Q waves), LVH, RVH, LAE, RAE, PR↑, QT↑, HR, NSR (Normal Sinus Rhythm), RAD, LAD
*   **Management/Drugs:** O2, GTN, ASA (Aspirin), Clopi (Clopidogrel), Tica (Ticagrelor), Pras (Prasugrel), BB (Beta-blocker), ACEi, ARB, CCB, MRA (Mineralocorticoid Receptor Antagonist), SGLT2i, DOAC, LMWH, UFH (Unfractionated Heparin), Warf (Warfarin), Statin, Diuretic (Loop/Thiazide), Dig (Digoxin), MgSO4, Adr (Adrenaline), Atro (Atropine), Amio (Amiodarone), Lido (Lidocaine), Adeno (Adenosine), NSAID, PPI
*   **Procedures/Devices:** PCI, CABG, AVR, MVR, TAVI/TAVR, PPM (Pacemaker), ICD, CRT, Ablation, CV (Cardioversion), Thrombolysis, ECMO, IABP, PTCA (old term for PCI), EP study
*   **Timing/Dosing:** Ac (Acute), Chr (Chronic), LT (Long Term), ST (Short Term), Stat, OD, BD, TDS, QDS, PRN, PO, IV, SC, IM, SL, mcg, mg, g, IU, mmol/L
*   **Other:** L), R) (Left, Right), Bilat (Bilateral), Uni (Unilateral), Ant, Post, Inf, Sup, Lat, Med, S1/S2/S3/S4 (Heart sounds), ESM (Ejection Systolic Murmur), PSM (Pansystolic Murmur), MDM (Mid-Diastolic Murmur), EDM (Early Diastolic Murmur)

**5. Category-Specific Guidelines:**

*   **Symptoms:**
    *   Start with cardinal/most common symptom(s).
    *   Use parentheses for key descriptors (quality, radiation, timing, triggers, relievers).
    *   Follow with significant associated symptoms.
    *   Mention key negatives if highly relevant (e.g., `CP (non-pleuritic)`).
    *   *Example:* `CP (central crushing, -> L) arm/jaw, exertional, ↓rest/GTN); SOB; Diaphoresis; N/V`
*   **Investigations:**
    *   List key diagnostic modalities first (ECG, Echo, specific bloods, imaging).
    *   Follow modality with key findings in parentheses `()`.
    *   Mention relevant scoring systems/criteria.
    *   *Example:* `ECG (ST↑ Ant leads V1-V4; Recip ST↓ Inf); Trop↑ (serial); Echo (Ant wall hypokinesis); Angio (LAD occlusion)`
*   **Management:**
    *   Distinguish Acute vs. Chronic/LT where applicable.
    *   Use numbering for steps or prioritization `1.`, `2.`, etc.
    *   Group interventions (e.g., `Pharm:`, `Surg:`, `Device:`, `Lifestyle:`).
    *   Specify drug class then example(s) `BB (Bisoprolol)`. Include key doses/timing if critical `ASA (300mg Stat -> 75mg OD)`.
    *   Note key monitoring `(monitor K+, INR)`.
    *   *Example (ACS Mx):* `Ac: MONA+ (O2 if<94%, ASA 300mg, GTN, Morphine PRN, Ticagrelor 180mg); STEMI -> PCI (<120min) / Lysis (>120min); NSTEMI -> Risk strat (GRACE), +/- Angio/PCI. LT: DAPT (ASA+Tica 12mo); BB; ACEi; Statin (high-dose); Lifestyle.`

**6. Example Application (Pulmonary Embolism):**

*   **Symptoms:** `SOB (sudden); CP (pleuritic); Tachypnoea; Tachycardia; +/- Cough, Haemoptysis, DVT Sx (leg swell/pain), Syncope (massive)`
*   **Investigations:** `Wells Score (>4 likely, ≤4 unlikely); If likely -> CTPA (1L) / VQ scan (renal/allergy); If unlikely -> D-dimer (if (-), R/O PE; if (+), -> CTPA); CXR (often normal; +/- wedge/effusion); ECG (Sinus tachy common; +/- S1Q3T3, RBBB)`
*   **Management:** `Rx: DOAC (Apixaban/Rivaroxaban 1L) OR LMWH -> Warf/Dabig/Edox; Duration (Provoked 3mo; Unprovoked 6mo+); Massive PE (shock) -> Thrombolysis (Alteplase) +/- Embolectomy; +/- IVC Filter (if anticoag C/I)`

**7. Extensibility & Customization:**

*   Users can adopt additional standard abbreviations common in their specific field or institution, but should aim to keep core symbols and syntax consistent for interoperability.
*   For personal use, minor deviations are acceptable if consistently applied by the individual.
