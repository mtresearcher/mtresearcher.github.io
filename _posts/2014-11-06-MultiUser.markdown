---
layout: post
title: MultiUser adaptive SMT
---

In this paper we investigate the problem of adapting a machine translation system to the
feedback provided by multiple post-editors. It is well know that translators might have very
different post-editing styles and that this variability hinders the application of online
learning methods, which indeed assume a homogeneous source of adaptation data.
We hence propose {\em multi-task learning} to  leverage bias information from each single
post-editors in order to constrain the evolution of the SMT system. A new framework for 
significance testing with sentence level metrics is described which shows that
Multi-Task learning approaches outperforms existing online learning approaches, with
significant gains of 1.24 and 1.88 TER score over a strong online adaptive baseline, 
on a test set of post-edits produced by four translators texts and on a popular benchmark 
with multiple references, respectively.

You can find the paper [here](https://hlt.fbk.eu/sites/hlt.fbk.eu/files/amta2014.pdf)
