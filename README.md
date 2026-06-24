# sp-pre

Interactive experiment dashboard for the stochastic finance course project:

**Reproducing and Extending Thompson Sampling for Non-Stationary Multi-Armed Bandits**

## Live Page

After GitHub Pages is enabled for this repository, the dashboard is published at:

```text
https://odsbaron.github.io/sp-pre/
```

## Local Preview

Open `index.html` directly in a browser, or start a local static server:

```bash
python3 -m http.server 8765
```

Then visit:

```text
http://localhost:8765
```

## Contents

- `index.html`: single-page experiment dashboard with key metrics, research logic, algorithm rankings, figure gallery, and reproducibility notes.
- `assets/figures/`: PNG figures copied from the full experiment output directory.
- `data/`: summary CSV and sweep CSV files copied from the full experiment output directory. Large raw CSV files are intentionally excluded.

Original data source:

```text
../00_extracted/ts_nonstationary_project/results
```
