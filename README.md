# medical_iclr_2025
Summary of Medical-Based Papers of ICLR 2025
- [MMED-RAG: VERSATILE MULTIMODAL RAG SYSTEM FOR MEDICAL VISION LANGUAGE MODELS](https://arxiv.org/pdf/2410.13085) **MLLM**
  - Problem Area: Improve Factuality or Reduce Hallucination Problem in Medical Large Vision Language Model.
  - Existing Solution: Fine-tuning (Lack of correct and well-labeled medical data). Additionally, there is a  domain gap between train and real data. Hence, RAG is a better option. However, recent methods are dataset-specific, and not generalized enough. At the same time, there remains a  misalignment issue. *This misalignment may arise from the impact of adding RAG on the original Med-LVLMs’ cross-modality alignment, as well as on the overall alignment between the model and ground truth*
  - Paper Solution : **M**ultimodal **Med**ical **RAG** system called MMed-RAG
      - introduces a domain-aware retrieval mechanism
      - designs a domain identification module
      - Includes a adaptive calibration approach for selecting the number of retrieved contexts.
      - Incorporates RAG-based preference fine-tuning to enhance cross-modality alignment and overall alignment with ground truth.

- [Reliable and Diverse Evaluation of LLM Medical Knowledge Mastery] (https://arxiv.org/pdf/2409.14302) **LLM**
  - Problem Area: Evaluate and Improve LLM's medical knowledge mastery with diverse test samples.
  - Existing Solution: Using LLM to generate test samples. Two Problem: Incorrect Factuality and Less Diverse.
  - Paper Solution: Proposes a Predicate-to-text Evaluation method (PretexEval) that dynamically generates reliable and structurally diverse test samples based on the medical knowledge points from knowledge bases.
- [TIME AFTER TIME: SCALABLE EFFECT ESTIMATION FOR INTERVENTIONS ON WHEN AND WHAT TO DO](https://openreview.net/pdf/29e1e0a0d4a12f556d73eb90edbcb7cc863e2fa1.pdf) **LLM**
  - This paper is trying to solve is how to estimate the effects of treatment timing in sequential decision-making, particularly in fields like healthcare and finance. Current methods struggle with handling irregularly spaced events—where treatments and observations do not happen at fixed intervals—leading to inaccurate or inefficient models. Many existing approaches either require discretizing time, which loses important details, or do not scale well to large models.
- [Efficiently Democratizing Medical LLMs for 50 Languages via a Mixture of Language Family Experts](https://arxiv.org/pdf/2410.10626) **LLM**
  - Problem Area: How to improve multilingual medical LLMs by addressing key challenges in data scarcity and model scalability
  - Solution: Creates a Dataset, And have a Post-MOE to choose and show its superior multilingual capabilities.
- [Future-Guided Pretraining via Time-to-Event Supervision for 3D Medical Imaging](https://arxiv.org/pdf/2411.09361)
  - Problem Area:
- [Prompt as Knowledge Bank: Boost Vision-language model via Structural Representation for zero-shot medical detection](https://openreview.net/pdf?id=l0t2rumAvR)
- [MEDICONFUSION: CAN YOU TRUST YOUR AI RADIOLOGIST? PROBING THE RELIABILITY OF MULTIMODAL MEDICAL FOUNDATION MODELS](https://arxiv.org/pdf/2409.15477)
- 
