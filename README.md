### Hi there, I'm Philipp 👋

AI Scientist focusing on Generative AI and NLP, building systems that decipher complex human data — from ancient languages to modern clinical records. Contact: philipp.wiesenbach@gmail.com

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/philipp-wiesenb/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-555555?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.de/citations?user=zdNEDqgAAAAJ&hl=de)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-FFDF00?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/phiwi)

> **Notice:** Active development is on the `2.0` branches: [biolm_utils](https://github.com/dieterich-lab/biolm_utils/tree/biolm-2.0), [rna_protein_xlnet](https://github.com/dieterich-lab/rna_protein_xlnet/tree/xlnet-2.0), [rna_saluki_cnn](https://github.com/dieterich-lab/rna_saluki_cnn/tree/saluki-2.0). `main` branches are legacy.

**Recent highlights**
- BertGCN: interpretable clinical/precedent-aware text classification with BERT + GCN
- LLM_Relations: LLM-based molecular interaction extraction → biological relation graph
- biolm_utils: modular bioinformatics DL platform (training, inference, XAI)

Below is a selection of key projects I've led or significantly contributed to during my time at the Klaus-Tschira-Institute (Dieterich Lab).

---

### 🚀 Key Projects & Contributions

#### 1. Architect of `biolm_utils`: A Deep Learning Framework for Bioinformatics
*   **Project:** [`dieterich-lab/biolm_utils`](https://github.com/dieterich-lab/biolm_utils)
*   **Role:** Lead Architect & Developer
*   **Tech:** Python, PyTorch, Hydra, Hugging Face, XAI

#### 2. Application: `rna_protein_xlnet` (Transformer-based Modeling)
*   **Project:** [`dieterich-lab/rna_protein_xlnet`](https://github.com/dieterich-lab/rna_protein_xlnet)
*   **Role:** Lead Developer
*   **Tech:** XLNet, PyTorch, biolm_utils plugins

#### 3. Application: `rna_saluki_cnn` (CNN-based Modeling)
*   **Project:** [`dieterich-lab/rna_saluki_cnn`](https://github.com/dieterich-lab/rna_saluki_cnn)
*   **Role:** Core Contributor
*   **Tech:** Custom CNN (Saluki), PyTorch, biolm_utils plugins
*   **Citation:** Agarwal, V., & Kelley, D. (2022). The genetic and biochemical determinants of mRNA degradation rates in mammals. bioRxiv.

#### 4. LLM Relations: Knowledge Graph Generation from Scientific Text
*   **Project:** [`dieterich-lab/LLM_Relations`](https://github.com/dieterich-lab/LLM_Relations)
*   **Role:** Lead Developer & Architect
*   **Tech:** Mistral/Llama, extraction pipelines, graph construction
*   *Specific contributions:* [llm_extractions](https://github.com/dieterich-lab/LLM_Relations/tree/main/llm_extractions)

#### 5. BertGCN: Graph Neural Networks with Document-Level Interpretability for Precedents Detection
*   **Project:** [`dieterich-lab/BertGCN`](https://github.com/dieterich-lab/BertGCN)
*   **Role:** Lead Developer
*   **Tech:** BERT, GCN, PyTorch Geometric, Hydra, MLflow
*   **Uniqueness:** Interpretable text classification framework that integrates BERT's contextual embeddings with graph convolutional networks to model document relationships, enabling precedent-aware classification in clinical settings.
*   **Key Innovation:** Novel combination of BERT and GCN for transductive learning on text graphs constructed with PMI and TF-IDF edge weighting, providing document-level interpretability for clinical decision-making.
*   **Citation:** Lin, Y., Meng, Y., Sun, X., Han, Q., Kuang, K., Li, J., & Wu, F. (2021). BertGCN: Transductive Text Classification by Combining GCN and BERT. arXiv preprint arXiv:2105.05727.
*   **Note:** This implementation uses confidential clinical data. No training data or trained models are publicly shared to maintain patient privacy and data security.

#### 6. CardioGuidelinesGraph: Knowledge Graph Construction from German Cardiovascular Guidelines
*   **Project:** [`dieterich-lab/CardioGuidelinesGraph`](https://github.com/dieterich-lab/CardioGuidelinesGraph)
*   **Role:** Lead Developer & Architect
*   **Tech:** Python, Neo4j, SNOMED CT, scispaCy, Ollama LLMs, Docling, BAML
*   **Uniqueness:** Pioneering approach to transform German medical guidelines into standardized, queryable knowledge graphs. Combines advanced PDF processing, biomedical NLP, and ontology engineering to create the first comprehensive KG for cardiovascular care in German, enabling semantic search, automated reasoning, and RAG applications for clinical decision support.
*   **Key Innovation:** Integrates SNOMED CT terminology with LLM-powered concept categorization, extracting 21,000+ medical concepts from guidelines while preserving complex clinical relationships and evidence-based recommendations.

---

### 🌍 Community & Open Source Contributions

#### Ancient Egyptian Translation Dataset
*   **Hugging Face Link:** [`phiwi/bbaw_egyptian`](https://huggingface.co/datasets/phiwi/bbaw_egyptian)
*   **Context:** This project connects my unique background in both Egyptology and Computational Linguistics. I curated, processed, and uploaded this dataset to the Hugging Face Hub to make it accessible for the community, enabling new research in low-resource machine translation. This work is directly related to my IWSLT 2019 publication on translating ancient texts with Transformer models.

---

### 📚 Lectures & Teaching

#### Graph Neural Networks in Modern Medicine
*   **Date:** November 13, 2025
*   **Audience:** Master's students in Medical Informatics
*   **Duration:** 90 minutes
*   **Topic:** Introduction to Graph Neural Networks, exploring their applications from molecular interactions to patient outcomes in biomedical research.
*   **Slides:** [View Presentation](https://phiwi.github.io/graphnn_lecture/)

---

### 🛠️ My Tech Stack

*   **Languages:** Python, Bash, Cypher, Java
*   **AI/ML:** PyTorch, Huggingface, Langchain, LlamaIndex, Scikit-Learn, Spacy
*   **Infrastructure & Data:** Docker, Git, HPC/Slurm, Neo4j, FAISS, MongoDB
