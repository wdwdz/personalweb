---
abstract: Interactive question-answering (QA) with a tutor is an effective learning method for middle school math students. The flexibility and emergent capabilities of generative large language models (LLMs) have sparked significant interest in automating this process to deepen conceptual understanding of mathematical learning. However, the issue of LLM hallucination has been well-documented in the research community. LLMs' responses to math problems can be inaccurate or misaligned with educational contexts, such as school curricula. A potential mitigating solution is retrieval-augmented generation (RAG), which involves integrating external knowledge sources into LLM prompts to enhance response quality. Although traditional RAG with vector embeddings has shown promise in improving generation quality, there are limitations regarding its information retrieval scalability, granularity, and explainability. One potential method to further improve traditional RAG is using a knowledge graph (KG). In this paper, we design a method to construct a KG with LLM, retrieve contextual prompts from high-quality math teaching resources via the KG, and then enhance the prompts to generate answers to real student questions about mathematical concepts. To evaluate the effect of retrieved information in RAG, we designed three levels of guidance prompts corresponding to three degrees of groundedness:high, low, and none. We evaluate from two perspectives:the semantic similarity between the retrieved information context and the generated text context, and conduct an experimental study to investigate the impact of our KG-enhanced QA system on student …
authors:
- Wanli Xing
- Chenglu Li
- Hai Li
- admin
- Bailing Liu
- Zeyu Yan

date: "2024-04-07T00:00:00Z"
doi: ""
featured: false
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false
# links:
# - name: Custom Link
#   url: http://example.org
# projects:
# - internal-project
# publication: ""
# publication_short: ""
# publication_types:
# - "3"
# publishDate: "2017-01-01T00:00:00Z"
# slides: example
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
#   ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
# tags:
# - Source Themes
title: Is Retrieval-Augmented Generation All You Need? Investigating Structured External Memory to Enhance Large Language Models’ Generation for Math Learning
# url_code: https://github.com/wowchemy/wowchemy-hugo-themes
# url_dataset: '#'
url_pdf: https://osf.io/preprints/edarxiv/mx83s
# url_poster: '#'
# url_project: ""
# url_slides: ""
# url_source: '#'
# url_video: '#'
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
