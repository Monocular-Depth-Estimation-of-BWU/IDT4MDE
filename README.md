# IDT4MDE
Image Dependent Dynamic Prompt Token Enhancement for CLIP-Based Monocular Depth Estimation

Authors: Dongjie Zhao , Lekai Sun , Shenao Song ,Yue Wu 

Abstract
As a powerful vision‑language pre‑trained model, CLIP (Contrastive Language‑Image Pre‑training) has demonstrated exceptional zero‑shot transferability across a variety of open‑ended tasks. Recently, DepthCLIP reformulated monocular depth estimation (MDE) as an ordinal classification task using language prompts, while Auty et al. further proposed replacing hand‑crafted prompts with learnable textual tokens. However, existing approaches remain constrained by static text representations and fail to fully exploit the dynamic associations between cross‑modal features.

In this study, we propose Image‑Dependent Dynamic Prompt Tokens (IDT) that are conditioned on image features. By establishing hierarchical interactions between multi‑scale features from the CLIP image encoder and learnable textual tokens, our approach enables text embeddings to dynamically adapt to image content. Experiments on the NYU‑Depth V2 and KITTI datasets demonstrate that our method achieves state‑of‑the‑art performance under zero‑shot settings. Compared to Auty’s prompt‑based approach, our method reduces the absolute relative error (AbsREL) by 25.3% on NYU‑Depth V2 (from 0.324 to 0.242) and by 48.5% on KITTI (from 0.307 to 0.158). Ablation studies further reveal that IDT exhibits stronger robustness in challenging scenarios, such as transparent objects and weak‑texture regions.

Keywords: Monocular Depth Estimation, Prompt Engineering, CLIP.

<img width="1202" height="776" alt="image" src="https://github.com/user-attachments/assets/79d5f1e0-1056-473c-b77c-511ffa7e98b8" />
