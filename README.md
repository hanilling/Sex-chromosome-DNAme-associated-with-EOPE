# X and Y DNA methylation associated with early onset preeclampsia
This respository contains code from the paper **Sex-linked placental DNA methylation associated with early-onset preeclampsia** (Biology of Sex Differences, 2026). It was the first study to investigate and identify an association between early-onset preeclampsia (EOPE) and X and Y chromosome placental DNA methylation. 

<img width="1394" height="779" alt="Slide 1" src="https://github.com/user-attachments/assets/457ad6f2-90e5-494a-8f82-a5a89be69a9a" />

We used DNA methylation data from 843 placentas (XX=386, XY=457) in publicly available datasets. 

The function to calculate **eoPRED score** is available in the [PlaNET R package](https://doi.org/doi:10.18129/B9.bioc.pla)

### Code Files:
- **01_SexEOPE_450K_Proc** - probe filtering, normalization, probe filtering, removing poor quality samples for the 450K dataset
- **02_SexEOPE_SPAH_Proc** - probe filtering, normalization, probe filtering, removing poor quality samples for the SPAH dataset
- **03_SexEOPE_PCA_and_Demographics** - PCA and demographics (Table 2) for both datasets
- **04_SexEOPE_450K_EWAS** - linear modelling DNAme~EOPE and DNAme~eoPRED for the sex chromosomes in the 450K dataset (Figures 1 & 2)
- **05_SexEOPE_SPAH_EWAS** - linear modelling DNAme~eoPRED score for the sex chromosomes in the SPAH dataset (Figure 3)
- **06_SexEOPE_Cohort_Comparison** - comparing the linear modelling results between datasets (Table 4)
