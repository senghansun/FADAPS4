# FADAPS4

### Fine-grained Adversarial Domain Adaptation with Pseudo-probability Smoothing and Sample Selection Strategy

This repository contains all the project codes and revision history for the FADAPS4.

FADAPS4 is a new adversarial-based Unsupervised Domain Adaptation (UDA) method that refines the existing fine-grained adversarial domain adaptation (FADA) proposed by Wang et al. in https://link.springer.com/chapter/10.1007/978-3-030-58568-6_38

There are 2 new components introduced in FADAPS4, namely:
1. Sample Selection Strategy using the Destroyed Your Object (DeYO) method as proposed by Lee et al. in https://arxiv.org/abs/2403.07366
2. Pseudo-probability Smoothing by incorporating a moving average formula as introduced by Yi et al. in https://arxiv.org/abs/2301.13381


*RELATED ARTICLE*

For more detail information related to the proposed method and previous studies done by the contributors, please refers to following publications:
1. Hansun, S., Argha, A., Liaw, S.-T., Celler, B. G. & Marks, G. B. Machine and Deep Learning for Tuberculosis Detection on Chest X-Rays: Systematic Literature Review. J. Med. Internet Res. 25, e43154 (2023).
2. Hansun, S. et al. Revisiting Transfer Learning Method for Tuberculosis Diagnosis. in 2023 45th Annual International Conference of the IEEE Engineering in Medicine & Biology Society (EMBC) 1–4 (IEEE, 2023). doi:10.1109/EMBC40787.2023.10340441.
3. Hansun, S. et al. Pulmonary Tuberculosis Detection Using an Ensemble of ConvNeXts. in 2024 5th International Conference on Biomedical Engineering (IBIOMED) 29–33 (IEEE, 2024). doi:10.1109/iBioMed62485.2024.10875706.
4. Hansun, S. et al. A New Ensemble Transfer Learning Approach with Rejection Mechanism for Tuberculosis Disease Detection. IEEE Trans. Radiat. Plasma Med. Sci. 1–1 (2024) doi:10.1109/TRPMS.2024.3474708.
5. Hansun, S. et al. Diagnostic Performance of Artificial Intelligence–Based Methods for Tuberculosis Detection: Systematic Review. J. Med. Internet Res. 27, e69068 (2025).


*DATA SOURCE*

The main data source is taken from public Tuberculosis datasets, including:
* Montgomery County (MC) and Shenzhen (SZ) from https://openi.nlm.nih.gov/faq?download=true
* India (DA/DB) from https://sourceforge.net/projects/tbxpredict/files/data/
* TBX11K from https://datasetninja.com/tbx-11k

*ACKNOWLEDGMENTS*

We would like to acknowledge the contribution of many parties, especially for the public data sources and previous studies as mentioned above.

*CONTACT US*

We welcome any comments, suggestions, and questions which can be addressed to the email provided below.
Email: s.hansun@unsw.edu.au

*TERMS OF USE*

For publications that use the codes and associated data provided in this repository, please cite: "Hansun, S. FADAPS4: Fine-grained Adversarial Domain Adaptation with Pseudo-probability Smoothing and Sample Selection Strategy. https://github.com/senghansun/FADAPS4"
