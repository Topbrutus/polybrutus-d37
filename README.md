# Polybrutus 37D — Exact 42-point Euclidean metric and 31-fold ideal graph mode

**Human scientific author and responsibility:** Gabriel St-Pierre, independent researcher.  
**Material AI assistance:** OpenAI ChatGPT (Astra) assisted exact mathematical derivations, two separately implemented checkers, the manuscript, and publication. AI is not a scientific author.

## Exactly reproducible results (R=1)

- **42 distinct unit vertices**; **861 unordered labelled squared-distance pairs**; exact minimum Euclidean affine dimension **37**.
- **820/820** predecessor labelled squared distances preserved from the frozen [Polybrutus D36 scientific tag](https://github.com/Topbrutus/polybrutus-d36/tree/v0.1.0), scientific commit `b1f8be2cdcdcae0d9911d90381a7b1304c84abf0`, DOI [10.5281/zenodo.24413083](https://doi.org/10.5281/zenodo.24413083).
- One newly appended perpendicular norm-one point adds **41** exact squared distances, each **2R²**.
- Normalized squared-distance class histogram `k=4d²/R²`: `{4:6,7:2,8:830,9:3,10:10,12:6,13:2,16:2}`; exact sum of squared distances at R=1 **6935/4**.
- Exact rational positive-semidefinite centered Euclidean Gram rank **37**.
- For one **separately stipulated mathematical ideal complete weighted graph** with unit scalar masses and symmetric edges `w_ij=R²/d_ij²`, weighted Laplacian eigenvalue **21** has exact multiplicity **31**, and **41/2** has multiplicity **4**. These dimensionless model eigenvalues are not experimentally measured physical frequencies.
- Two separately implemented exact-rational programs verify all 861 distance labels, all 820 frozen parent labels, exact Euclidean rank, and selected graph eigenspaces. Four primary negative controls pass.

## Reproduce

```bash
python -m pip install sympy==1.14.0
python src/verify_d37.py
python tests/independent_d37.py
```

Both programs print identical SHA-256 for deterministic `results/certificate_d37.json`. The entire frozen D36 scientific source and inherited ancestors are archived under `prior/d36/` as ordinary files via `git archive`, with no nested `.git` metadata or submodules.

## Official DOI and verified public release

- **Official DOI:** [10.5281/zenodo.24413346](https://doi.org/10.5281/zenodo.24413346).
- **Public Zenodo record:** https://zenodo.org/records/24413346, all 3 files verified against sizes and MD5 with Zenodo public API.
- **Frozen scientific source:** [v0.1.0](https://github.com/Topbrutus/polybrutus-d37/tree/v0.1.0), commit `294be7f814f2c8770af806833e98194fb192afff`.
- **Tag CI:** [GitHub Actions 44877731333](https://github.com/Topbrutus/polybrutus-d37/actions/runs/44877731333), success.
- **Durable checkpoint:** https://github.com/Topbrutus/topbrutus_one/blob/main/memoria/checkpoints/POLYBRUTUS_D37_PUBLICATION_2026-11-21.md .
- **Publications registry:** https://github.com/Topbrutus/topbrutus_one/blob/main/memoria/projects/POLYBRUTUS_X72_PUBLICATIONS_INDEX.md .

## Scientific materials

- [Exact specification](SPECIFICATION_D37.md), [proof and adversarial checks](PREUVE_D37.md), [scientific provenance](PROVENANCE.md).
- [Scientific PDF preprint](publication/POLYBRUTUS_37D_NOTE.pdf), [Markdown manuscript](publication/POLYBRUTUS_37D_NOTE.md), [complete 861-pair distance certificate](results/certificate_d37.json).

**Scope and limitations:** One specifically constructed synthetic exact Euclidean metric and one chosen ideal graph, using established mathematical methods. This work does not prove extra physical spacetime dimensions, measured resonances, new particles, a new universal theorem, or independent human peer review.

**Licences:** code MIT, scientific manuscript CC BY 4.0.
