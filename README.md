# Rooting the early SARS-CoV-2 phylogenetic tree

This repository contains code and data to make interactive Nextstrain trees for various possible roots of the early SARS-CoV-2 phylogenetic tree.

See [https://nextstrain.org/groups/jbloomlab/narratives/SARS2-rooting/early-SARS2-trees-v1](https://nextstrain.org/groups/jbloomlab/narratives/SARS2-rooting/early-SARS2-trees-v1) for a Nextstrain narrative that summarizes the various possible roots.
This narrative is the recommended way to interact with the trees.
You can also look at individual interactive trees for various possible roots at the following links:

 - Using sequences curated by [Crits-Christoph et al (2024)](https://www.sciencedirect.com/science/article/pii/S0092867424009012):

   * [lineage A + C29095T root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colormuts)
   *  [lineage A + C18060T root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C18060T-colormuts)
   * [lineage A root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-colormuts)
   *  [lineage B root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-B-colormuts)

 - Using sequences curated by [Lv et al (2024)](https://academic.oup.com/ve/article/10/1/veae020/7619252):

   * [lineage A + C29095T root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/lv2024-Feb-15-2020-lineage-A-C29095T-colormuts)
   *  [lineage A + C18060T root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/lv2024-Feb-15-2020-lineage-A-C18060T-colormuts)
   * [lineage A root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/lv2024-Feb-15-2020-lineage-A-colormuts)
   *  [lineage B root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/lv2024-Feb-15-2020-lineage-B-colormuts)

## Data and pipeline
Input data are in [./data/](data); see the README files therein for more details.
The configuration for the analysis is in [config.yaml](config.yaml).

To run the analysis, build the `conda` environment in [environment.yml](environment.yml), then activate it with:
    conda activate early-SARS2-trees

You can then run the `snakemake` pipeline in [Snakefile](Snakefile) with:

    snakemake -j <n_cpus>

Note that before doing this, you will need to download the GISAID sequences as they cannot be hosted in this repository due to GISAID data sharing restrictions.
See [data/crits-christoph2024/README.md](data/crits-christoph2024/README.md) and [data/lv2024/README.md](data/lv2024/README.md) for details on the accessions to download and how to name the resulting file.
To view the contributors of the GISAID sequences used in this analysis, visit [https://doi.org/10.55876/gis8.250518yk](https://doi.org/10.55876/gis8.250518yk).

The results of running the pipeline are placed in `./results/`, which is not tracked in this repo.
The final JSON files holding the Nextstrain trees are in the `./auspice/` directory.
The narrative describing these trees is in [./narratives/](narratives).

Note that different trees are built for all combinations:
  - the different sequence datasets (currently `lv2024` and `crits-christoph2024`)
  - the different date ranges (currently sequences from Jan-31 and earlier, and sequences from Feb-15 and earlier)
  - the different candidate roots (currently lineage A, lineage B, lineage A + C29095T, and lineage A + C18060T)
  - different default colorings of the tree. It should not really be necessary to make a different tree for each default coloring, but due to what appears to be a bug in the Nextstrain narrative rendering it can only show the default colorings.

## Displaying the interactive narrative and trees via `auspice`
The final trees in `./auspice/` and the narrative in [./narratives/](narratives) where they can be displayed as Nextstrain community builds or via a Nextstrain group.
