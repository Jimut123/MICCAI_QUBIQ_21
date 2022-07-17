# Holistic network for quantifying uncertainties in medical images
***
## Work presented at the [MICCAI BrainLes 2021 workshop](https://www.brainlesion-workshop.org/).
***
#### [[Poster](https://jimut123.github.io/publications/MICCAI_QUBIQ_21/Jimut_Bahan_Pal_QUBIQ_MICCAI.pdf)] | [[Presentation](https://www.youtube.com/watch?v=AaVvNG-ihMU)]

## Abstract

Variability in delineation is an inherent property for segmenting medical imagery, when images are annotated by a variety of expert annotators. Previous methods have used adversarial training, Monte-Carlo sampling, and dropouts, which might sometimes produce a wide range of segmentation masks that differ from the styles of mask produced by a set of expert annotators. State-of-the-art method uses multiple U-Nets to capture the individual delineations, but it is computationally demanding. To mitigate this problem, a holistic network containing N-Encoder and N-Decoder is proposed, which could individually model the variability of delineation produced by the expert annotators. This will help to create segmentation masks for different tasks of the same dataset through a single network by learning the common features of multiple Encoders via a common channel and passing those features to Decoder. These create one segmentation mask. All the masks are calculated by using weighted loss at each end of the Decoders that show excellent results for some datasets. 





## Some relevant stuffs from paper

<center>
  <img src="https://github.com/Jimut123/MICCAI_QUBIQ_21/raw/main/assets/holistic_network.png">
  <img src="https://github.com/Jimut123/MICCAI_QUBIQ_21/raw/main/assets/enc_dec.png">
  <img src="https://github.com/Jimut123/MICCAI_QUBIQ_21/raw/main/assets/results_table.png">
</center>



## If you find this work useful, please consider citing our paper

```
@InProceedings{10.1007/978-3-031-09002-8_49,
author="Pal, Jimut Bahan",
editor="Crimi, Alessandro
and Bakas, Spyridon",
title="Holistic Network for Quantifying Uncertainties in Medical Images",
booktitle="Brainlesion: Glioma, Multiple Sclerosis, Stroke and Traumatic Brain Injuries",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="560--569"
}

```
