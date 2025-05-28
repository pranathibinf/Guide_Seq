# Guide_Seq

GUIDE-seq Analysis: On-Target and Off-Target Effects on LRRK2 Gene

##  Project Goal

The objective of this project is to evaluate the specificity of a CRISPR guide RNA targeting the LRRK2 gene (chr12:40,196,744–40,369,285) by analyzing GUIDE-seq data. We focus on: Confirming cleavage at the intended on-target site, Identifying and visualizing off-target effects within the LRRK2 region and across the genome

### Data Sources

Dataset: https://zenodo.org/records/10800918 ; 

#### Methods & Tools

a) Language: Python 3 (b) Libraries: pandas, matplotlib (c) Analysis steps: (1)Load and inspect GUIDE-seq peak data (2) Visualize on-target and off-target events within the LRRK2 region (3) Plot global distribution of read counts to evaluate genome-wide specificity

##### Results
I. Files: 1) lrrk2_on_target.csv: Contains on-target GUIDE-seq peak (chr12:40248639–40248771)  (2) lrrk2_off_targets.csv: Contains GUIDE-seq peaks in the LRRK2 region excluding the on-target  (3) offtarget_peaks_test.csv: Genome-wide GUIDE-seq peaks (potential off-targets) 

II. Output: LRRK2 region plot with on-target overlay; Histogram of read counts for genome-wide peaks; Summary statistics and top off-targets (available on request)

###### Results summary

1) One strong on-target peak identified at chr12:40248639–40248771 with 8 reads (2) Only 23 off-target peaks were found within the broader LRRK2 region, all with low read counts (1–6) (3) Genome-wide analysis revealed most off-target peaks had only 2–4 reads, indicating low-intensity or background events.

Interpretation:
These results indicate that the CRISPR guide RNA exhibits high specificity for the LRRK2 gene with minimal off-target activity, making it suitable for downstream therapeutic or research applications.
