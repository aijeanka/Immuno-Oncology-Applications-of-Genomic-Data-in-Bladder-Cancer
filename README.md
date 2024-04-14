# Immuno-Oncology Applications of Genomic Data in Bladder Cancer

## Project Overview
The final project for HIDS-7003-1 2023 involves a comprehensive analysis of gene expression data to explore potential immuno-oncology applications in bladder cancer. The project consists of several steps, culminating in a systems biology analysis of differentially expressed genes (DEGs) and a subsequent CIBERSORT analysis to examine the tumor microenvironment's immune cell composition.

## Objectives
- To perform an EnrichR analysis on DEGs to understand the molecular changes and biological processes in bladder cancer stages compared to normal tissue.
- To use CIBERSORT to infer the immune cell composition within bladder cancer and normal tissue and relate these findings to the pathways identified from gene expression data.

## Step 2: EnrichR Analysis
- Conducted a systems biology analysis of DEGs using EnrichR.
- Output includes enriched pathways and biological processes relevant to different cancer stages.

## Step 4: Final Analysis Using CIBERSORT Data
- Examined the immune cell composition within bladder cancer tissues and normal tissues using CIBERSORT.
- Compared the results from CIBERSORT with pathways identified in the EnrichR analysis to draw correlations between gene expression changes and immune infiltration patterns.

## Repository Contents
- `Aizhan_Team1-Step1.Rmd`: R Markdown file with the code for the initial t-test analysis to identify DEGs.
- `Aizhan-Team1-Step2.Rmd`: R Markdown file with the EnrichR analysis code.
- `Aizhan-Team1-Step2-EnrichR-summary.pdf`: Summary of the EnrichR analysis.
- `Aizhan_Step3.Rmd`: R Markdown file for further data analysis and comparison.
- `Team1-Step4-FinalAnalysis.docx`: Document describing the comparative analysis of pathways and CIBERSORT results.
- Graphical outputs: Bar and line graphs showing immune cell compositions from CIBERSORT analysis.

## File Descriptions
- `Aizhan_Bladder_TTest.csv`: The output of the initial t-test analysis, listing DEGs.
- `Aizhan_Step3.Rmd`: R Markdown file for further analysis, including comparison of datasets or additional biological interpretations.
- `Aizhan-Team1-Phase1-Ttest-summary.pdf`: A summary of the initial t-test analysis.
- `01-CibersortAverageBarGraph.pdf`: A bar graph showing the average fraction of various immune cells in bladder cancer tumors.
- `03-CibersortLineGraph.pdf`: A line graph visualizing changes in immune cell fractions between adjacent normal and tumor tissues.
- `2023_Ciber_BLCANormal_AvgBarPlot.pdf`: A bar graph of the average fraction of immune cells in normal bladder tissue samples.
- `2023_Ciber_BLCATumor_AvgBarPlot.pdf`: A bar graph of the average fraction of immune cells in bladder tumor samples.
- `2BLCA_Ciber_LinePlot.pdf`: Another line graph representation similar to `03-CibersortLineGraph.pdf`.

## How to Use This Repository
- Review the summary documents for an overview of each analysis phase.
- For a deep dive into the analysis steps, refer to the R Markdown files and their associated output graphs.
- Each graphical output can be used to interpret the immune landscape of bladder cancer.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Authors
- Aizhan Uteubayeva
- Team 1: Joan, Adi, Aizhan, Gazie

## Notes
- This project was conducted collaboratively by Team 1, with equal contributions expected from all members.
- The repository documents the process and findings from each step, highlighting the potential of genomics in immuno-oncology applications.
