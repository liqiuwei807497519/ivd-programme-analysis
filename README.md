# IVD programme analysis

Project-authored software for separating programme abundance, complete-member allocation and regional probability prediction in spatial transcriptomics. The companion manuscript is *Programme abundance and member fidelity in spatial studies of intervertebral disc degeneration*. This repository makes the implemented software available; it is not a claim of algorithmic novelty, independent adult-disc validation or journal acceptance.

## Source packages

The archives preserve their module directories and contain readable source files, requirements, source fingerprints and usage instructions. They contain no study count arrays, trained checkpoints, medical/animal records, credentials or bundled scientific runtimes.

| Package | Contents |
| --- | --- |
| [Manuscript_Code_Components_20261007_v3.zip](Manuscript_Code_Components_20261007_v3.zip) | Regional-count models, native rat RNA, nonlinear count comparison, human prepared-count statistics, FieldLaw aggregate scoring, prepared-figure code and path-parameterized historical context scripts. |
| [Regional_Count_Probability_Code_20261007_v2.zip](Regional_Count_Probability_Code_20261007_v2.zip) | Native-XGBoost mean prediction, source-only NB2/PIT calibration, five coherent count laws, exact empirical-quantile scoring and saved-world replay; original synthetic tests included. |
| [External_RNA_Figure_Code_20261007_v2.zip](External_RNA_Figure_Code_20261007_v2.zip) | Figure7/S12 builder and project-authored style helper, with explicit input/output paths and source provenance. |

Extract each archive into its own directory, then follow its README. Do not flatten the import trees. For example:

```text
python -m zipfile -e Regional_Count_Probability_Code_20261007_v2.zip external_rna_probability
```

## Checked software behavior

The external-RNA core's 13 distinct original synthetic tests passed in a relocated directory, using the recorded scientific environment. They exercise native-count offsets, source-only dispersion/correlation arithmetic, coherent world/ROI projections, proper scores, rational quantiles and hash-bound replay. The native-XGBoost tests fit artificial three-row examples; no paper model was refitted.

The historical figure/context adapters expose explicit roots. Their help and input-description interfaces were tested without importing scientific packages or opening project data. Original scientific AST nodes were preserved except the declared path bindings. Their complete real-data workflows were not rerun as part of this software release. Earlier component tests and prepared-output replay scopes are documented separately in the manuscript-code package; data-dependent tests require their separately supplied lawful inputs.

These software checks establish stated arithmetic and interface behavior. The paper's observed results come from the separately archived studies, not from synthetic examples or a code-release test count.

## Data and reproducibility scope

Complete source tables, result packets, frozen predictions and scoped replay inputs are supplied in the manuscript's Additional Files1–28. Those submission materials are distinct from this code-only repository; no public data DOI is assigned here. Raw/source-data access and redistribution follow the original studies. Private CTM inputs, historical acquisition conditions and source-training reconstruction are not replaced by a synthetic example.

The figure builder requires the source tables described in its README. Font availability and scientific-package installation remain system dependencies; font binaries and third-party packages are not distributed. Use the recorded module-specific requirements rather than assuming one environment can run every historical workflow.

## Licensing

[LICENSE](LICENSE) covers original project-authored software. Libraries, fonts, datasets and articles retain their own licenses and access conditions. Source-copy fingerprints and declared path-only adaptations are recorded within each package. No third-party data rights are created by this license.

For versioned citation and audit, use the immutable repository commit for this release together with [FILES_SHA256.tsv](FILES_SHA256.tsv). A GitHub repository is public source availability, not a registered DOI or a journal-submission receipt.
