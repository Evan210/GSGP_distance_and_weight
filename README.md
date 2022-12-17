# To Reviewers:
Sorry!!! We forgot to upload Supplementary Table S7 in the submission system. Please take the table from [here](https://github.com/Evan210/GSGP_distance_and_weight/blob/main/Supplementary%20Table%20S7.xlsx) for now. We have contacted the Journal for help and are waiting for a reply.

# GSGP distance and weight
The codes describing the selection of distances and weights of GSGP.

- **distance_and_weights_TCGA_eQTL.ipynb**

Calculate parameters using TCGA eQTL data. The main parameters used by our paper.

Gene annotations should be obtained from [GENCODE](https://www.gencodegenes.org/human/).

- **distance_and_weights_GTEx.ipynb**

Calculate parameters using GTEx eQTL data.

GTEx v8 eQTL data should be downloaded from [here](https://storage.googleapis.com/gtex_analysis_v8/single_tissue_qtl_data/GTEx_Analysis_v8_eQTL.tar).

Gene annotations should be obtained from [here](https://storage.googleapis.com/gtex_analysis_v8/reference/gencode.v26.GRCh38.genes.gtf).

- **distance_and_weights_TCGA_BRCA.ipynb**

Calculate parameters using TCGA BRCA eQTL data provided by previous [research](https://doi.org/10.1016/j.cell.2012.12.034).

eQTLs are contained in the supplementary table 2 and 3 of [this](https://doi.org/10.1016/j.cell.2012.12.034) paper.

Gene annotations should be obtained from [here](https://api.gdc.cancer.gov/data/25aa497c-e615-4cb7-8751-71f744f9691f).

The GRCh38 positions of rsIDs could be download from [here](https://ftp.ncbi.nlm.nih.gov/snp/organisms/human_9606_b151_GRCh38p7/VCF/All_20180418.vcf.gz).

As the file is really huge, you can just use [this](https://github.com/Evan210/GSGP_distance_and_weight/raw/main/rsID.txt.gz) small file that only contains the involved rsIDs.
