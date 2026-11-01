# Optimal Regret for Online Storage Control via Cumulative Policies

Research manuscript by **Kamiar Asgari and Michael J. Neely**.

**[Read the manuscript source](main.tex)** · [Bibliography](references.bib) · [Prepared source archive](arxiv-submission.zip)

This work studies online control of a scalar storage system with adversarial nonnegative arrivals and convex costs that depend on both storage and allocation. A controller must respect current resource availability before the current arrival and cost are revealed.

The manuscript reparameterizes simplex disturbance-action policies using cumulative allocation fractions. It develops a decay-weighted projected subgradient method and analyzes its regret, memory requirements, and lower bounds. Precise statements depend on the retention coefficient, cost assumptions, feedback model, and comparator class specified in the paper.

## Repository contents

| File | Purpose |
| --- | --- |
| [main.tex](main.tex) | Complete manuscript and proofs; LaTeX entry point. |
| [references.bib](references.bib) | Bibliographic sources. |
| [arxiv-submission.zip](arxiv-submission.zip) | Prepared source package. |
| [arxiv-upload-fields.txt](arxiv-upload-fields.txt) | Prepared submission metadata. |

The presence of submission files does not establish that a submission or publication has occurred. This repository currently supplies manuscript sources; it does not include a checked-in manuscript PDF or an implementation of the cumulative-policy algorithm.

## Source preparation

`main.tex` declares its LaTeX dependencies and uses BibTeX with `references.bib` and the `plain` bibliography style. The manuscript source is the reference for theorem assumptions, definitions, and attribution.

## Related work and code

- [Online Dynamic Resource Allocation with State Constraints](https://github.com/kamiaras/phd-last-paper) develops the simplex disturbance-action control setting.
- [Adversarial online control for finite-capacity storage](https://github.com/kamiaras/Adversarial-Online-Control-for-Finite-Capacity-Storage) contains related storage-control algorithms and experiments.

Those repositories are related projects, not a verified implementation or reproduction package for this manuscript's cumulative-policy results. Check the policy parameterization, assumptions, and manuscript version before comparing results.
