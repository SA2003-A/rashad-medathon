# Rashad (رشاد) – Interactive design prototype

Team Rashad · MED-76DNXQ · MEDATHON 2026, Filter 2

Rashad turns a patient's medicines into a clear daily schedule built around their own meal times. This repository contains a **click-through design prototype** of the patient flow.

## What the prototype shows
1. Photograph a medicine box (the photo stays in the browser and is never uploaded).
2. Confirm the medicine.
3. Enter breakfast, lunch and dinner times.
4. See a daily schedule with the patient's own package photo, the timing, and a plain-language reason for each medicine.
5. See a safety alert for a risky combination (warfarin with ibuprofen) that timing cannot fix.

## What it is not
- **Medicine recognition is simulated.** The user picks the medicine from a list; there is no OCR or AI yet.
- **The 7 sample medicines and their timing rules are demo content.** They have not yet been reviewed by a pharmacist and must not be used as medical guidance.
- Rashad organizes timing only. It does not change doses and does not replace a pharmacist or physician.

## Run it
Open `index.html` in any browser, or use the GitHub Pages link of this repository.

## Next steps
Build a working MVP with Arabic and English OCR, a pharmacist-reviewed rules database, and validation with pharmacists and older adults.
