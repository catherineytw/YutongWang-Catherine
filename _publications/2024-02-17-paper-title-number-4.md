---
title: "Make-A-Character: High Quality Text-to-3D Character Generation within Minutes"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: "We propose a user-friendly framework named Make-A-Character (Mach) to create lifelike 3D avatars from text descriptions. <img src='../images/make_a_character.jpg'>"
date: 2024-01-20
venue: 'arXiv preprint'
url: "https://human3daigc.github.io/MACH/"
paperurl: 'https://arxiv.org/pdf/2312.15430'
citation: 'Jianqiang Ren, Chao He, Lin Liu, Jiahao Chen, <b>Yutong Wang</b>, Yafei Song, Jianfang Li, Tangli Xue, Siqi Hu, Tao Chen, Kunkun Zheng, Jianjing Xiang, Liefeng Bo. &quot;Make-A-Character: High Quality Text-to-3D Character Generation within Minutes.&quot; <i>arXiv preprint arXiv:2312.15430s</i>.'
---

[Git](https://human3daigc.github.io/MACH/)

There is a growing demand for customized and expressive 3D characters with the emergence of AI agents and Metaverse, but creating 3D characters using traditional computer graphics tools is a complex and time-consuming task. To address these challenges, we propose a user-friendly framework named Make-A-Character (Mach) to create lifelike 3D avatars from text descriptions. The framework leverages the power of large language and vision models for textual intention understanding and intermediate image generation, followed by a series of human-oriented visual perception and 3D generation modules. Our system offers an intuitive approach for users to craft controllable, realistic, fully-realized 3D characters that meet their expectations within 2 minutes, while also enabling easy integration with existing CG pipeline for dynamic expressiveness. For more information, please visit the project page at https://human3daigc.github.io/MACH/.

<img src='../../images/make_a_character_framework.png'>

The overview of Make-A-Character. The framework utilizes the Large Language Model (LLM) to extract various facial attributes(e.g., face shape, eyes shape, mouth shape, hairstyle and color, glasses type). These semantic attributes are then mapped to corresponding visual clues, which in turn guide the generation of reference portrait image using Stable Diffusion along with ControlNet. Through a series of 2D face parsing and 3D generation modules, the mesh and textures of the target face are generated and assembled along with additional matched accessories. The parameterized representation enable easy animation of the generated 3D avatar.
