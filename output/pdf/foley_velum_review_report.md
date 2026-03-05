# Peer Review Report

## Manuscript
**Title:** The development of velum coordination in children: a real-time MRI study  
**Author:** Sean Foley  
**Date on manuscript:** February 15, 2026

## 1) Study Summary
This manuscript presents an rtMRI study of velum-tongue tip (TT) coordination in American English-speaking children (reported final sample: 7 female speakers, ages 5-15). The main questions concern developmental patterns in (i) velum-TT timing, (ii) velum magnitude, (iii) velum duration, and (iv) timing stability. Stimuli contrast onset, coda, and juncture-geminate nasal contexts in labial/alveolar frames. The key claim is that the two oldest speakers (age 15) pattern like adults (onset near-synchrony; coda/geminate earlier velum lowering), while younger speakers largely show uniformly early velum lowering across conditions. The paper further argues that velum target-to-TT onset lag is more stable than onset lag and may therefore be the more relevant timing relation.

## 2) Major Issues (Priority)

1. **Inference is stronger than design supports (very small, non-independent sample).**  
   The developmental interpretation is based on seven speakers (with sibling pairs), all female, with clear clustering by age but sparse coverage. The sharp "stage shift" claim (5-14 vs 15) is plausible but not well identified statistically with this sample structure. At minimum, claims should be reframed as preliminary and exploratory.

2. **Statistical independence and pseudoreplication concerns are not fully addressed.**  
   Many token-level observations are modeled, but speaker-level N is very small. This risks overconfident inference from repeated measures when between-speaker evidence is limited. The manuscript should explicitly separate within-speaker effects from speaker-level developmental generalizations.

3. **"Stability" is inferred from non-significance in correlation tests.**  
   The argument "no significant correlation => stability" is not sufficient, especially with small per-speaker sample sizes and varying power. A better analysis would use equivalence testing, confidence-interval bounds, or explicit variance-based stability metrics.

4. **Multiple testing strategy is under-specified.**  
   Many within-speaker pairwise Wilcoxon comparisons are reported, but there is no clear correction strategy across the family of tests (and figures use significance stars). This can inflate false positives.

5. **Methodological reporting has reproducibility gaps.**  
   Key details are missing or incomplete: number of usable tokens per condition after exclusions, exclusion criteria at token level, inter-rater/retest reliability for manual alignment corrections and landmark verification, and exact preprocessing/quality-control workflow for ROI tracking.

6. **Several placeholders/incomplete statements remain in the draft.**  
   Examples include unresolved citations `(?)`, `(??)`, and incomplete numeric statements (e.g., variance explained by PC1 listed as `%` with missing values). These currently prevent full scientific evaluation.

## 3) Introduction / Literature Review

1. **Narrative is generally strong but contains unresolved citation gaps.**  
   There are multiple placeholder citations in core argumentation (including developmental coarticulation and timing claims). These need to be resolved before review can evaluate evidential support.

2. **Some redundancy could be reduced.**  
   The manuscript repeats similar framing points about under-studied timing and novelty in multiple places. Condensing repeated background paragraphs would improve clarity and focus.

3. **Foundational theoretical framing could be expanded.**  
   Given the gestural-coordination claims, the introduction should anchor more directly in foundational articulatory-phonology and dynamical timing references (see recommended references below).

## 4) Methods

1. **Participant description and dependency structure need clearer handling.**  
   Sibling pairs are included, and one participant is excluded. The manuscript should report exactly how family structure is handled in modeling (or why it is negligible).

2. **Potential inconsistency in speaker IDs.**  
   The text mentions `Spk7` in ROI description, but participant table lists `Spk5, Spk8, Spk11a, Spk11b, Spk14, Spk15a, Spk15b`. This inconsistency needs correction.

3. **ROI and landmark pipeline needs reproducibility metrics.**  
   Provide quantitative reliability checks: repeated ROI placement, intra-/inter-annotator consistency for alignment correction and gestural landmarks, and error statistics.

4. **Control variables are limited for timing interpretation.**  
   Speech rate and prosodic variation are likely to affect timing/duration outcomes but are not clearly controlled in primary models.

5. **Only low-vowel context is used.**  
   The manuscript acknowledges this limitation, but because intrinsic vowel nasalization can affect velum behavior, this confound should be more central in interpretation.

## 5) Results

1. **Result patterns are interesting, but inferential framing should be softened.**  
   The age-linked patterns are suggestive, not definitive, with this sample.

2. **Model reporting should include diagnostics and uncertainty emphasis.**  
   Include assumptions checks, random-effect structure justification, potential convergence/singularity notes, and effect-size interpretation beyond p-values.

3. **Per-speaker analyses need sample-size transparency.**  
   Report per-speaker per-condition token counts after all exclusions for every key figure and regression.

## 6) Discussion / Conclusions

1. **Some mechanistic claims are overextended.**  
   Claims that target-onset timing is encoded in cognitive representations are plausible but should be presented as hypotheses consistent with data, not conclusions directly established by the current design.

2. **Alternative explanations deserve fuller treatment.**  
   In addition to developmental control and inhibition accounts, discuss scanner-task effects, speech-rate/prosodic differences, and lexical/item effects as competing contributors.

3. **Conclusion should better match evidential strength.**  
   Recommend reframing as evidence for a *candidate developmental pattern* requiring replication in larger, more diverse samples.

## 7) Clarity and Presentation Issues

1. Resolve all placeholder citations and figure cross-references.  
2. Fix typographical/formatting artifacts (e.g., special-character rendering issues) in extracted equations and text.  
3. Correct grammar and consistency issues (e.g., "this facts", "predicated" for "predicted", etc.).

## 8) References Likely Missing but Important

The following references are strong candidates to include because they ground core claims about gestural coordination and dynamical timing:

1. Browman, C. P., & Goldstein, L. (1986). *Towards an articulatory phonology.*
2. Browman, C. P., & Goldstein, L. (1992). *Articulatory phonology: An overview.*
3. Saltzman, E., & Munhall, K. (1989). *A dynamical approach to gestural patterning in speech production.*

Optional additional candidates (depending on final framing):

4. Additional foundational work on coordinative structures and temporal control in speech motor behavior if the manuscript continues to emphasize stability as a control objective.

## 9) Overall Recommendation
**Major revision.** The topic is strong, the rtMRI dataset is valuable, and the paper has clear potential. But the current draft needs (i) complete citation/reporting cleanup, (ii) tighter inferential claims matched to sample size, and (iii) stronger statistical/reproducibility reporting before it is ready for publication.
