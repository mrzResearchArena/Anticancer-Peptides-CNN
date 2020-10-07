# Multi-headed Deep-Convolutional Neural Network to Accurately Predict Anticancer peptides

&nbsp;

#### Abstract:
Although advancing the therapeutic alternatives for treating deadly cancers has gained much attention
globally, still the primary methods such as chemotherapy have significant downsides and low specificity.
Most recently, Anticancer peptides (ACPs) have emerged as a potential alternative to therapeutic
alternatives with much fewer negative side-effects. However, the identification of ACPs through wet-lab
experiments is expensive and time-consuming. Hence, computational methods have emerged as viable
alternatives. During the past few years, several computational ACP identification techniques using hand-
engineered features have been proposed to solve this problem. In this study, we propose a new multi headed
deep convolutional neural network model called ACP-MHCNN, for extracting and combining
discriminative features from different information sources in an interactive way. Our model extracts
sequence, physicochemical, and evolutionary based features for ACP identification using different
numerical peptide representations while restraining parameter overhead. It is evident through rigorous
experiments using cross-validation and independent-dataset that ACP-MHCNN outperforms other models
for anticancer peptide identification by a substantial margin. ACP-MHCNN outperforms state-of-the-art
model by 6.3%, 8.6%, 3.7%, 4.0%, and 0.20 in terms of accuracy, sensitivity, specificity, precision, and
MCC respectively.

&nbsp;

#### A. Model Architecture:
<!-- ![Model-Image](https://github.com/mrzResearchArena/ACP/blob/master/CNN-model.png "Multi-headed Deep-CNN") -->
<img src="https://github.com/mrzResearchArena/ACP/blob/master/CNN-model.png" class="center" title="Multi-headed Deep-CNN" width="650" height="450" />

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
