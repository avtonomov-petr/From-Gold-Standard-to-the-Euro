# From Gold Standard to the Euro: Global Currency Blocs, Bretton Woods Realignments, and Floating Regimes, 1870–2013

[![License: MIT](https://shields.io)](LICENSE)

This repository contains the reproducible Python/Jupyter calibration pipeline, high-resolution figures, open-access Clio Infra dataset, and LaTeX manuscript sources for the study:

> **Avtonomov, P. (2026e).** *From Gold Standard to the Euro: Global Currency Blocs, Bretton Woods Realignments, and Floating Regimes, 1870–2013.*

This work is the fifth study in a multi-layer empirical research cycle auditing historical and modern market integration across Atlantic grain prices ([doi:10.5281/zenodo.24436177](https://doi.org)), Baltic Sound Toll shipping passages ([doi:10.5281/zenodo.24461586](https://doi.org)), St. Petersburg–European exchange rates ([doi:10.5281/zenodo.24498028](https://doi.org)), and the Eurasian silver corridor ([doi:10.5281/zenodo.24508139](https://doi.org)).

## Key Calibration Findings

* **Regime Signatures in $(\mathrm{PR}(u_1), \mathrm{PR}(v_1))$ Space:** Fixed-parity pegs (Bretton Woods `1946–1971`, $\mathrm{PR}(u_1) = 0.060$ in USD; $0.008$ in GBP) and institutional currency conversions (the `1999` Euro launch, $\mathrm{PR}(u_1) = 0.043$ in USD; $0.010$ in GBP) exhibit extreme temporal localization, whereas multi-country depressions (`1919–1939`) produce high spatial participation ($\mathrm{PR}(v_1) = 0.735$) across sequential shocks (`1920` deflation `26.4%`; `1932–1934` gold-bloc breakup `37.5%`).
* **Blind Eurozone Identification (`1973–2013`):** Without regional labels or dummy variables, Mode 1 isolates the seven largest future Eurozone contributors (`Netherlands`, `France`, `Finland`, `Belgium`, `Spain`, `Portugal`, `Italy`), capturing `73.7%` of Mode 1 spatial variance in USD (`90.8%` in GBP), while Mode 2 ($\mathrm{Var}_2 = 17.6\%$) isolates Latin American debt-crisis economies.
* **Numeraire Invariance:** Re-estimating the entire diagnostic directly on British pound sterling (`GBP`) quotations ($N = 20$) confirms that the regime hierarchy is invariant to the choice of anchor currency.

## Repository Contents

* `reproduce_modern_fx.ipynb` / `reproduce_modern_fx.py` — End-to-end reproducible Python script generating all regime diagnostics, 95% subsampling bootstrap confidence intervals, and `300 dpi` figures.
* `Figure_1_ModernFX.png`, `Figure_2_ModernFX.png` — Publication-grade (`300 dpi`) figures.
* `From_Gold_Standard_to_the_Euro.pdf` / `main.tex` — Compiled preprint and LaTeX source.
* `ExchangeRatestoUKPound_Compact.xlsx` — Clio Infra historical exchange rate dataset (`1500–2013`).
