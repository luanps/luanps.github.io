---
title: 'Rastreamento facial e refinamento de pontos fiduciais 3d baseado na
região do nariz em ambientes não controlados (SIBRAGPI, 2018)'
publications: true
layout: post
date: '2018-11-19 00:01:00'
tag:
- Nose tracker
- Face tracker
- Facial image quality
- 3d face alingment
category: publications
author: luan
---

***Abstract**:*
Neste trabalho foi explorado o uso da região do nariz para  realizar duas etapas essenciais para a análise de faces em ambientes sem restrição: (1) o rastreamento de faces em vídeos, e (2) o alinhamento de imagens de faces.

O rastreamento da face utiliza a informação temporal para inferir a posição da mesma em cada frame. Quando o rastreamento é aplicado em cenários não controlados, os métodos de detecção da face podem falhar.
As abordagens atuais são em geral baseadas em pontos fiduciais, porém encontram dificuldades quando aplicadas em cenários não triviais.
Para lidar com esta dificuldade, o presente trabalho explora de forma original o rastreamento da região do nariz, inicializando-o no frame de vídeo com melhor qualidade da face.
A região do nariz, ao invés da face inteira, foi escolhida devido sua menor probabilidade de estar oclusa, ser invariante a expressões faciais e visível em grande variações de pose.
Foram realizados experimentos na base de dados 300 Videos in the Wild e Point and Shoot Challenge, em comparação ao rastreamento da face, mostrando que o rastreamento pela região do nariz possui melhores resultados quando imagens mais complexas são usadas.

Já o alinhamento de faces em ambientes sem restrições consiste em localizar pontos fiduciais com precisão, auxiliando em tarefas como reconstrução 3D e análise de expressões faciais. Em cenários com variações de poses, a aparência da face difere da face frontal, dificultando a tarefa de alinhamento. Para contornar esta situação, este trabalho propõe refinar a localização dos pontos fiduciais com regressões em cascata e vetores de suporte (SVR), auxiliado pela pose estimada com a região do nariz. Experimentos foram realizados na base de dados 3D Face Alignment in the Wild, demonstrando resultados superiores ao alinhamento baseado na pose da cabeça, e comparáveis ao estado-da-arte.

e Silva, L. P., Bellon, O. R., & Silva, L. 
[Rastreamento facial e refinamento de pontos fiduciais 3D baseado na região do
nariz em ambientes não
controlados](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=2&cad=rja&uact=8&ved=2ahUKEwi6u6Tf3abjAhVcGbkGHS-mAvUQFjABegQIABAB&url=http%3A%2F%2Fsibgrapi.sid.inpe.br%2Frep%2Fsid.inpe.br%2Fsibgrapi%2F2018%2F10.17.11.03%3Fmirror%3Dsid.inpe.br%2Fbanon%2F2001%2F03.30.15.38.24%26metadatarepository%3Dsid.inpe.br%2Fsibgrapi%2F2018%2F10.17.11.03.04&usg=AOvVaw0tttJ_YtiMPFuqp6xQNIhR).
In Conf. on Graphics, Patterns and Images-Workshop of Theses and Dissertations, 2017.
