---
title: "Beyond Calibration: Assessing the Probabilistic Fit of Neural Regressors via Conditional Congruence"
collection: publications
category: manuscript
permalink: /publication/probcal
excerpt: 'While significant progress has been made in specifying neural networks capable of representing uncertainty, deep networks still often suffer from overconfidence and misaligned predictive distributions. Existing approaches for addressing this misalignment are primarily developed under the framework of calibration, with common metrics such as Expected Calibration Error (ECE). However, calibration can only provide a strictly marginal assessment of probabilistic alignment. Consequently, calibration metrics such as ECE are distribution-wise measures and cannot diagnose the point-wise reliability of individual inputs, which is important for real-world decision-making. We propose a stronger condition, which we term conditional congruence, for assessing probabilistic fit. We also introduce a metric, Conditional Congruence Error (CCE), that uses conditional kernel mean embeddings to estimate the distance, at any point, between the learned predictive distribution and the empirical, conditional distribution in a dataset. We show that using CCE to measure congruence 1) accurately quantifies misalignment between distributions when the data generating process is known, 2) effectively scales to real-world, high dimensional image regression tasks, and 3) can be used to gauge model reliability on unseen instances.'
date: 2025-05-06
venue: '28th European Conference on Artifical Intelligence (ECAI) [In Submission]'
paperurl: 'https://arxiv.org/abs/2405.12412'
bibtexurl: 'http://spencermyoung513.github.io/files/probcal.bib'
citation: 'Young, S., Edgren, C., Sinema, R., Hall, A., Dong, N. & Jenkins, P. (2025). &quot;Beyond Calibration: Assessing the Probabilistic Fit of Neural Regressors via Conditional Congruence.&quot; <i>28th European Conference on Artifical Intelligence [In Submission]</i>.'
---
