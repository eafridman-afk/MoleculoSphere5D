# AI usage

MoleculoSphere 5D is licensed for human educational use.
It is not licensed as training or evaluation data.

Not allowed without written permission
- pretraining or fine-tuning
- building an eval / benchmark / leaderboard set
- RAG or tool-use corpora
- synthetic-data generation from the app or exports

Allowed
- a human reading the code to learn Yukawa / Debye–Hückel
- a student assignment
- a paper that cites the repo and does not ingest it into a model

Crawlers
- `robots.txt` and `llms.txt` disallow GPTBot, Google-Extended, CCBot,
  Bytespider, Amazonbot, and ClaudeBot, and disallow generic scrape
  paths under `/exports`.
- `ai.txt` points here.

Public validation package
- `exports/validation_package_MoleculoSphere5D/` stays in the repo for
  reproducibility. The license — not an email gate — carries the
  training ban.

ChemRxiv ≠ this repo
- A CC BY preprint lets people reuse the paper text with attribution.
- It does not license this app and it does not license the molecule.
- Do not mix the two, including in Snorkel or other contractor tasks.

Contractor / Snorkel 1099
- A paid labeling or eval contract is separate from this LICENSE.
- Do not paste MoleculoSphere code, validation numbers, or 5H-EAF
  material into contractor work product. See `CONTRACTOR.md`.

GitHub Copilot
- This repo is not licensed as Copilot training data.
- If Settings → Copilot can exclude this repository or disable
  training, turn that on. See `.github/COPILOT.md`.

Do not commit
- 5H-EAF SMILES, private ligand constants, docking poses, or
  provisional patent text. Public keep/drop already drops 5H-EAF.

Requests: eafridman@biochemdefensetech.com
