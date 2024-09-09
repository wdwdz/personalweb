---
date: "2022-12-31T00:00:00Z"
external_link: ""

tags:
- Creation via AI
title: RAG Technologies
url_code: ""
url_pdf: "https://osf.io/preprints/edarxiv/mx83s"
url_slides: ""
url_video: ""

---
Levonian, Z., Li, C., Zhu, W., Gade, A., Henkel, O., Postle, M. E., & Xing, W. (2023). Retrieval-augmented Generation to Improve Math Question-Answering: Trade-offs Between Groundedness and Human Preference. NeurIPS'23. New Orleans, Florida, United States.\
Xing, W., Li, C., Li, H., Zhu, W., Lyu, B., & Yan, Z. (2024, September 5). Is Retrieval-Augmented Generation All You Need? Investigating Structured External Memory to Enhance Large Language Models’ Generation for Math Learning.

The first article is RAG using vector embeddings; the second article RAG using knowledge graphs.

Issues of LLM hallucination have
been well documented in the research community, where LLMs’
responses to math problems can be inaccurate or misaligned
with educational contexts such as school curricula. A potential
mitigating solution is retrieval-augmented generation (RAG),
which involves integrating external knowledge sources into LLM
prompts to enhance response quality. Although traditional RAG
with vector embeddings has shown promise to improve generation
quality, there are limitations regarding its information retrieval
scalability, granularity, and explainability. One potential method
to further improve the traditional RAG is using a knowledge
graph (KG). In this paper, we design a method to construct KG
with LLM, retrieve contextual prompts from high-quality math
teaching resources via KG, and then enhance the prompts to
generate answers to real student questions about mathematical
concepts. To evaluate the effect of retrieved information in RAG,
we designed three levels of guidance prompts corresponding
to three degrees of groundedness: high, low, and none. We
evaluate from two perspectives: the semantic similarity of the
retrieved information context and the generated text context, and
conduct an experimental study to investigate the impact of our
KG-enhanced QA system on student learning gains. The study
found that compared to baseline methods, the KG-based RAG
approach can enhance the groundedness and faithfulness of both
the retrieved documents and the generated context. Additionally,
low guidance can improve student learning gains. Our technical
framework and analysis results contribute to advancing the
application of LLMs in educational technology.