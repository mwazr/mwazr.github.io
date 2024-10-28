---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 2
---

## Working Papers

### “Traditional Media Bias and Offline Polarization in the Online Era”

**Abstract**  
Television news has become increasingly partisan in recent decades, while the U.S. population's self-reported ideological distribution has remained stable. Concurrently, political polarization has risen, particularly among demographic groups least likely to use the Internet. This paper presents a theory that ties these observations together. I show that if developments in a substitute platform tend to attract better-informed audiences away from traditional media firms, they strategically respond with an increase in slanted reporting — despite no changes in the ideological distribution of the population. This rise of slant leads to increased partisan disagreements among less-informed audiences who rely more on traditional media. To empirically investigate an implication of the theory, I collect a novel dataset of Facebook posts from 600 U.S. local television news channels from 2012 to 2016. I perform an algorithmic text analysis to measure partisanship changes in news and find that markets with greater increases in moderately high-speed Internet connections also exhibit larger increases in local news partisanship. 

## Work In Progress

### “An LLM-Aided Measure of Media Slant from Social-Media Text Data”

I present a novel method for measuring media bias using social media text data. Posts from political figures and media outlets are collected and processed through a large language model to extract "frames" — standardized declarative claims that encapsulate the core message of each post. These frames are embedded into a shared semantic space and clustered using a hierarchical density-based clustering algorithm, representing broadly held positions among politicians and media firms. For each account, vectors are constructed to represent the frequency of frames in each cluster, capturing the activity of each account across these clusters. I separate the vectors for politicians and use party labels to train a classifier model that predicts political affiliations based on contribution to frame clusters. The trained model is then applied to media outlets, generating probabilistic scores that position each outlet on a partisan spectrum. This method contributes to the literature on measuring media slant using modern machine-learning tools to better discern semantic patterns in language. This allows for a more granular separation of partisan positions and a more nuanced measure of partisan slant.
