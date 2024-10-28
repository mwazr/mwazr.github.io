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

**Description**
I present a novel method for measuring media bias using social media text data. Posts from political figures and media outlets are collected and processed through a large language model to extract "frames" — standardized declarative claims that encapsulate the core message of each post. These frames are embedded into a shared semantic space and clustered using a hierarchical density-based clustering algorithm, representing broadly held positions among politicians and media firms. For each account, vectors are constructed to represent the frequency of frames in each cluster, capturing the activity of each account across these clusters. I separate the vectors for politicians and use party labels to train a classifier model that predicts political affiliations based on contribution to frame clusters. The trained model is then applied to media outlets, generating probabilistic scores that position each outlet on a partisan spectrum. This method contributes to the literature on measuring media slant using modern machine-learning tools to better discern semantic patterns in language. This allows for a more granular separation of partisan positions and a more nuanced measure of partisan slant without sacrificing interpretability. 

### "Optimal Supply of Fact-Checking in a Model of Misinformation Propagation" with Patrick Warren & Morgan Wack

**Description**
This paper introduces a compartmental model to analyze the propagation of misinformation through social networks. We categorize a false narrative as spreading through two distinct types of claims: (1) viral, easy-to-fact-check claims, and (2) less viral, harder-to-fact-check claims. Our analysis reveals that when fact-checkers allocate excessive resources to combat type (1) claims, due to their virality and ease of fact-checking, it inadvertently allows type (2) claims, which are more complex and harder to debunk, to proliferate—potentially leading to a larger, long-term spread of the false narrative. We propose optimal fact-checking strategies that effectively manage the long-term spread of misinformation by balancing resource allocation between these claim types. Our findings suggest that fact-checkers should not solely focus on the immediate efficiency of debunking viral claims but also account for the transmission dynamics and interactions between different types of claims that collectively sustain a broader false narrative. We are currently empirically analyzing data to observe fact-checking behavior and its impact on misinformation transmission. 
