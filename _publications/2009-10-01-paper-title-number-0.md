---
title: "Sketch-Based Interactive Modeling of Geology (in Chinese)"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-0
excerpt: "We present a new method to efficiently generate a set of morphologically diverse and inspiring virtual trees through hierarchical topology-preserving blending, aiming to facilitate designers’ creativity production. <img src='../images/sketch_geology.jpg'>"
date: 2015-10-01
venue: 'Journal of Software'
paperurl: 'https://jos.org.cn/josen/article/pdf/16035'
citation: '<b>王雨桐</b>, 陈 浩, 田唐昊, 金小刚. &quot; Sketch-Based Interactive Modeling of Geology &quot; <i>Journal of Software.</i>, 2016,27(S2):207-219.'
---

<img src='../images/sketch_geology_2.jpg'>

This paper proposes a sketch-based interactive geological modeling method, aiming at helping geologists to effectively create data-free conceptual geological models at the early stage of geological exploration. Up to date, the majority of the existing professional
modeling tools take expensive measured data to build sophisticated 3D geological models, and usually suffer from the drawbacks of time-consuming and difficult to learn and use. Therefore, this paper exploits the intuitiveness of “paper-pencil” metaphor and develops a
complete sketch-based interactive geological modeling framework, including 3D sketching, surfacing and sketch-based model editing. Geological sketches can be drawn on user-defined 3D drawing planes. Intersecting sketches constitute a sketch network, from which the
corresponding 3D model is generated on the fly with the surface patching method. Specifically, surface patching employs the idea of divide-and-conquer and takes three steps. Based on the topology of the sketch network, planar cycles are first collected by minimizing
their geometric energies, i.e. the corners. Then, surface patches are generated for each cycle by Laplacian optimization of the target mean curvatures and normals, which are pre-computed by harmonic functions. Finally, surface patches are stitched to make a complete 3D model. Geological phenomena such as folding and faulting can be modeled by over-sketching and cutting operations, respectively. In
addition, the hierarchy of models is preserved in a hierarchical tree structure. To maintain the contact between geo-bodies, the deformation of an edited model is automatically transferred to its siblings and parents on the basis of their hierarchies. Compared to the existing sketch-based modeling tools, awareness of the geological knowledge makes the method advantageous in effectively describing geo
-bodies with fewer expressive sketches. Based on user experiences, this method is intuitive and easy-to-use for both professionals and inexperienced users to model illustrative geological scenarios.
