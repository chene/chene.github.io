---
title: "A global optimization method for specular highlight removal from a single image"
collection: publications
permalink: /publication/2019-09-03-IEEE-Access_XCP+2019
excerpt: 'In this paper, we proposed a global optimization method for specular highlight removal from a single image based on a dichromatic reflection model.'
date: 2019-09-03
venue: 'IEEE Access'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/8822996'
citation: 'W. Xia et al., (2019). "Multi-view 3D echocardiography volume compounding for mitral valve procedure planning"; in <i>IEEE Access</i>, 7, pp. 125976-125990.'
---

The presence of specular highlight is a critical issue for both natural and medical images such as those produced by laparoscopes, which can lead to erroneous visual tracking, stereo reconstruction, and image segmentation. Specular highlight removal from a single image is necessary for image analysis and applications. Due to the differences between natural and medical image scenes, existing literature to address this issue has only been effective on natural images or medical images with textureless regions. To overcome this limitation, we propose a global optimization method for specular highlight removal from a single image based on a dichromatic reflection model. In addition to introducing modified illumination chromaticity, the proposed method consists of two novel steps: one for estimating diffuse chromaticity by correcting hue and saturation on highlighted regions, and the other for estimating diffuse and specular reflection coefficients using convex optimization with double regularization. The estimated diffuse chromaticity is proven to approximate the true diffuse chromaticity and the proposed optimization algorithm is guaranteed to find the optimal diffuse coefficients. Experimental results show that the proposed method can effectively remove specular highlights from both natural images and endoscopic images with texture detail preservation. To further demonstrate the efficacy of our proposed method, an application of stereo reconstruction using a public dataset illustrates that our highlight removal method can enhance surface reconstruction accuracy from 1.10mm RMSD to 0.69mm RMSD.

[Download paper here](https://ieeexplore.ieee.org/abstract/document/8822996) [BibTeX](./../files/bibtex/XCP+2019.bib)