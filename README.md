# Rashad (رشاد) – Interactive design prototype

Team Rashad · MED-76DNXQ · MEDATHON 2026, Filter 2

Rashad turns a patient's medicines into a clear daily schedule built around their own meal times. This repository contains a **click-through design prototype** of the patient flow.

## What the prototype shows
1. Photograph a medicine box. OCR (Tesseract.js, English and Arabic) runs inside the browser and the photo is never uploaded.
2. Rashad suggests the medicine by matching the OCR text against a list of 7 sample medicines; the user confirms or corrects it.
3. Enter breakfast, lunch and dinner times.
4. See a daily schedule with the patient's own package photo, the timing, and a plain-language reason for each medicine.
5. See a safety alert for a risky combination (warfarin with ibuprofen) that timing cannot fix.

## What it is not
- **Recognition is basic and its accuracy has not been measured.** It is generic OCR plus name matching against 7 medicines, not a trained medicine-recognition model. The user must always confirm.
- **The 7 sample medicines and their timing rules are demo content.** They have not yet been reviewed by a pharmacist and must not be used as medical guidance.
- Rashad organizes timing only. It does not change doses and does not replace a pharmacist or physician.

## Run it
Open `index.html` in any browser, or use the GitHub Pages link of this repository.

## Next steps
Measure OCR accuracy on real packages, extend coverage, build a pharmacist-reviewed rules database, and validation with pharmacists and older adults.
