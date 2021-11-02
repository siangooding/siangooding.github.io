---
title: MPhil Projects
featured_image: /images/home.jpg
---

<h2>Curriculum learning for text simplfication</h2>

Humans and animals learn much more effectively when the examples are not randomly presented but organized in a meaningful way. For instance, by introducing gradually more concepts, and increasingly more complex ones. [1] This has been referred to as <i>curriculum learning</i>. The use of a curriculum learning framework applied to neural machine translation has been shown to reduce training time and result in overall better performance [2]. 

Text simplification is aimed at reducing the reading and grammatical complexity of text whilst retaining the meaning. Neural machine translation approaches have dominated the text simplification field over the past few years [3]. In this setting, the aim is to 'translate' complex text to simpler text using traditional translation architectures. In this project you will investigate whether curriculum learning can be used to improve an NMT system for text simplification. You will reimplement a neural translation system and experiment with how the ordering of training data impacts the model performance. 


## Proficiency prediction from reading behaviour 

Reading comprehension is based on a range of reader-related, text-related, and situational factors. It has been defined as the ability to process text, understand its meaning, and integrate the meaning with what the reader already knows. Being able to judge whether a reader would comprehend a given text requires knowledge of their background and level of proficiency. Techniques have been explored that measure how an individual interacts with text whilst reading to predict their proficiency level. For instance, features from eye tracking have been used to predict the language proficiency of readers [4]. 

On device reading has predominantly taken the place of traditional formats. Such devices allow access to implicit user feedback by measuring how a user interacts with the text they read. A key advantage to implicit feedback techniques is that they can unobtrusively obtain information by measuring user interactions with a system. In this project, you will use a <a href = "https://github.com/siangooding/readability_scroll">dataset that has been collected in collaboration with Google</a>, containing implicit reading interactions of participants whilst reading [5][6]. Using features extracted from text interactions, the aim is to predict the comprehension score and proficiency of readers.



### Sources
[1] <a href ="https://dl.acm.org/doi/pdf/10.1145/1553374.1553380?casa_token=YNHzxTxY7_AAAAAA:J-BmBwUXzD9VVpteUvFRRdWsa-BYVRoZ_8lhn8Wvnj2Om07XLWkhPh3DLNUpGHLrXL5979wV88vD">Curriculum learning (Bengio et al., 2009)</a> <br>
[2] <a href = "https://arxiv.org/pdf/1903.09848.pdf">Competence-based Curriculum Learning for Neural Machine Translation (Plantanious et al., 2019)</a> <br>
[3] <a href="https://arxiv.org/pdf/2008.08612.pdf">A Survey on Text Simplification (Sikka and Mango, 2020)</a>

[4] <a href="https://arxiv.org/pdf/1804.07329.pdf">Assessing Language Proficiency from Eye Movements in Reading (Berzak et al., 2018)</a>
[5]  <a href="https://arxiv.org/pdf/2105.06354.pdf">Predicting Text Readability from Scrolling Interactions (Gooding et al., 2021)</a>
[6] <a href="https://ai.googleblog.com">Google AI Blog (Gooding, 2021)</a>