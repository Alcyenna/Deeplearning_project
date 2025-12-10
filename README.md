# Deep Learning Project — Corrupted EMNIST Anomaly Detection & GAN Mode Collapse (MNIST)

Single team delivery; the final submission must be one pre-run notebook named `Name1Name2Name3.ipynb`, sent by email before the deadline (per course rules). This README is meant to be close to the final version; we will enrich it as we build.

## Goals
- Anomaly detection on a corrupted EMNIST dataset (unsupervised). Identify corruption, detect anomalies, propose recovery.
- GAN on MNIST without labels. Intentionally observe mode collapse, then mitigate it; report metrics and visuals.

## Repository layout
- `notebooks/` — main notebook lives here (placeholder present). Final pre-run notebook will be placed here.
- `data/` — datasets (ignored by git). Put the corrupted EMNIST here; document the sharing link below.
- `outputs/` — local results (ignored by git): figures, logs, checkpoints.
- `.venv/` — local virtual environment (ignored).
- `requirements.txt` — to be filled as dependencies are decided.
- `.gitignore` — excludes data/outputs/venv/caches/IDE files.

## Collaboration
- Work primarily in the notebook; keep it runnable end-to-end.
- Keep small, reviewed changes; document any reused external code (per course rule).
- Do not commit datasets

## Data (to be filled)
- Corrupted EMNIST source/link: TBD (e.g., Slack link). Place under `data/`.
- Expected format (tentative): `.npz` with `images` shaped `(N, H, W)` and optional `labels`.


## Deliverables checklist
- [ ] Single pre-run notebook `Name1Name2Name3.ipynb` covering both parts.
- [ ] Description of approach, what was tried/observed, and references for reused code.
- [ ] Anomaly detection: ≥2 unsupervised techniques; corruption identification; recovery attempt; evaluation metrics.
- [ ] GAN: multiple seeds/architectures; collapse observed; mitigations applied; metrics/visuals reported.

## Notes
- No MNIST labels allowed for the GAN task.
- Keep the final notebook runnable; heavy downloads cached in `data/` (ignored).

