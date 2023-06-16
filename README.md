# Awesome Personalized Text-to-Image
A collection of papers, datasets, and evaluations for personalized text-to-image generation.

***Content:***

 - [Description](#description)
 - [Papers](#papers)
 - [Quantitative Evaluations](#evaluations)
 - [Datasets](#datasets)

## <span id="description"> *Description* </span>
Personalized text-to-image (P-T2I) generation aims to acquire a new concept from a limited set of reference images and generate target images embodying this novel concept. The ability to generate such images holds significant value for various applications, including image editing, enhancing classifier performance, and bolstering robustness, among others.

This GitHub repository aims to provide the necessary resources for people interested in this line of research.

## <span id="papers"> *Papers* </span>

 - **An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion**, (ICLR'23)
 [\[project\]](https://textual-inversion.github.io) [\[paper\]](https://arxiv.org/abs/2208.01618) [\[code\]](https://github.com/rinongal/textual_inversion) 
 - **DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation**, (CVPR'23) [\[project\]](https://dreambooth.github.io) [\[paper\]](https://arxiv.org/abs/2208.12242) [\[code*\]](https://github.com/huggingface/diffusers/tree/main/examples/dreambooth) 
 - **Multi-Concept Customization of Text-to-Image Diffusion**, (CVPR'23) [\[project\]](https://www.cs.cmu.edu/~custom-diffusion/) [\[paper\]](https://arxiv.org/abs/2212.04488) [\[code\]](https://github.com/adobe-research/custom-diffusion) 
 - **Multiresolution Textual Inversion**, (NeurIPS-W'22) [\[paper\]](https://arxiv.org/abs/2211.17115) [\[code\]](https://github.com/giannisdaras/multires_textual_inversion) 
 - **Encoder-based Domain Tuning for Fast Personalization of Text-to-Image Models**, (arXiv - Feb'23) [\[project\]](https://tuning-encoder.github.io) [\[paper\]](https://arxiv.org/abs/2302.12228) 
 - **ELITE: Encoding Visual Concepts into Textual Embeddings for Customized Text-to-Image Generation**, (arXiv - Feb'23) [\[paper\]](https://arxiv.org/abs/2302.13848) [\[code\]](https://github.com/csyxwei/ELITE) [\[demo\]](https://huggingface.co/spaces/ELITE-library/ELITE) 
 - **Highly Personalized Text Embedding for Image Manipulation by Stable Diffusion**, (arXiv - March'23) [\[project\]](https://hiper0.github.io) [\[paper\]](https://arxiv.org/abs/2303.08767) [\[code\]](https://github.com/HiPer0/HiPer) 
 - **P+: Extended Textual Conditioning in Text-to-Image Generation**, (arXiv - March'23) [\[project\]](https://prompt-plus.github.io) [\[paper\]](https://arxiv.org/abs/2303.09522) 
 - **Cones: Concept neurons in diffusion models for customized generation**, (arXiv - March'23) [\[paper\]](https://arxiv.org/abs/2303.05125) [\[code\]](https://github.com/Johanan528/Cones)
 - **InstantBooth: Personalized Text-to-Image Generation without Test-Time Finetuning**, (arXiv - April'23) [\[project\]](https://jshi31.github.io/InstantBooth/) [\[paper\]](https://arxiv.org/abs/2305.13921)
 - **Enhancing Detail Preservation for Customized Text-to-Image Generation: A Regularization-Free Approach**, (arXiv - May'23) [\[paper\]](https://arxiv.org/abs/2305.13579)
 - **BLIP-Diffusion: Pre-trained Subject Representation for Controllable Text-to-Image Generation and Editing**, (arXiv - May'23) [\[project\]](https://dxli94.github.io/BLIP-Diffusion-website/) [\[paper\]](https://arxiv.org/abs/2305.14720) [\[code\]](https://github.com/salesforce/LAVIS/tree/main/projects/blip-diffusion) 
 - **Break-A-Scene: Extracting Multiple Concepts from a Single Image**, (arXiv - May'23) [\[project\]](https://omriavrahami.com/break-a-scene/) [\[paper\]](https://arxiv.org/abs/2305.16311) 
 - **A Neural Space-Time Representation for Text-to-Image Personalization**, (arXiv - May'23) [\[project\]](https://neuraltextualinversion.github.io/NeTI/) [\[paper\]](https://arxiv.org/abs/2305.15391) [\[code\]](https://github.com/NeuralTextualInversion/NeTI) 
 - **Photoswap: Personalized Subject Swapping in Images**, (arXiv - May'23) [\[project\]](https://photoswap.github.io) [\[paper\]](https://arxiv.org/abs/2305.18286)
 - **Mix-of-Show: Decentralized Low-Rank Adaptation for Multi-Concept Customization of Diffusion Models**, (arXiv - May'23) [\[project\]](https://showlab.github.io/Mix-of-Show/) [\[paper\]](https://arxiv.org/abs/2305.18292) [\[code\]](https://github.com/TencentARC/Mix-of-Show)
 - **Concept Decomposition for Visual Exploration and Inspiration**, (arXiv - May'23) [\[project\]](https://inspirationtree.github.io/inspirationtree/) [\[paper\]](https://arxiv.org/abs/2305.18203)
 - **Inserting Anybody in Diffusion Models via Celeb Basis**, (arXiv - June'23) [\[project\]](https://celeb-basis.github.io) [\[paper\]](https://arxiv.org/abs/2306.00926) [\[code\]](https://github.com/ygtxr1997/CelebBasis)
 - **ViCo: Detail-Preserving Visual Condition for Personalized Text-to-Image Generation**, (arXiv - June'23) [\[paper\]](https://arxiv.org/abs/2306.00971) [\[code\]](https://github.com/haoosz/ViCo)
 - **Face0: Instantaneously Conditioning a Text-to-Image Model on a Face**, (arXiv - June'23) [\[paper\]](https://arxiv.org/abs//2306.06638)
 - **ConceptBed: Evaluating Concept Learning Abilities of Text-to-Image Diffusion Models**, (arXiv - June'23) [\[project\]](https://conceptbed.github.io) [\[paper\]](https://arxiv.org/abs/2306.04695) [\[code\]](https://github.com/ConceptBed/evaluations) [\[demo\]](https://huggingface.co/spaces/mpatel57/ConceptBed) 
 - **Controlling Text-to-Image Diffusion by Orthogonal Finetuning**, (arXiv - June'23) [\[project\]](https://oft.wyliu.com) [\[paper\]](https://arxiv.org/abs/2306.07280) [\[code\]](https://github.com/Zeju1997/oft)

## <span id="evaluations"> *Evaluations* </span>

 - Fréchet Inception Distance (FID) -- For Image Quality [\[Paper\]](https://proceedings.neurips.cc/paper_files/paper/2017/file/8a1d694707eb0fefe65871369074926d-Paper.pdf) [\[Python Code (Pytorch)\]](https://github.com/toshas/torch-fidelity)
 - Kernel Inception Distance (KID) -- For Concept Overfitting [\[Paper\]](https://arxiv.org/pdf/2206.10935.pdf) [\[Python Code (Pytorch)\]](https://github.com/toshas/torch-fidelity)
 - DINO Cosine Similarity -- For Concept Similarity [\[Paper\]](https://arxiv.org/abs/2104.14294) [\[Code\]](https://huggingface.co/facebook/dino-vitb8)
 - CLIPScore -- For Image-Text Alignment [\[Paper\]](https://arxiv.org/abs/2104.08718) [\[Code\]](https://github.com/jmhessel/clipscore)
 - Concept Confidence Deviation (CCD) -- For Concept & Composition Alignment [\[paper\]](https://arxiv.org/abs/2306.04695) [\[code\]](https://github.com/ConceptBed/evaluations)

## <span id="datasets"> *Datasets* </span>

 - Source: DreamBooth [\[Link\]](https://github.com/google/dreambooth)
 - Source: Custom Diffusion [\[Link\]](https://www.cs.cmu.edu/~custom-diffusion/assets/data.zip)
 - Source: ConceptBed [\[Link\]](https://conceptbed.github.io/data.html)

## Contributions
We highly encourage community contributions. Feel free to create either issue or a pull request.
