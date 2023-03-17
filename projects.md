---
layout: page
title: Projects
sidebar_link: true
description: Ricardo Guimarães' projects
sitemap:
  priority: 0.5
  changefreq: 'yearly'
  lastmod: '2023-03-17'
sidebar_sort_order: 2
---

<details><summary><b>Computing MVF Efficiently</b></summary>
<p>

In our novel approach to learning ontologies from knowledge graphs, we need to compute a graph metric which we call MVF. This metric indicates the maximum number of vertices that a walk in the graph can visit, given a fixed starting point. Computing this metric is linear on the size of the graph but, as we handle large graphs, we still need to find ways to optimise the MVF's computation, especially when doing it for multiple vertices. Not only that, we have to consider derivations of the original knowledge graph that are exponentially large on its size. The project would consist of devising, implementing and evaluating methods for efficient computation of the MVF, and that can also provide other useful information about the graph.

</p>
</details>

<details><summary><b>Selecting Knowledge Graph Repairs using Taxonomy Aware Embeddings</b></summary>
<p>

While Knowledge Graphs are becoming increasing popular, one persistent issue concerns the quality of data. Sometimes not only the information described is incomplete, but it is also incorrect. One can rely on ontological approaches or machine learning techniques using knowledge graph embeddings to fix incorrect information in such graphs. This project's primary research goal is to investigate the combination of methods in the mentioned approaches. Embeddings that can relate to the taxonomical rules in the Knowledge Graphs are particularly promising.

</p>
</details>

<details><summary><b>OWL2DL-CCC: A Corpus Generator for Ontology Repair</b></summary>
<p>

While there are already well-maintained corpora and methodologies to compare standard reasoners, there is still no standardise methodology or dataset
tailored for tasks such as Ontology Repair, Defeasible Reasoning, Inconsistent Tolerant Reasoner, and other non-standard applications.
The <a ref="https://gitlab.com/rfguimaraes/owl2dl-ccc">OWL 2 DL Change Case Creator (OWL2DL-CCC)</a> provides a convenient and flexible way to generate a corpus of ontologies for these tasks using a set of ontologies, and set of specifications that indicate how these ontologies should be modified. It produces as output a set of files that can be easily parsed and employed when testing and benchmarking different tools aimed at OWL 2 DL ontologies.

</p>
</details>
