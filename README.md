# wfspm-dataset
This repository contains the datasets used in the paper "Weighted sequential pattern mining". Items in these datasets have associated weights added synthetically following different probability distribution.




We have chosen four real datasets and one synthetic dataset from SPMF Open-Source Data Mining Library. We have also used another large dense synthetic dataset that we have prepared using the SPMF Data Generator.

(a) SIGN: A dataset of sign language utterances.
(b) LEVIATHAN: A conversion of the novel Leviathan by Thomas Hobbes (1651) as a sequence database (each word is an item).
(c) FIFA: Click-stream data from the website of FIFA World Cup 98.
(d) Kosarak: Click-stream data from a Hungarian news portal.
(e) synthetic: A synthetic dataset, generated using IBM Quest Dataset Generator.
(f) T1000KU500: A synthetic dataset, generated SPMF sequence database generator.

Each of these datasets has a correspond weight file in the repository. "synthetic" dataset has two weight files: one for negatively skewed and another for positively skewed weight distribution.


If you use any of these datasets with the weight-values, we humbly request to cite us

@article{islam2021weighted,
  title={Weighted frequent sequential pattern mining},
  author={Islam, Md Ashraful and Rafi, Mahfuzur Rahman and Azad, Al-amin and Ovi, Jesan Ahammed},
  journal={Applied Intelligence},
  pages={1--28},
  year={2021},
  publisher={Springer}
}
