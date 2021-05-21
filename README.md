# wfspm-dataset
This repository contains the datasets used in the paper "Weighted sequential pattern mining". Items in these datasets have associated weights added synthetically following different probability distribution.

We have chosen four real datasets and one synthetic dataset from SPMF Open-Source Data Mining Library. We have also used another large dense synthetic dataset that we have prepared using the SPMF Data Generator.

(a) SIGN: A dataset of sign language utterances. <br>
(b) LEVIATHAN: A conversion of the novel Leviathan by Thomas Hobbes (1651) as a sequence database (each word is an item). <br>
(c) FIFA: Click-stream data from the website of FIFA World Cup 98. <br>
(d) Kosarak: Click-stream data from a Hungarian news portal. <br>
(e) synthetic: A synthetic dataset, generated using IBM Quest Dataset Generator. <br>
(f) T1000KU500: A synthetic dataset, generated SPMF sequence database generator. <br>

Dataset T1000KU500 is not added in this repository. You can download this dataset from this <a href="https://drive.google.com/file/d/1kL4bFSlQoLqEhImUar8jMdVNAdjCHVOP/view?usp=sharing">link</a><br>

Each of these datasets has a correspond weight file in the repository. "synthetic" dataset has two weight files: one for negatively skewed and another for positively skewed weight distribution.


If you use any of these datasets with the weight-values, we humbly request to cite us

@article{islam2021weighted,<br>
  title={Weighted frequent sequential pattern mining},<br>
  author={Islam, Md Ashraful and Rafi, Mahfuzur Rahman and Azad, Al-amin and Ovi, Jesan Ahammed},<br>
  journal={Applied Intelligence},<br>
  pages={1--28},<br>
  year={2021},<br>
  publisher={Springer}<br>
}
