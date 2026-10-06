# Pulm Rounds

A browser game for reviewing pulmonary pathology for USMLE Step 2 CK and the internal medicine shelf.

You walk into a 3D exam room with a patient, take a history, examine them by clicking body regions (lungs, neck, heart, hands, legs), and order labs, imaging, and procedures. Every action advances the clock and orders cost money. Results always come back, but some won't help. When you're ready, commit to a diagnosis and pick a management plan. The debrief grades you on:

- **Diagnosis (40):** partial credit for close calls (e.g., simple vs. tension pneumothorax).
- **Management (40):** essential and helpful orders earn points; not-indicated and harmful ones subtract.
- **Efficiency (20):** time and cost against a target, with penalties for low-yield or harmful tests.

Unstable patients (tension pneumothorax, severe asthma, ARDS) deteriorate on the vitals monitor as the clock runs.

## Cases

COPD exacerbation · severe asthma · pulmonary embolism · tension pneumothorax · community-acquired pneumonia · sarcoidosis · idiopathic pulmonary fibrosis · small cell lung cancer with SIADH · empyema · reactivation TB · obstructive sleep apnea · ARDS

## Running it

Open `index.html` in a modern browser. It loads Three.js r128 from cdnjs, so it needs an internet connection. No build step.

Chest X-rays are schematic canvas drawings, not real radiographs. Clinical content follows common Step 2 CK teaching (CURB-65, Wells, Light's criteria, Berlin ARDS definition, GOLD/GINA exacerbation management) and is for study only.
