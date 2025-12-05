# A Novel Approach Based on Integrating Small Language Models and Retrieval-Augmented Generation for Medical Question Answering
![Made With python](https://img.shields.io/badge/Made%20with-Python-brightgreen)![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)![Pytorch](https://imgshields.io/badge/Made%20with-Pytorch-green.svg)

### Download Large Files
Due to GitHub file size limitations, please download the following dataset files from our Google Drive:

- **All Dataset Files**: [Download from Google Drive](https://drive.google.com/drive/folders/1wvsLcidxxceB7LyCs3b3T4tfC4stptOy?usp=share_link)

The download includes:
- `ori_pqaa.json`
- `ori_pqal.json` 
- `ori_pqau.json`

### Abstract
This paper proposes a novel approach that integrates Small Language Models (SLMs) with Retrieval-Augmented Generation (RAG) to deliver precise and comprehensible medical information, specifically for cancer-related queries. Our method leverages curated biomedical sources such as PubMed articles and clinical guidelines, converting them into vector embeddings via BioBERT to enable high-fidelity semantic retrieval. An SLM is then employed to synthesize the retrieved evidence into fluent, context-aware responses, which are delivered in the user's native language.In the process of experimental evaluation, we demonstrate that our SLM+RAG framework not only enhances answer accuracy and mitigates hallucinations, but also improves computational efficiency compared to larger language models. Additionally, the approach supports seamless domain knowledge updates without requiring extensive retraining. Our findings indicate that this method reliably assists clinicians in decision-making while empowering patients by demystifying complex medical information. We conclude that the fusion of SLMs with RAG presents a scalable and practical pathway for clinical decision support and medical education, particularly in resource-constrained environments.

### Paper
(Link paper will be deployed)

### Citation
If you would like to cite this paper, please use the following reference:

```bibtex
@inproceedings{author2025slmrag,
title={A Novel Approach Based on Integrating Small Language Models and Retrieval-Augmented Generation for Medical Question Answering},
author={Nguyen, Gia Bao and Le, Quang Hung}, 
year ={2025}}