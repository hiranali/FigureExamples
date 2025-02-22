## **Figure One Lab** (**F1L**)

Replicating Figure 1 of modern biology papers. 

### **What is in F1L?**

F1L contains a curated set of questions, data, and methods that you can use to build a strong compbio project:
1. **Questions** presented in the form of papers are sourced from the fields of cancer biology, immunology, neuroscience, stem cell biology. Figure 1 of these papers serve as our starting point. These papers address topics of broad scientific appeal to both academia and industry so you are working on problems that people actually care about.
   - [Kinker_2020_NatureGenetics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8135089/) is study of biological programs in commonly used cancer cell lines.
   - [Schmidt_2022_Science](https://www.science.org/doi/10.1126/science.abj4008) is a study of CRISPR-edited human T cells.
   - [Trevino_2021_Cell](https://www.sciencedirect.com/science/article/pii/S0092867421009429) is a study of human cortex development.
   - [Uzquiano_2022_Cell](https://www.sciencedirect.com/science/article/pii/S0092867422011680) is a study of human cortical organoids.
2. **Data** accompanying these papers are open (not behind a paywall or in a restricted database), from human tissue, and multiomic. Emphasizing single-cell RNA-sequencing (scRNA-seq) data at first because it is a rich data modality ubiquitous in every field of biology and a good gateway data modality that can be integrated with many other types of data.
3. **Methods** are well-documented Python packages. F1L does not emphasize method development because there are already plenty of powerful, popular methods that you can use to put together a brilliant compbio project. No need to reinvent the wheel.


The notebooks only recreate a part of Figure 1.

A simple directory structure that you might use to organize your work:

<img width="325" alt="Screen Shot 2024-01-01 at 5 42 52 PM" src="https://github.com/deanslee/FigureOneLab/assets/35471368/43a129e4-fa33-469a-9206-f07d9854f071">

- FigureOneLab/trevino/data/ holds all the "raw" files, PDFs, code provided by authors, Excel spreadsheets, etc., from the paper needed to re-enact Figure 1.

- FigureOneLab/trevino/outs/ holds all the intermediate and final outputs of analysis.

- FigureOneLab/trevino/filename1.ipynb is first analysis.

- FigureOneLab/trevino/filename2.ipynb is second analysis. etc.

### **A Concise List of Helpful Resources/References**
- [3Blue1Brown](https://www.youtube.com/c/3blue1brown) for linear algebra
- [Points of Significance](https://www.nature.com/collections/qghhqm/pointsofsignificance) for statistics
- [StatQuest!!!](https://statquest.org/) for statistics
- [STAT115 by Shirley Liu](https://www.youtube.com/playlist?list=PLeB-Dlq-v6tY3QLdQBA7rwb4a7fK9mLpv) for an introduction to compbio
- [Best practices for scRNA-seq data analysis](https://www.sc-best-practices.org/preamble.html) the best resource of its kind so far
- [Glittr](https://glittr.org/?per_page=25&sort_by=stargazers&sort_direction=desc) a collection of Git repos with bioinformatics training material
