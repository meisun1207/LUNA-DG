# LUNA-DG

We released the dataset list of LUNA-DG we used in our paper. We traced back the CT scans in LUNA16 to LIDC-IDRI and figured out the meta information. We filtered out one scan that has no meta information. Then, we divided the CT scans into different domains according to their reconstructing convolution kernels. We selected the domains with fewer CT scans as target domains and the other domains were regarded as source domains. We also randomly selected some CT scans from the source domain as the separate source test set to evaluate the models’ performance on the source domain.


Citation
=
If you find this project useful for your research, please use the following BibTeX entry.
> 
@article{yin2022afa,
  title={AFA: adversarial frequency alignment for domain generalized lung nodule detection},
  author={Yin, Baocai and Sun, Mei and Zhang, Jing and Liu, Wenchao and Liu, Cong and Wang, Zengfu},
  journal={Neural Computing and Applications},
  volume={34},
  number={10},
  pages={8039--8050},
  year={2022},
  publisher={Springer}
}

