# Multi-headed Deep-Convolutional Neural Network to Accurately Predict Anticancer peptides

&nbsp;

#### Abstract:
We will complete it after the paper writing.

&nbsp;

#### A. Model Architecture:
<!-- ![Model-Image](https://github.com/mrzResearchArena/ACP/blob/master/CNN-model.png "Multi-headed Deep-CNN") -->
<img src="https://github.com/mrzResearchArena/ACP/blob/master/CNN-model.png" class="center" title="Multi-headed Deep-CNN" width="700" height="400" />

&nbsp;

#### B. Datasets:
We used three anticancer peptide dataset for our experiment. The datasets are ACP-740 [1], ACP-240 [1], and ACP-500/164 [2].
The raw dataset are FASTA sequences; the raw datasets are available on [repository](https://github.com/mrzResearchArena/Anticancer-Peptides-CNN/tree/master/Datasets-FASTA) in FASTA format. Afterward, we extract feature using (A) Binary Profile Feature (BPF) Encoding, (B) Physiochemical Property based Encoding, and (C) Evolutionary Information based Encoding. The extracted datasets are also available on [repository](https://github.com/mrzResearchArena/Anticancer-Peptides-CNN/tree/master/Datasets-NumPy) in NumPy format.

&nbsp;

#### C. Implementation:
1. Implementation for the [ACP-740](https://github.com/mrzResearchArena/Anticancer-Peptides-CNN/blob/master/Codes/ACP-740-ROC.ipynb) dataset.
2. Implementation for the [ACP-240](https://github.com/mrzResearchArena/Anticancer-Peptides-CNN/blob/master/Codes/ACP-240-ROC.ipynb) dataset.
3. Implementation for the [ACP-500/164](https://github.com/mrzResearchArena/Anticancer-Peptides-CNN/blob/master/Codes/ACP-500-164-ROC.ipynb) dataset.

&nbsp;

#### D. Model Architecture:
You can find the model architectures from the given [link](https://github.com/mrzResearchArena/Anticancer-Peptides-CNN/tree/master/Model-Architecture).

&nbsp;

#### E. ROC Curve:
You can find the ROC curves from the given [link](https://github.com/mrzResearchArena/Anticancer-Peptides-CNN/tree/master/ROC-Curve).

&nbsp;

#### References:
[1]. https://doi.org/10.1016/j.omtn.2019.04.025

[2]. https://doi.org/10.1093/bioinformatics/bty451
