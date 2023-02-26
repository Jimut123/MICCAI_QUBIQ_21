# Holistic network for quantifying uncertainties in medical images
***
## Work presented at the [MICCAI BrainLes 2021 workshop](https://www.brainlesion-workshop.org/).
***

[Pal, J.B. (2022). Holistic Network for Quantifying Uncertainties in Medical Images. In: Crimi, A., Bakas, S. (eds) Brainlesion: Glioma, Multiple Sclerosis, Stroke and Traumatic Brain Injuries. BrainLes 2021. Lecture Notes in Computer Science, vol 12963. Springer, Cham. https://doi.org/10.1007/978-3-031-09002-8_49](https://link.springer.com/chapter/10.1007/978-3-031-09002-8_49)

#### [[Poster](https://jimut123.github.io/publications/MICCAI_QUBIQ_21/Jimut_Bahan_Pal_QUBIQ_MICCAI.pdf)] | [[Presentation](https://www.youtube.com/watch?v=AaVvNG-ihMU)] | [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-09002-8_49)]

## Abstract

Variability in delineation is an inherent property for segmenting medical imagery, when images are annotated by a variety of expert annotators. Previous methods have used adversarial training, Monte-Carlo sampling, and dropouts, which might sometimes produce a wide range of segmentation masks that differ from the styles of mask produced by a set of expert annotators. State-of-the-art method uses multiple U-Nets to capture the individual delineations, but it is computationally demanding. To mitigate this problem, a holistic network containing N-Encoder and N-Decoder is proposed, which could individually model the variability of delineation produced by the expert annotators. This will help to create segmentation masks for different tasks of the same dataset through a single network by learning the common features of multiple Encoders via a common channel and passing those features to Decoder. These create one segmentation mask. All the masks are calculated by using weighted loss at each end of the Decoders that show excellent results for some datasets. 


#### Download the related materials from here:
https://figshare.com/articles/dataset/CXR_Challenge_QUBIQ_21_COVID19_Perc_Estimation/21225287


## Some relevant stuffs from paper

<center>
  <img src="https://github.com/Jimut123/MICCAI_QUBIQ_21/raw/main/assets/holistic_network.png">
  <img src="https://github.com/Jimut123/MICCAI_QUBIQ_21/raw/main/assets/enc_dec.png">
  <img src="https://github.com/Jimut123/MICCAI_QUBIQ_21/raw/main/assets/results_table.png">
</center>

## Acknowledgements

The author acknowledges the MICCAI-QUBIQ-2021 team to organize such a wonderful challenge by making the novel datasets available and also the reviewers for their critical discussions. Finally, the author thanks his mentors, Tamal Maharaj, Swathy Prabhu Mj, Dripta Mj and his father Dr. Jadab Kumar Pal for their suggestions.

## If you find this work useful, please consider citing our paper

```
@InProceedings{10.1007/978-3-031-09002-8_49,
author="Pal, Jimut Bahan",
editor="Crimi, Alessandro and Bakas, Spyridon",
title="Holistic Network for Quantifying Uncertainties in Medical Images",
booktitle="Brainlesion: Glioma, Multiple Sclerosis, Stroke and Traumatic Brain Injuries",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="560--569"
isbn="978-3-031-09002-8"
}

Or

@inproceedings{DBLP:conf/brainles-ws/Pal21,
  author    = {Jimut Bahan Pal},
  editor    = {Alessandro Crimi and
               Spyridon Bakas},
  title     = {Holistic Network for Quantifying Uncertainties in Medical Images},
  booktitle = {Brainlesion: Glioma, Multiple Sclerosis, Stroke and Traumatic Brain
               Injuries - 7th International Workshop, BrainLes 2021, Held in Conjunction
               with {MICCAI} 2021, Virtual Event, September 27, 2021, Revised Selected
               Papers, Part {II}},
  series    = {Lecture Notes in Computer Science},
  volume    = {12963},
  pages     = {560--569},
  publisher = {Springer},
  year      = {2021},
  url       = {https://doi.org/10.1007/978-3-031-09002-8\_49},
  doi       = {10.1007/978-3-031-09002-8\_49},
  timestamp = {Thu, 28 Jul 2022 13:13:16 +0200},
  biburl    = {https://dblp.org/rec/conf/brainles-ws/Pal21.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}


```
