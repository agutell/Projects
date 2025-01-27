# Projects
## [Re] Diffusion Posterior Sampling for Noisy Inverse Problems
This paper aims to reproduce the experiments presented in Chung et al. [2023],
where the authors propose a sampling technique for solving inverse problems with
diffusion models as priors. Our re-implementation successfully reproduces the
results to a satisfactory extent based on the information provided in the original
paper, though with worse FID, LPIPS, SSIM, and PSNR scores compared to the
reported benchmarks. Additionally, we extend the original implementation by
incorporating a fast sampling algorithm for diffusion models, DPM-Solver Lu et al.
[2024]. Further, we conduct several additional experiments, including ablation
studies on mask size for Random and Box Inpainting, and perform an in-depth
statistical analysis of LPIPS scores to better understand the model’s performance
and limitations.

**Code** is available at: [GitHub Repository](https://github.com/KTH-DD2412-Project-Group-18/diffusion_posterior_sampling)

## Contrast to the Past - Autoregressive Contrastive Temporal Knowledge Graph Extrapolation
Graphs are fundamental across various fields, representing complex relationships and structures — such as social
networks, chemical bonds, and even neural networks in machine learning. Knowledge graphs extend this concept to organize real world information into entities and relationships, structuring facts in interconnected ways. However, traditional knowledge graphs lack temporal context, limiting their ability to capture the evolution of information over time. Temporal Knowledge Graphs (TKGs) address this by adding a temporal dimension, enabling dynamic analysis and prediction of future events by tracking how interactions evolve across timestamps. This project seeks to improve the RE-GCN model for extrapolation tasks on TKGs, specifically for predicting events involving unseen entities or relationships. By integrating a contrastive learning framework inspired by the CENET model, our approach enhances RE-GCN’s ability to distinguish historical from non-historical dependencies, which in turn improves predictive accuracy on complex, dynamic datasets. Experimental results on the ICEWS18 dataset demonstrate that our modifications to RE-GCN lead to unchanged accuracy in capturing both historical and non-historical dependencies. These results underscore the complexity of modeling diverse temporal patterns within TKGs and highlight areas for further refinement, such as improved calibration techniques and extensions for uncertainty quantification.

## Explainable Machine Learning in Cardiovascular Diagnostics
Bachelor Thesis at KTH: Explainable Machine Learning in Cardiovascular
Diagnostics
## Transfer Learning - A Deep Learning Approach
The paper explores transfer learning together with pseudo labeling and semi-supervised learning.
## Quantization and Finetuning of LLMs
Quantization and finetuning of Llama-2-7B and Mistral-7B for generation of WikiHow articles.
## TSA on Temperature and Exchange Rate
Project report exploring time series forecasting on data from SMHI and exchange rate between the USD and EUR. 
## Reimplementation of Importance Weighted Autoencoders 
Reimplementation of Y. Burda, R. Grosse, and R. Salakhutdinov. Importance weighted autoencoders
## Active Debris Removal from Space
Evaluation of an active debris removal method. This report explores an early-stage idea of how space debris can be removed more efficiently.
