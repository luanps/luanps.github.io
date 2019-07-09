---
title: 'Follow that nose: tracking faces based on the nose region and image quality
  feedback. (SIBGRAPI, 2016)'
publications: true
layout: post
date: '2016-10-31 00:00:00'
tag:
- Face tracker
- Nose tracker
- Facial image quality
category: publications
author: luan
---

***Abstract**:*
Face tracking uses temporal information to infer the position of the face in each frame. 
One of its applications is in unconstrained (in-the-wild) environments where face detection methods fail to perform robustly. 
Current approaches presented in the literature are based on facial landmarks. 
Therefore, they have limitations when applied in in-the-wild environments as estimating the landmarks in such scenarios is not trivial. 
To address this issue, we propose a novel landmark-free approach based on a state-of-the-art generic visual tracking method, as baseline, combined with face quality assessment for initializing the tracking. 
In addition, we introduce using only the nose region as a solution for in-the-wild face tracking, initializing it with the nose of the best quality face in the video sequence. 
The nose is detected and used to estimate the head pose, which is combined with the face quality score for choosing the initialization frame. 
The nose region, rather than the entire face was chosen due to it being unlikely to be occluded, mostly invariant to facial expressions and visible in a long range of head poses. 
We performed experiments on the 300 Videos in the Wild dataset and our results favorably compared against the baseline method.

Silva, L. P., Zavan, F. H. D. B., Bellon, O. R., & Silva, L. [Follow that nose: tracking faces based on the nose region and image quality feedback](http://gibis.unifesp.br/sibgrapi16/eproceedings/wfpa/11.pdf). In Conf. on Graphics, Patterns and Images-W. Face Processing, 2016