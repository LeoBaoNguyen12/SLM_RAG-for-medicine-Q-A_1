# SLM-RAG for Medical Question Answering: Bridging Clinical Practice with Biomedical Evidence
![Made With python](https://img.shields.io/badge/Made%20with-Python-brightgreen)![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)![Pytorch](https://img.shields.io/badge/Made%20with-Pytorch-green.svg)

### Download Large Files
Due to GitHub file size limitations, please download the following dataset files from our Google Drive:

- **All Dataset Files**: [Download from Google Drive](https://drive.google.com/drive/folders/1wvsLcidxxceB7LyCs3b3T4tfC4stptOy?usp=share_link)

The download includes:
- `ori_pqaa.json`
- `ori_pqal.json` 
- `ori_pqau.json`

### Abstract
The chasm between burgeoning scientific discoveries and their practical application in clinical settings poses a significant challenge in modern healthcare. To bridge this gap, we propose a novel hybrid system that integrates Small Language Models (SLMs) with Retrieval-Augmented Generation (RAG) for delivering precise and comprehensible medical information, specifically for cancer-related queries. Our system harnesses curated biomedical sources such as PubMed articles and clinical guidelines converting them into vector embeddings via BioBERT to enable high-fidelity semantic retrieval. We then employ an SLM to synthesize the retrieved evidence into fluent, context-aware responses, which are delivered in the user's native language. Through experimental evaluation, we demonstrate that our SLM+RAG framework not only enhances answer accuracy and mitigates hallucinations but also optimizes computational efficiency compared to larger language models. Furthermore, the system allows for seamless updates to domain knowledge without requiring extensive retraining. Our findings confirm that this approach reliably aids clinicians in decision-making and empowers patients by demystifying complex medical information. We conclude that the fusion of SLMs with RAG presents a scalable, practical pathway for clinical decision support and medical education, particularly in resource-constrained environments. Our implementation is available in this Github repository.

### Paper
(Link paper will be deployed)

### Citation
If you would like to cite this paper, please use the following reference:
@inproceedings{author2025slmrag,
title={SLM-RAG for Medical Question Answering: Bridging Clinical Practice with Biomedical Evidence},
author={Nguyen, Gia Bao and Le, Quang Hung},
booktitle={Proceedings of the 2nd International Conference on Computational Intelligence in Engineering Science},
year={2025}
}