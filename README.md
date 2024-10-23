# Enhancing-Skin-Disease-Classification-Using-Transformers

Official implementation of the paper: "Enhancing Skin Disease Classification Leveraging Transformer-based Deep Learning Architectures and Explainable AI"

Abstract:

Skin diseases affect over a third of the global population, yet their impact is often underestimated. Automating the classification of these diseases is essential for supporting timely and accurate diagnoses. This study leverages Vision Transformers, Swin Transformers, and DinoV2, introducing DinoV2 for the first time in dermatology tasks. On a 31-class skin disease dataset, DinoV2 achieves state-of-the-art results with a test accuracy of 96.48% and an F1-Score of 0.9727, marking a nearly 10% improvement over existing benchmarks. The robustness of DinoV2 is further validated on the HAM10000 and Dermnet datasets, where it consistently surpasses prior models. Comparative analysis also includes ConvNeXt and other CNN architectures, underscoring the benefits of transformer models. Additionally, explainable AI techniques like GradCAM and SHAP provide global heatmaps and pixel-level correlation plots, offering detailed insights into disease localization. These complementary approaches enhance model transparency and support clinical correlations, assisting dermatologists in accurate diagnosis and treatment planning. This combination of high performance and clinical relevance highlights the potential of transformers, particularly DinoV2, in dermatological applications.

Proposed Pipeline:

<img width="888" alt="image" src="https://github.com/user-attachments/assets/667114c9-fa98-4e21-b7b1-c7a05fa0a13e">

Interpretability:

<img width="549" alt="image" src="https://github.com/user-attachments/assets/3d1ef778-7527-4c93-9eb9-33e1b614dd5c">

Demo (Models uploaded to HuggingFace):

ViT-Base: https://huggingface.co/Jayanth2002/vit_base_patch16_224-finetuned-SkinDisease
Swin-Base: https://huggingface.co/Jayanth2002/swin-base-patch4-window7-224-rawdata-finetuned-SkinDisease
DinoV2-Base: https://huggingface.co/Jayanth2002/dinov2-base-finetuned-SkinDisease

If you use this work, kindly cite:

@article{mohan2024enhancing,
  title={Enhancing skin disease classification leveraging transformer-based deep learning architectures and explainable ai},
  author={Mohan, Jayanth and Sivasubramanian, Arrun and Sowmya, V and Vinayakumar, Ravi},
  journal={arXiv preprint arXiv:2407.14757},
  year={2024}
}
