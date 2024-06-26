Data analysis and supervised learning techniques applied to Clifford invariants of Coxeter elements.

The folder `InvariantData` contains zip files for each Clifford algebra (A8,D8,E8) listing the permutation of the Coxeter element and the respective 9 invariants. The folder also contains the script `ADE8_InvariantGeneration.py` which generated this data (runs with multiprocessing, used on a hpc).     
   
The `ADE8_classification.ipynb` notebook illustrates the application of supervised learning to classification Geometric invariants of A8, D8 and E8 algebras.    
   
The `ADE8_frequencies.ipynb` notebook contains the analysis of the A8, D8 and E8 algebras' invariants' components. We found the number of unique invariants (classes) and the number of occurrences of invariants from each of the classes (frequencies).    
   
The `ADE8_subinvariant_frequencies.ipynb` contains the analysis of the A8, D8 and E8 algebras' subinvariants' components: scalar, bivector, quadrivaector, sextuvector and pseudoscalar parts. We found the number of unique subinvariants (classes) and the number of occurrences of subinvariants from each of the classes (frequencies).    

The `ADE8_doublets_quadruplets.ipynb` notebook contains an analysis of frequencies, focusing particularly on the symmetries observed among classes sharing identical frequencies.

The `ADE8_FAke_data_for_classification.ipynb` notebook generates the fake data for A8/D8/E8 datasets based on the frequency distributions of the components of SOCMs

The `BivectorAnalysis.py` script extracts the bivector subinvariants from the datasets, interprets them as graphs, and runs the respective frequency and eigenspectrum analysis.  

The `PCA.py` script performs the principal component analysis (PCA) on the invariant datasets and plots scatter plots of the first two components.
    
# BibTeX Citation
``` 
@article{Chen:2023whk,
    author = "Chen, Siqi and Dechant, Pierre-Philippe and He, Yang-Hui and Heyes, Elli and Hirst, Edward and Riabchenko, Dmitrii",
    title = "{Machine Learning Clifford Invariants of ADE Coxeter Elements}",
    eprint = "2310.00041",
    archivePrefix = "arXiv",
    primaryClass = "cs.LG",
    reportNumber = "QMUL-PH-23-15",
    doi = "10.1007/s00006-024-01325-y",
    journal = "Adv. Appl. Clifford Algebras",
    volume = "34",
    number = "3",
    pages = "20",
    year = "2024"
}
```
