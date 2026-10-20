---
layout: default
title: Projects
permalink: /projects/
---

## Current Projects

I am investigating how people detect AI-generated images and what factors make them miss the subtle artifacts these images contain, under supervision of <a href="https://mattgroh.com/" target="_blank">Matt Groh</a> and <a href="http://users.eecs.northwestern.edu/~jhullman/" target="_blank">Jessica Hullman</a> at Northwestern. My research aims to develop tools and techniques to enhance human ability to distinguish between real and synthetic images. In a world where AI-generated images are increasingly realistic, understanding how people perceive them is crucial for combating misinformation and maintaining trust in visual media.

Think you can distinguish real photos from AI-generated images? Try our <a href="https://detectfakes.kellogg.northwestern.edu/" target="_blank">DetectFakes</a> website!

**Mechanistic Interpretability of AI-Image Detection:** I am studying what open-weight vision-language models know about AI-generated images and whether they use it. Linear probes on model activations detect AI-generated images far better than the models' own answers (AUC 0.92, against 62% accuracy), and activation patching and region ablation indicate that the evidence is present in the model but goes unused when it writes advice. The work covers Qwen3-VL and Gemma.

**LLM Coach for Cash-Transfer Recipients:** I led Northwestern's evaluation of a WhatsApp LLM coach that <a href="https://www.givedirectly.org/" target="_blank">GiveDirectly</a> deployed to cash-transfer recipients in Rwanda. I helped design a randomized comparison of two coaching prompts, built an arm-blind LLM-as-judge rubric for topics, coaching style, and plan formation, and analyzed more than 1,500 real voice and text conversation turns. GiveDirectly's product and leadership teams adopted a single-agent design and revised their prompts before launch.

**Decision-Calibrated Explanations:** I contributed the human judgment data behind HD-RL, a reinforcement learning method that fine-tunes an open-weight LLM to write explanations that improve human decisions, using a reward model trained on real human choices. In a four-arm human evaluation, its explanations raised accuracy to 65.6%, against 51.9 to 55.3% for the RLVR and RLAIF baselines.

## Past Projects

**Conformal Prediction for AI-Advised Decisions:** Advised by <a href="http://users.eecs.northwestern.edu/~jhullman/" target="_blank">Jessica Hullman</a>, I researched enhancing AI-advised decision-making by accurately quantifying prediction uncertainty of deep neural networks. I explored the effectiveness of conformal prediction sets as an alternative to traditional uncertainty measures, measuring how they impact human decisions in real-world image labeling scenarios. This work received a **Best Paper Honorable Mention** at CHI 2024.

**Prenatal Stress Reduction:** In collaboration with the <a href="https://casmi.northwestern.edu/" target="_blank">Center for Advancing Safety of Machine Intelligence (CASMI)</a>, advised by <a href="https://sites.northwestern.edu/nupath/people/" target="_blank">Maia Jacobs</a>, I worked on <a href="https://casmi.northwestern.edu/research/projects/prenatal-stress-reduction.html" target="_blank">co-designing patient-facing machine learning for prenatal stress reduction</a>.
