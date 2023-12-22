# Adsorption Energy from Open Catalyst Project OC22 Dataset

This repository includes an example code to obtain the adsorption energies from the dataset [OC22](https://github.com/Open-Catalyst-Project/ocp/blob/main/DATASET.md#open-catalyst-2022-oc22). OC22 basically includes total energies and forces of the slabs with/without adsorbates, of the relaxed structure and of the structures at each relaxation step.

To be able to calculate, adosrption energy of a specific adsorbate on a material. we need to have the energies of the slab+adsorbate, the slab and the adsorbate (or sometimes called gas). This code shows how to get the energies of the slab+adsorbate and the slab from both mapping file and trajectory files, while the energies of the adsorbates are calculated by linear combination of each adsorbate in atomic form.

References:
[1] [OCP Github Page]()
[2] [R. Tran, et.al (2023) *ACS Catalysis*, 13(5), 3066-3084.](https://pubs.acs.org/doi/10.1021/acscatal.2c05426)
