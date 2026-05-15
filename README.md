# Health Records — Ivan Gorbunov

Personal medical records repository. Organized by specialty.

## Folder Structure

```
health-records/
├── psychiatry/          # Psychiatric consultations & treatment history
├── childhood/           # Childhood medical records (2009–2015)
│   ├── scans/           # Original scanned PDFs
│   └── *.md             # Structured extracted data
├── covid-testing/       # COVID-19 PCR tests
└── dietology/           # Weight management & nutrition consultations
```

## Psychiatry

**First contact with psychiatry:** June 2025 (no prior psychiatric history)

**Active diagnosis:** Depressive disorder with anxiety component

**Current medication (as of May 2026):** Wellbutrin (bupropion) 300 mg/day

### Treatment Timeline

| Period | Medications | Notes |
|--------|------------|-------|
| Jun 2025 | Escitalopram 10 mg + Bromazepam 1.5 mg | First psychiatric contact |
| Jul 2025 | Escitalopram 15 mg + Quetiapine 25 mg | Quetiapine poorly tolerated (hypersomnia, anhedonia) |
| Aug 2025 | Quetiapine discontinued (self) + Melatonin 1 mg | Some improvement |
| Aug–Sep 2025 | Lamotrigine 75 mg | Stopped — skin allergy reaction |
| Sep 2025 | Sertraline 50 mg + Bromazepam | Worsening; fatigue |
| Oct 2025 | Venlafaxine 75→150→112.5 mg | Nausea; slight improvement in depression |
| Nov 2025 | + Valproate 300 mg | Severe insomnia onset; discontinued 28.11.25 |
| Dec 2025 | Desvenlafaxine 100 mg | Dizziness episodes; mood more stable |
| Jan 2026 | Desvenlafaxine 150 mg (50 am / 100 midday) | Anxiety reduced |
| Feb 2026 | + Lamotrigine (titrated to 200 mg) | Sleep issues persist; fatigue |
| Mar 2026 | Lamotrigine discontinued; Desvenlafaxine → 100 mg | Simplifying regimen |
| Apr 2026 | Desvenlafaxine tapered off; Wellbutrin 150→300 mg | Positive energy shift; gym resumed |
| May 2026 | Wellbutrin 300 mg (150 am / 150 pm) | Managing irritability & sleep |

### Key History Notes

- Relocation stress (Turkey → Serbia, 2022) — prolonged isolation, daily alcohol use (~1 bottle wine/day for ~6 months)
- High sensitivity to SSRIs (sertraline, escitalopram) even at low doses
- Roaccutane use until early 2025
- Weight: 190 cm / 98 kg (+11 kg since starting antidepressants)
- Ozempic started 27.01.26 (0.25 mg → 0.125 mg → back to 0.25 mg)
- ADHD symptoms noted — to be evaluated after mood stabilization
- Smoking cessation planned (pulmonologist: Maxim Kopylov)

### Symptom Scores (latest — 01.05.26 context)

| Scale | Score |
|-------|-------|
| HADS | 2 / 11 (Feb 2026) |
| Beck Depression Inventory | 16 (9 cognitive / 7 somatic) |
| Burns | 51 |
| Zung | 55 / 69 |

---

## Dietology & Weight Management

**Chief issue:** ~20 kg weight gain over 1–1.5 years on antidepressants  
**Consultation date:** 27 January 2026  
**Current:** 101 kg / 190 cm (BMI 28.0); goal 80–86 kg

### Treatment Attempted

| Date | Intervention | Outcome |
|------|-------------|---------|
| Jan 2026 | **Semaglutide (Ozempic)** prescribed: 0.25→0.5→1.0 mg SC weekly | **Stopped** — non-responder (~1% of patients) |

### Key Findings
- Weight gain likely multifactorial: changed food preferences (toward fatty foods) on antidepressants + low daily activity + psychological stress
- High milk consumption (1–2 L/day)
- Labs ordered: CBC, glucose, lipid panel, liver/kidney function, TSH, vitamin D/B12, ferritin
- Desvenlafaxine 150 mg (current psychiatric med) has typical weight gain up to ~6 kg; current gain (~20 kg) exceeds this

---

## COVID-19 Testing

| Date | Test Type | Result | Lab |
|------|-----------|--------|-----|
| 07.08.2021 | PCR (nasopharyngeal swab) | **Negative** | Lifetime+ / LITEX |

---

## Childhood Records (2009–2015)

**Source:** Scanned paper documents (ДИСПАНСЕРИЗАЦИЯ_4__А.pdf, 14 pages)

> Note: Page 12 was a Belgrade lease agreement (2025) accidentally included in the scan — not a health document.

### Documents extracted

| File | Date | Contents |
|------|------|----------|
| `2009-04_dispensary_checkup.md` | Apr 2009, age 10 | Annual checkup: ophthalmology, ENT, orthopedics, pediatrics; **cardiology referral** |
| `2009-04_blood_count.md` | Apr 2009 | CBC — RBC slightly elevated, all else normal |
| `2009-2010_plantography.md` | Oct 2009 & Sep 2010 | Foot imprints — bilateral grade I flat feet (stable) |
| `2010-04_dispensary_checkup.md` | Apr 2010, age 11 | Annual checkup — vision improved; flat feet + posture noted |
| `2010-04_lab_results.md` | Apr 2010 | CBC + urinalysis — all essentially normal |
| `2010-04_ecg_and_posture_topography.md` | Apr 2010 | ECG (sinus rhythm) + computer spinal topography |
| `2015_ultrasound_and_bp_monitoring.md` | Apr–Jul 2015, age 16 | Abdominal ultrasound + 24hr BP monitoring |

### Key childhood findings summary

| Year | Finding | Significance |
|------|---------|--------------|
| 2009 | **Cardiology consultation referral** | Noted at age 10 — significant given 2015 hypertension |
| 2009–2010 | Flat feet grade 1 (bilateral) | Chronic, mild |
| 2009–2010 | Postural disturbance / scoliosis I° | Chronic, mild; resolved or stable |
| 2009–2010 | RBC mildly elevated (5.5–6.0 × 10¹²/l) | Recurrent, likely constitutional |
| 2010 | ECG: sinus rhythm, horizontal axis, HR 88–100 | Normal for age |
| 2015 | **Bilateral kidney microliths** (up to 1.2 mm) | Follow-up needed |
| 2015 | **Arterial hypertension** (avg 133/90, max 169/123 mmHg) | Significant — documented at age 16; unclear if followed up |

---

> ⚠️ This repository contains private medical information. Do **not** make it public.
