---
title: Noisy Positive-Unlabeled Learning with Self-Training for Speculative Knowledge
  Graph Reasoning
authors:
- Ruijie Wang
- Baoyu Li
- Yichen Lu
- Dachun Sun
- Jinning Li
- Yuchen Yan
- Shengzhong Liu
- Hanghang Tong
- Tarek Abdelzaher
date: '2023-07-01'
publishDate: '2024-10-22T21:14:10.115239Z'
publication_types:
- paper-conference
publication: '*Findings of the Association for Computational Linguistics: ACL 2023*'
# doi: 10.18653/v1/2023.findings-acl.153
abstract: This paper studies speculative reasoning task on real-world knowledge graphs
  (KG) that contain both false negative issue (i.e., potential true facts being excluded)
  and false positive issue (i.e., unreliable or outdated facts being included). State-of-the-art
  methods fall short in the speculative reasoning ability, as they assume the correctness
  of a fact is solely determined by its presence in KG, making them vulnerable to
  false negative/positive issues. The new reasoning task is formulated as a noisy
  Positive-Unlabeled learning problem. We propose a variational framework, namely
  nPUGraph, that jointly estimates the correctness of both collected and uncollected
  facts (which we call label posterior) and updates model parameters during training.
  The label posterior estimation facilitates speculative reasoning from two perspectives.
  First, it improves the robustness of a label posterior-aware graph encoder against
  false positive links. Second, it identifies missing facts to provide high-quality
  grounds of reasoning. They are unified in a simple yet effective self-training procedure.
  Empirically, extensive experiments on three benchmark KG and one Twitter dataset
  with various degrees of false negative/positive cases demonstrate the effectiveness
  of nPUGraph.
# links:
# - name: URL
#   url: https://aclanthology.org/2023.findings-acl.153
url_pdf: https://aclanthology.org/2023.findings-acl.153
---
