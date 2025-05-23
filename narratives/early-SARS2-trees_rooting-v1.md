---
title: Rooting SARS-CoV-2 phylogenetic tree
authors: Jesse Bloom
authorLinks: https://jbloomlab.org/
date: 2025-05-19
dataset: "https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colormuts"
abstract: '

Determining the "root" (or most-recent-common-ancestor, MRCA) of SARS-CoV-2 is important for understanding its emergence and early evolution.


SARS-CoV-2 derives from bat SARS-like coronaviruses, so the root of the tree might be expected to be the SARS-CoV-2 sequence most similar to bat coronaviruses, as subsequent evolution in humans would make SARS-CoV-2 more different from these relatives.
This is _outgroup_-based rooting.


The tree at right shows early SARS-CoV-2 sequences with the root at a cluster of viruses among the most similar to the bat coronavirus relatives.
The mutations on branches leading away from this root (eg, T29095C, C28144T, T8782C) all make SARS-CoV-2 more different than its bat coronavirus relatives (eg, those relatives have T at site 29095, C at 28144, and T at site 8782).


The tree at right is colored according to how many mutations each sequence has relative to the inferred bat ancestor of SARS-CoV-2 (recombinant common ancestor, recCA).
As you move away from the root of the tree (to the right), descendants have more mutations relative to the recCA, as expected as the virus evolves aways from its bat coronavirus relatives.


So if we just think about how similar each sequence is to bat SARS-like coronaviruses (ie, _outgroup_ rooting), the tree at right makes sense.
But...
'
---

# [But the sequences most similar to bat coronaviruses are not the first ones collected](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colordates)

We might also expect the first SARS-CoV-2 sequences collected from humans to be at the root of the tree.
This idea is _date_-based rooting.

But when we color the tree by the date on which sequences were collected as shown at right, we see that the first-collected sequences aren't at the root when the tree is rooted on the sequences most similar to bat coronaviruses!


Instead, the first collected sequences are mostly in cluster that has three additional mutations away from bat coronaviruses (T29095C, C28144T, and T8782C) relative to the root of the tree (you can see this more clearly by mousing over the blue box for December 2019 at the color key in the upper left).

# [But if we root on first collected sequences, then sequences most similar to bat coronaviruses are descendants](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-B-colormuts)

We can instead use _date_-based rooting to place the root of the tree on the first collected sequences, as shown at right.

But then if we color the tree by how many mutations separate each SARS-CoV-2 sequence from the inferred bat coronavirus ancestor (recCA) as shown at right, the sequences closest to the bat coronavirus ancestor are not near the root of the tree.
This rooting requires that the early evolution of SARS-CoV-2 in humans involved multiple mutations (eg, C8782T, T28144C, and C29095T) that all happened to make SARS-CoV-2 more similar to its bat coronavirus relatives.

# [Outgroup- and date-based rooting are inconsistent](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-B-colormuts?l=scatter&scatterX=num_date&scatterY=mutations_from_recCA)

Another way to look at the data is to simply make a scatter plot of the date on which each sequence was collected versus how many mutations it has relative to the bat coronavirus relative recCA, as shown at right.

This scatter plot shows how the first human sequences collected are _not_ the most similar to the bat coronavirus relatives.
In other words, the dots representing the first collected sequences (the ones furthest to the left) are _not_ the sequences most similar to the bat coronavirus ancestor (the ones furthest towards the bottom).

This discrepancy between outgroup- and date-based rooting was first analyzed in detail in a paper by [Pipes et al (2020)](https://academic.oup.com/mbe/article/38/4/1537/6028993) who concluded:

_"These results suggest that phylogenetic evidence alone is unlikely to identify the origin of the SARS-CoV-2 virus and we caution against strong inferences regarding the early spread of the virus based solely on such evidence."_

# [Relevance to Huanan Market](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-coloraddtlannotations?l=scatter&scatterX=num_date&scatterY=mutations_from_recCA)

How to root the phylogenetic tree is relevant to the role of the Huanan Seafood Market, namely whether it was where the virus first entered humans or simply a downstream superspreading event.

This can be seen by looking at the scatter plot at right, which again shows the date on which sequences were collected versus how similar they are to the bat coronavirus ancestor.
The points are now colored by whether sequences are from patients that the [joint-WHO China report](https://www.who.int/publications/i/item/who-convened-global-study-of-origins-of-sars-cov-2-china-part) (page 76) says had symptom onset prior to Dec-31-2019 annotated by whether or not that patient visited the Huanan Market, or from environmental samples [collected from the Huanan Market by the Chinese CDC on Jan-1-2020](https://www.nature.com/articles/s41586-023-06043-2).

As can be seen from the plot at right, the sequences from early patients who visited the Huanan Market and environmental samples from the Huanan Market are _not_ among those most similar to the bat coronavirus ancestor.

# [Huanan Market sequences are not at the _outgroup_-based root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-coloraddtlannotations)
So if the tree is rooted at one of the clusters of sequences most similar to the bat coronavirus ancestor, then the Huanan Market sequences appear as descendants of other sequences that are not from patients who visited the Huanan Market (or environmental samples from the Huanan Market).

This can be seen most clearly by mousing over the boxes defining the colors for the Huanan Market sequences in the color key at upper left of the tree at right, which uses an outgroup-based root.

# [Huanan Market sequences are at the _date_-based root](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-B-coloraddtlannotations)

In contrast, if the tree is rooted at main cluster of the earliest sequenced patients, then Huanan Market sequences appear as among the earliest ones.

This can be seen most clearly by mousing over the boxes defining the colors for the Huanan Market sequences in the color key at upper left of the tree at right, which uses a date-based root.

# [An aside on lineage A versus B](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colorlineage)

Scientific literature about rooting the SARS-CoV-2 tree uses the nomenclature "lineage A" and "lineage B."

SARS-CoV-2 is continuously evolving, and to keep track scientists classify related sequences into "lineages."
There are currently >5,000 [different designated SARS-CoV-2 lineages](https://github.com/cov-lineages/pango-designation/blob/master/lineage_notes.txt).

The first two lineages named were called A and B, and differ by just two mutations (at sites 8782 and 28144).
These lineages are labeled on the tree at right: lineage A has T8782 / C28144, and lineage B has C8782 / T21844.
The tree at right is outgroup-rooted, so you can see that lineage A is more similar to the bat coronavirus ancestor but lineage B contains the earliest sequenced human cases from the Huanan Seafood Market.
This fact was noted in the [first scientific paper](https://www.nature.com/articles/s41564-020-0770-5) defining the lineages: _"although viruses from lineage B happen to have been sequenced and published first, it is likely (based on current data) that the most recent common ancestor (MRCA) of the SARS-CoV-2 phylogeny shares the same genome sequence as the early lineage A sequences."_

There are also some sequences genetically intermediate between lineages A and B.
Some of these intermediates are [errors](https://www.science.org/doi/full/10.1126/science.abp8337), but for a while there was a [dispute](https://www.mdpi.com/2036-7481/14/1/33) about whether some were also real.
A [2024 paper by Yong-Zhen Zhang's group](https://academic.oup.com/ve/article/10/1/veae020/7619252) shows that some human SARS-CoV-2 sequences truly do have T8782 / T28144 identities that make them genetically intermediate to lineages A and B.
So lineages A and B are connected by single mutations, but it is still useful to use this nomenclature scheme as is done below...

# [What is the correct root? There is no consensus...](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-B-coloraddtlannotations)

Due to the discrepancy between outgroup- and date-based rooting, there is not a consensus on this question.
The table at right summarizes some scientific papers that address this question.

Below are links to interactive trees rooted at each candidate that has been proposed.
The trees at these links are interactive, with dropdowns to color the sequences by mutations from the ancestor, collection date, lineage, or other annotations (eg, whether from Huanan Market)--so explore them yourself:

 - [lineage A + C29095T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colormuts): one of the sequence clusters most similar to bat coronavirus ancestor, but does not contain early sequences from Huanan Market.
 - [lineage A + C18060T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C18060T-colormuts): one of the sequence clusters most similar to bat coronavirus ancestor, but does not contain early sequences from Huanan Market.
 - [lineage A](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-colormuts): the defined Pango lineage closest to bat coronavirus ancestor (although less close than variants with C29095T or C18060T); none of the early sequences from the Huanan Market are lineage A itself, although one environmental sample from Jan-1-2020 is lineage A plus two derived mutations).
 - [lineage B](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-B-colormuts): more distant from bat coronavirus ancestor, but early human sequences and most environmental sequences from Huanan Market are lineage B.

```auspiceMainDisplayMarkdown

## Brief summary of scientific papers that try to root SARS-CoV-2 tree.
See links to papers in table below to read full details of each study.

| Paper (lead and corresponding authors) | Conclusions about rooting of tree |
| -------- |------|
| [Morel, ..., Stamatakis (2021)](https://academic.oup.com/mbe/article/38/5/1777/6030946) | "We cannot draw general, nor confident conclusions about the position of the root using the two mathematically highly distinct approaches that we have deployed here." |
| [Pipes, ..., Huelsenback, Nielsen (2021)](https://academic.oup.com/mbe/article/38/4/1537/6028993)  | "These results suggest that phylogenetic evidence alone is unlikely to identify the origin of the SARS-CoV-2 virus and we caution against strong inferences regarding the early spread of the virus based solely on such evidence." |
| [Kumar, ..., Pond, Miura (2021)](https://academic.oup.com/mbe/article/38/8/3046/6257226) | Suggests root of [lineage A + C18060T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C18060T-colormuts). |
| [Bloom (2021)](https://academic.oup.com/mbe/article/38/12/5211/6353034) | Suggests outgroup-based root of either [lineage A + C29095T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colormuts) or [lineage A + C18060T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C18060T-colormuts). |
| [Pekar, Worobey, ..., Wertheim (2021)](https://www.science.org/doi/full/10.1126/science.abf8003) | "Our estimates for the timing of the Hubei index case further distance this individual from the outbreak at the Huanan Seafood Wholesale Market." |
| [Pekar, ..., Suchard, Andersen, Worobey, Wertheim (2022)](https://www.science.org/doi/full/10.1126/science.abp8337) | Uses three approaches: **[1]** Date-based (unconstrained) phylodynamic model suggests a root of [lineage B](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-B-colormuts); **[2]** Outgroup-based (constrained) model suggests root of [lineage A](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-colormuts); **[3]** Epidemic model suggests separate introductions of lineage A and lineage B. |
| [Lv, ..., Zhang (2024)](https://academic.oup.com/ve/article/10/1/veae020/7619252) | Suggests outgroup-based root of [lineage A + C29095T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colormuts); notes other outgroup-based roots also possible. Confirms existence of sequences genetically intermediate between lineage A and lineage B. |
| [Crits-Christoph, ..., Andersen, Worobey, Debarre (2024)](https://www.sciencedirect.com/science/article/pii/S0092867424009012) | Suggests a root of [lineage A](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-colormuts); notes that while that root does not correspond to any Huanan Market patient or environmental sequences, those sequences have lineage A as their MRCA. |
```

# [Outgroup-based rooting could be wrong if there were early reversions](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-B-colormuts)

For both the best outgroup-based roots ([lineage A + C29095T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colormuts) and [lineage A + C18060T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C18060T-colormuts)) to be wrong, early evolution of SARS-CoV-2 in humans must have involved _reversions_, which are mutations that make the sequence more similar to the bat coronavirus ancestors.
If the root was lineage B root (as shown at right) then there would have had to have been _lots_ of early reversions: C8782T, T28144C, C29095T, and C18060T (the last of these not labeled on the default view shown at right).
Rooting on [lineage A](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-colormuts) requires fewer reversions (just C29095T and C18060T).
And even if [lineage A + C29095T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-colormuts) or [lineage A + C18060T](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C18060T-colormuts) was the root, there must have been at least one reversion (either C18060T or C29095T).

Reversions are statistically rare.
The SARS-CoV-2 genome is ~29,000 nucleotides in length so there are ~29,000 x 3 = 87,000 different mutations that can occur.
Only ~380, or 0.4%, of these possible mutations are reversions the recCA ancestor.
So naively it seems unlikely the virus would acquire a reversion in its early evolution, let alone several.
But in fact the odds aren't quite that bad: not all mutations are tolerated, and C-to-T mutations (which represent most of the possible reversions) are the [most common type of mutation](https://academic.oup.com/mbe/article/40/4/msad085/7113660) during SARS-CoV-2 evolution (certain C-to-T mutations are [especially](https://www.biorxiv.org/content/10.1101/2024.02.27.581995v2) [common](https://www.biorxiv.org/content/10.1101/2025.01.07.631013v1)).

So it's possible that SARS-CoV-2 could have acquired reversions in its early evolution in humans--although it gets less and less likely the more reversions we have to assume.

Alternatively...

# [Date-based rooting could be wrong if earliest sequences are biased subset of early cases](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-coloraddtlannotations)

If the earliest available sequences are a biased subset of the actual early cases, then outgroup-based rooting could be correct and the discrepancy with date-based rooting could simply be because the sequences with the earliest dates are not representative of the viruses in Wuhan at that time.

In fact, the earliest sequences are biased:
the 2021 [joint-WHO China report](https://www.who.int/publications/i/item/who-convened-global-study-of-origins-of-sars-cov-2-china-part) (page 43-45) says that there were 174 confirmed cases from December 2019, just a small fraction of which were sequenced.
The report says that just 33% of all December 2019 cases had recent exposure to the Huanan Seafood Market (page 44), but 12 of 13 (92%) of the sequences from patients with symptom onset before Dec-31-2019 were linked to the Huanan Market (page 76), as plotted at right.
Other earlier studies from independent groups (eg, [Huang et al (2020)](https://www.sciencedirect.com/science/article/pii/S0140673620301835), [Li et al (2020)](https://www.nejm.org/doi/10.1056/NEJMoa2001316)) also found an appreciable fraction of the first identified cases did not have exposure to the Huanan Market (as plotted at right)---but most of these non-Huanan Market cases were never sequenced.

The bias of the earliest sequences towards being from the Huanan Market relative to all cases may be because into mid-January of 2020, the Wuhan Health Commission had incorrectly [reported](https://web.archive.org/web/20200111023106/http:/wjw.wuhan.gov.cn/front/web/showDetail/2020011109035) that most patients were linked to the Huanan Market and there was no clear evidence of human-to-human transmission.
This mistaken assumption that all early cases were linked to the Huanan Market may have meant there was less sequencing of pneumonia patients not linked to the Huanan Market.

The 12 of the earliest sequences from the Huanan Market are all lineage B, but the one earliest sequence not from the Huanan Market is lineage A.
Of course, we don't know the sequences from the many unsequenced December 2019 cases from patients who did not visit the Huanan Market, but if some are closer to the bat coronavirus ancestor then that could resolve the discrepancies around outgroup-rooting.

```auspiceMainDisplayMarkdown

# The earliest available SARS-CoV-2 sequences are a biased subset of the actual early cases

### The 2021 joint-WHO China report says most Dec-2019 cases did not have exposure to the Huanan Seafood Market, but most of the earliest available sequences are from patients with exposure to the Huanan Market
![WHO Dec sequence vs case counts](https://raw.githubusercontent.com/jbloom/early-SARS2-trees/refs/heads/master/data/images/WHO_case_vs_sequence_plot.png)
Statistics taken from pages 44 and 76 of the [joint-WHO China report](https://www.who.int/publications/i/item/who-convened-global-study-of-origins-of-sars-cov-2-china-part).

### A Feb-2020 study by doctors from Beijing also found many of the earliest cases did not have exposure to the Huanan Seafood Market
![Figure 1B from [Huang et al (2020)](https://www.sciencedirect.com/science/article/pii/S0140673620301835)](https://raw.githubusercontent.com/jbloom/early-SARS2-trees/refs/heads/master/data/images/Huang2020.png)
Figure 1B from [Huang et al (2020)](https://www.sciencedirect.com/science/article/pii/S0140673620301835).

### A Jan-2020 study by the Chinese CDC, Wuhan CDC, and Hong Kong School of Public Health also found many of the earliest cases did not have exposure to the Huanan Seafood Market
![Figure 1 from [Li et al (2020)](https://www.nejm.org/doi/10.1056/NEJMoa2001316)](https://raw.githubusercontent.com/jbloom/early-SARS2-trees/refs/heads/master/data/images/Li2020.png)
Figure 1 from [Li et al (2020)](https://www.nejm.org/doi/10.1056/NEJMoa2001316).

```

# [Explore the data yourself](https://nextstrain.org/groups/jbloomlab/SARS2-rooting/early-SARS2-trees/crits-christoph2024-Feb-15-2020-lineage-A-C29095T-coloraddtlannotations)

As the foregoing explains, there isn't enough evidence to place the root of the SARS-CoV-2 phylogenetic tree with high confidence.

However, a goal of this narrative is to provide ways to explore the data so you can see the strengths and weaknesses of different hypotheses.

Below are links to interactive Nextstrain trees with the four possible roots discussed above.
You can use the _Color By_ box in the upper left of each tree to color sequences by different annotations, and mouse over specific strains for details.
Although the foregoing narrative discusses outgroup based rooting in terms of the distance from the inferred ancestor recCA, equivalent results are obtained if distances are instead from the bat coronavirus relative RaTG13 (you can also color by this annotation in the interactive trees).

The foregoing narrative uses sequences from samples collected no later than Feb-15-2020 as curated by [Crits-Christoph et al (2024)](https://www.sciencedirect.com/science/article/pii/S0092867424009012), but below are also links to trees showing sequences in the same date range as curated by [Lv et al (2024)](https://academic.oup.com/ve/article/10/1/veae020/7619252) (the results are qualitatively similar both sequence sets).

Links to interactive trees:

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

```auspiceMainDisplayMarkdown

# Methods details

### Data and computer code
The computer code and data used to generate this narrative are at [https://github.com/jbloom/early-SARS2-trees](https://github.com/jbloom/early-SARS2-trees).

### Summary of phylogenetics
SARS-CoV-2 sequence datasets were assembled using the lists of Genbank, NGDC, and GISAID accessions provided by [Crits-Christoph et al (2024)](https://www.sciencedirect.com/science/article/pii/S0092867424009012) or [Lv et al (2024)](https://academic.oup.com/ve/article/10/1/veae020/7619252); see [https://github.com/jbloom/early-SARS2-trees/tree/master/data/crits-christoph2024](https://github.com/jbloom/early-SARS2-trees/tree/master/data/crits-christoph2024) and [https://github.com/jbloom/early-SARS2-trees/tree/master/data/lv2024](https://github.com/jbloom/early-SARS2-trees/tree/master/data/lv2024) for details.

A [snakemake pipeline](https://github.com/jbloom/early-SARS2-trees/blob/master/Snakefile) was then used to assemble all sequences with collection dates no later than Feb-15-2020 (dropping low-quality or incomplete sequences).
The [augur](https://docs.nextstrain.org/projects/augur) pipeline was used to align the sequences and infer a phylogenetic tree using a GTR substitution model, masking sites near the each termini of the genome.
The trees were rooted on representative lineage A, lineage B, lineage A + C29095T, or lineage A + C18060T sequences as indicated.

Annotations were added including the sequence collection date, number of mutations relative to the recombinant common ancestor [recCA](https://www.science.org/doi/10.1126/science.abp8337) or [RaTG13](https://www.ncbi.nlm.nih.gov/nuccore/MN996532), and annotations about whether they were from patients with symptom onset before Dec-31-2019 from the [joint-WHO China report](https://www.who.int/publications/i/item/who-convened-global-study-of-origins-of-sars-cov-2-china-part) or environmental samples from the Huanan Market from [Liu et al (2024)](https://www.nature.com/articles/s41586-023-06043-2).

See [https://github.com/jbloom/early-SARS2-trees](https://github.com/jbloom/early-SARS2-trees) for the full data and pipeline.

### Have a question or suggestion?
If you have a question or suggestion about how to clarify or improve the narrative, analyze a different root, or curate the sequences different please [raise a GitHub issue](https://github.com/jbloom/early-SARS2-trees/issues).

### Acknowledgments
Thanks to the scientists who submitted the analyzed sequences to the Genbank, NGDC, or GISAID databases.
See [https://doi.org/10.55876/gis8.250518yk](https://doi.org/10.55876/gis8.250518yk) for the GISAID acknowledgments.

```
