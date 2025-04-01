# watermark Paper List
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/liwd190019/Awesome-Diffusion-Model-Watermark/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

**Class:** watermark

# Table of Contents

- [2025](#2025)
- [2024](#2024)
- [2023](#2023)
- [2022](#2022)
- [2021](#2021)

## 2025

- **Title:** [Image Watermarks are Removable Using Controllable Regeneration from Clean Noise](https://arxiv.org/abs/2410.05470)
  - **Authors:** Yepeng Liu, Yiren Song, Hai Ci, Yu Zhang, Haofan Wang, Mike Zheng Shou, Yuheng Bu
  - <details>
    <summary>Abstract</summary>

    Image watermark techniques provide an effective way to assert ownership, deter misuse, and trace content sources, which has become increasingly essential in the era of large generative models. A critical attribute of watermark techniques is their robustness against various manipulations. In this paper, we introduce a watermark removal approach capable of effectively nullifying state-of-the-art watermarking techniques. Our primary insight involves regenerating the watermarked image starting from a clean Gaussian noise via a controllable diffusion model, utilizing the extracted semantic and spatial features from the watermarked image. The semantic control adapter and the spatial control network are specifically trained to control the denoising process towards ensuring image quality and enhancing consistency between the cleaned image and the original watermarked image. To achieve a smooth trade-off between watermark removal performance and image consistency, we further propose an adjustable and controllable regeneration scheme. This scheme adds varying numbers of noise steps to the latent representation of the watermarked image, followed by a controlled denoising process starting from this noisy latent representation. As the number of noise steps increases, the latent representation progressively approaches clean Gaussian noise, facilitating the desired trade-off. We apply our watermark removal methods across various watermarking techniques, and the results demonstrate that our methods offer superior visual consistency/quality and enhanced watermark removal performance compared to existing regeneration approaches. Our code is available at this https URL.

  </details>

  - **Comments:** ICLR2025
  - **Subjects:** Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [SWA-LDM: Toward Stealthy Watermarks for Latent Diffusion Models](https://arxiv.org/abs/2502.10495)
  - **Authors:** Zhonghao Yang, Linye Lyu, Xuanhang Chang, Daojing He, YU LI
  - <details>
    <summary>Abstract</summary>

    In the rapidly evolving landscape of image generation, Latent Diffusion Models (LDMs) have emerged as powerful tools, enabling the creation of highly realistic images. However, this advancement raises significant concerns regarding copyright infringement and the potential misuse of generated content. Current watermarking techniques employed in LDMs often embed constant signals to the generated images that compromise their stealthiness, making them vulnerable to detection by malicious attackers. In this paper, we introduce SWA-LDM, a novel approach that enhances watermarking by randomizing the embedding process, effectively eliminating detectable patterns while preserving image quality and robustness. Our proposed watermark presence attack reveals the inherent vulnerabilities of existing latent-based watermarking methods, demonstrating how easily these can be exposed. Through comprehensive experiments, we validate that SWA-LDM not only fortifies watermark stealthiness but also maintains competitive performance in watermark robustness and visual fidelity. This work represents a pivotal step towards securing LDM-generated images against unauthorized use, ensuring both copyright protection and content integrity in an era where digital image authenticity is paramount.

  </details>

  - **Comments:** 13 pages, 5 figures
  - **Subjects:** Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV); Machine Learning (cs.LG)

- **Title:** [CogMorph: Cognitive Morphing Attacks for Text-to-Image Models](https://arxiv.org/abs/2501.11815v2)
  - **Authors:** Zonglei Jing, Zonghao Ying, Le Wang, Siyuan Liang, Aishan Liu, Xianglong Liu, Dacheng Tao
  - <details>
    <summary>Abstract</summary>

    The development of text-to-image (T2I) generative models, that enable the creation of high-quality synthetic images from textual prompts, has opened new frontiers in creative design and content generation. However, this paper reveals a significant and previously unrecognized ethical risk inherent in this technology and introduces a novel method, termed the Cognitive Morphing Attack (CogMorph), which manipulates T2I models to generate images that retain the original core subjects but embeds toxic or harmful contextual elements. This nuanced manipulation exploits the cognitive principle that human perception of concepts is shaped by the entire visual scene and its context, producing images that amplify emotional harm far beyond attacks that merely preserve the original semantics. To address this, we first construct an imagery toxicity taxonomy spanning 10 major and 48 sub-categories, aligned with human cognitive-perceptual dimensions, and further build a toxicity risk matrix resulting in 1,176 high-quality T2I toxic prompts. Based on this, our CogMorph first introduces Cognitive Toxicity Augmentation, which develops a cognitive toxicity knowledge base with rich external toxic representations for humans (e.g., fine-grained visual features) that can be utilized to further guide the optimization of adversarial prompts. In addition, we present Contextual Hierarchical Morphing, which hierarchically extracts critical parts of the original prompt (e.g., scenes, subjects, and body parts), and then iteratively retrieves and fuses toxic features to inject harmful contexts. Extensive experiments on multiple open-sourced T2I models and black-box commercial APIs (e.g., DALLE-3) demonstrate the efficacy of CogMorph which significantly outperforms other baselines by large margins (+20.62% on average).

  </details>

  - **Comments:** N/A
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [On the Coexistence and Ensembling of Watermarks](https://arxiv.org/abs/2501.17356)
  - **Authors:** Aleksandar Petrov, Shruti Agarwal, Philip H.S. Torr, Adel Bibi, John Collomosse
  - <details>
    <summary>Abstract</summary>

    Watermarking, the practice of embedding imperceptible information into media such as images, videos, audio, and text, is essential for intellectual property protection, content provenance and attribution. The growing complexity of digital ecosystems necessitates watermarks for different uses to be embedded in the same media. However, to detect and decode all watermarks, they need to coexist well with one another. We perform the first study of coexistence of deep image watermarking methods and, contrary to intuition, we find that various open-source watermarks can coexist with only minor impacts on image quality and decoding robustness. The coexistence of watermarks also opens the avenue for ensembling watermarking methods. We show how ensembling can increase the overall message capacity and enable new trade-offs between capacity, accuracy, robustness and image quality, without needing to retrain the base models.

  </details>

  - **Comments:** N/A
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI); Computers and Society (cs.CY)

- **Title:** [An Undetectable Watermark for Generative Image Models](https://arxiv.org/abs/2410.07369)
  - **Authors:** Sam Gunn, Xuandong Zhao, Dawn Song
  - <details>
    <summary>Abstract</summary>

    We present the first undetectable watermarking scheme for generative image models. Undetectability ensures that no efficient adversary can distinguish between watermarked and un-watermarked images, even after making many adaptive queries. In particular, an undetectable watermark does not degrade image quality under any efficiently computable metric. Our scheme works by selecting the initial latents of a diffusion model using a pseudorandom error-correcting code (Christ and Gunn, 2024), a strategy which guarantees undetectability and robustness. We experimentally demonstrate that our watermarks are quality-preserving and robust using Stable Diffusion 2.1. Our experiments verify that, in contrast to every prior scheme we tested, our watermark does not degrade image quality. Our experiments also demonstrate robustness: existing watermark removal attacks fail to remove our watermark from images without significantly degrading the quality of the images. Finally, we find that we can robustly encode 512 bits in our watermark, and up to 2500 bits when the images are not subjected to watermark removal attacks. Our code is available at this https URL.

  </details>

  - **Comments:** ICLR 2025
  - **Subjects:** Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG); Multimedia (cs.MM)

## 2024

- **Title:** [RingID: Rethinking Tree-Ring Watermarking for Enhanced Multi-Key Identification](https://arxiv.org/abs/2404.14055)
  - **Authors:** Hai Ci, Pei Yang, Yiren Song, Mike Zheng Shou
  - <details>
    <summary>Abstract</summary>

    We revisit Tree-Ring Watermarking, a recent diffusion model watermarking method that demonstrates great robustness to various attacks. We conduct an in-depth study on it and reveal that the distribution shift unintentionally introduced by the watermarking process, apart from watermark pattern matching, contributes to its exceptional robustness. Our investigation further exposes inherent flaws in its original design, particularly in its ability to identify multiple distinct keys, where distribution shift offers no assistance. Based on these findings and analysis, we present RingID for enhanced multi-key identification. It consists of a novel multi-channel heterogeneous watermarking approach designed to seamlessly amalgamate distinctive advantages from diverse watermarks. Coupled with a series of suggested enhancements, RingID exhibits substantial advancements in multi-key identification. Github Page: this https URL

  </details>

  - **Comments:** 27 pages, 9 figures
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [Gaussian Shading: Provable Performance-Lossless Image Watermarking for Diffusion Models](https://arxiv.org/abs/2404.04956)
  - **Authors:** Zijin Yang, Kai Zeng, Kejiang Chen, Han Fang, Weiming Zhang, Nenghai Yu
  - <details>
    <summary>Abstract</summary>

    Ethical concerns surrounding copyright protection and inappropriate content generation pose challenges for the practical implementation of diffusion models. One effective solution involves watermarking the generated images. However, existing methods often compromise the model performance or require additional training, which is undesirable for operators and users. To address this issue, we propose Gaussian Shading, a diffusion model watermarking technique that is both performance-lossless and training-free, while serving the dual purpose of copyright protection and tracing of offending content. Our watermark embedding is free of model parameter modifications and thus is plug-and-play. We map the watermark to latent representations following a standard Gaussian distribution, which is indistinguishable from latent representations obtained from the non-watermarked diffusion model. Therefore we can achieve watermark embedding with lossless performance, for which we also provide theoretical proof. Furthermore, since the watermark is intricately linked with image semantics, it exhibits resilience to lossy processing and erasure attempts. The watermark can be extracted by Denoising Diffusion Implicit Models (DDIM) inversion and inverse sampling. We evaluate Gaussian Shading on multiple versions of Stable Diffusion, and the results demonstrate that Gaussian Shading not only is performance-lossless but also outperforms existing methods in terms of robustness.

  </details>

  - **Comments:** 17 pages, 11 figures, accepted by CVPR 2024
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)

- **Title:** [Attack-Resilient Image Watermarking Using Stable Diffusion](https://arxiv.org/abs/2401.04247)
  - **Authors:** Lijun Zhang, Xiao Liu, Antoni Viros Martin, Cindy Xiong Bearfield, Yuriy Brun, Hui Guan
  - <details>
    <summary>Abstract</summary>

    Watermarking images is critical for tracking image provenance and proving ownership. With the advent of generative models, such as stable diffusion, that can create fake but realistic images, watermarking has become particularly important to make human-created images reliably identifiable. Unfortunately, the very same stable diffusion technology can remove watermarks injected using existing methods. To address this problem, we present ZoDiac, which uses a pre-trained stable diffusion model to inject a watermark into the trainable latent space, resulting in watermarks that can be reliably detected in the latent vector even when attacked. We evaluate ZoDiac on three benchmarks, MS-COCO, DiffusionDB, and WikiArt, and find that ZoDiac is robust against state-of-the-art watermark attacks, with a watermark detection rate above 98% and a false positive rate below 6.4%, outperforming state-of-the-art watermarking methods. We hypothesize that the reciprocating denoising process in diffusion models may inherently enhance the robustness of the watermark when faced with strong attacks and validate the hypothesis. Our research demonstrates that stable diffusion is a promising approach to robust watermarking, able to withstand even stable-diffusion--based attack methods. ZoDiac is open-sourced and available at this https URL.

  </details>

  - **Comments:** 28 pages, 11 figures; NeurIPS24
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)
 
- **Title:** [Shallow Diffuse: Robust and Invisible Watermarking through Low-Dimensional Subspaces in Diffusion Models](https://arxiv.org/abs/2410.21088)
  - **Authors:** Wenda Li, Huijie Zhang, Qing Qu
  - <details>
    <summary>Abstract</summary>

    The widespread use of AI-generated content from diffusion models has raised significant concerns regarding misinformation and copyright infringement. Watermarking is a crucial technique for identifying these AI-generated images and preventing their misuse. In this paper, we introduce Shallow Diffuse, a new watermarking technique that embeds robust and invisible watermarks into diffusion model outputs. Unlike existing approaches that integrate watermarking throughout the entire diffusion sampling process, Shallow Diffuse decouples these steps by leveraging the presence of a low-dimensional subspace in the image generation process. This method ensures that a substantial portion of the watermark lies in the null space of this subspace, effectively separating it from the image generation process. Our theoretical and empirical analyses show that this decoupling strategy greatly enhances the consistency of data generation and the detectability of the watermark. Extensive experiments further validate that our Shallow Diffuse outperforms existing watermarking methods in terms of robustness and consistency. The codes will be released at this https URL.

  </details>

  - **Comments:** N/A
  - **Subjects:** Machine Learning (cs.LG); Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [Leveraging Optimization for Adaptive Attacks on Image Watermarks](https://arxiv.org/abs/2309.16952)
  - **Authors:** Nils Lukas, Abdulrahman Diaa, Lucas Fenaux, Florian Kerschbaum
  - <details>
    <summary>Abstract</summary>

    Untrustworthy users can misuse image generators to synthesize high-quality deepfakes and engage in unethical activities. Watermarking deters misuse by marking generated content with a hidden message, enabling its detection using a secret watermarking key. A core security property of watermarking is robustness, which states that an attacker can only evade detection by substantially degrading image quality. Assessing robustness requires designing an adaptive attack for the specific watermarking algorithm. When evaluating watermarking algorithms and their (adaptive) attacks, it is challenging to determine whether an adaptive attack is optimal, i.e., the best possible attack. We solve this problem by defining an objective function and then approach adaptive attacks as an optimization problem. The core idea of our adaptive attacks is to replicate secret watermarking keys locally by creating surrogate keys that are differentiable and can be used to optimize the attack's parameters. We demonstrate for Stable Diffusion models that such an attacker can break all five surveyed watermarking methods at no visible degradation in image quality. Optimizing our attacks is efficient and requires less than 1 GPU hour to reduce the detection accuracy to 6.3% or less. Our findings emphasize the need for more rigorous robustness testing against adaptive, learnable attackers.

  </details>

  - **Comments:** ICLR'24
  - **Subjects:** Cryptography and Security (cs.CR); Machine Learning (cs.LG)

- **Title:** [SoK: Watermarking for AI-Generated Content](https://arxiv.org/abs/2411.18479)
  - **Authors:** Xuandong Zhao, Sam Gunn, Miranda Christ, Jaiden Fairoze, Andres Fabrega, Nicholas Carlini, Sanjam Garg, Sanghyun Hong, Milad Nasr, Florian Tramer, Somesh Jha, Lei Li, Yu-Xiang Wang, Dawn Song
  - <details>
    <summary>Abstract</summary>

    As the outputs of generative AI (GenAI) techniques improve in quality, it becomes increasingly challenging to distinguish them from human-created content. Watermarking schemes are a promising approach to address the problem of distinguishing between AI and human-generated content. These schemes embed hidden signals within AI-generated content to enable reliable detection. While watermarking is not a silver bullet for addressing all risks associated with GenAI, it can play a crucial role in enhancing AI safety and trustworthiness by combating misinformation and deception. This paper presents a comprehensive overview of watermarking techniques for GenAI, beginning with the need for watermarking from historical and regulatory perspectives. We formalize the definitions and desired properties of watermarking schemes and examine the key objectives and threat models for existing approaches. Practical evaluation strategies are also explored, providing insights into the development of robust watermarking techniques capable of resisting various attacks. Additionally, we review recent representative works, highlight open challenges, and discuss potential directions for this emerging field. By offering a thorough understanding of watermarking in GenAI, this work aims to guide researchers in advancing watermarking methods and applications, and support policymakers in addressing the broader implications of GenAI.

  </details>

  - **Comments:** N/A
  - **Subjects:** Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Machine Learning (cs.LG)

- **Title:** [Safe-SD: Safe and Traceable Stable Diffusion with Text Prompt Trigger for Invisible Generative Watermarking](https://arxiv.org/abs/2407.13188)
  - **Authors:** Zhiyuan Ma, Guoli Jia, Biqing Qi, Bowen Zhou
  - <details>
    <summary>Abstract</summary>

    Recently, stable diffusion (SD) models have typically flourished in the field of image synthesis and personalized editing, with a range of photorealistic and unprecedented images being successfully generated. As a result, widespread interest has been ignited to develop and use various SD-based tools for visual content creation. However, the exposure of AI-created content on public platforms could raise both legal and ethical risks. In this regard, the traditional methods of adding watermarks to the already generated images (i.e. post-processing) may face a dilemma (e.g., being erased or modified) in terms of copyright protection and content monitoring, since the powerful image inversion and text-to-image editing techniques have been widely explored in SD-based methods. In this work, we propose a Safe and high-traceable Stable Diffusion framework (namely Safe-SD) to adaptively implant the graphical watermarks (e.g., QR code) into the imperceptible structure-related pixels during the generative diffusion process for supporting text-driven invisible watermarking and detection. Different from the previous high-cost injection-then-detection training framework, we design a simple and unified architecture, which makes it possible to simultaneously train watermark injection and detection in a single network, greatly improving the efficiency and convenience of use. Moreover, to further support text-driven generative watermarking and deeply explore its robustness and high-traceability, we elaborately design lambda sampling and encryption algorithm to fine-tune a latent diffuser wrapped by a VAE for balancing high-fidelity image synthesis and high-traceable watermark detection. We present our quantitative and qualitative results on two representative datasets LSUN, COCO and FFHQ, demonstrating state-of-the-art performance of Safe-SD and showing it significantly outperforms the previous approaches.

  </details>

  - **Comments:** N/A
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [Watermark Anything with Localized Messages](https://arxiv.org/abs/2411.07231)
  - **Authors:** Tom Sander, Pierre Fernandez, Alain Durmus, Teddy Furon, Matthijs Douze
  - <details>
    <summary>Abstract</summary>

    Image watermarking methods are not tailored to handle small watermarked areas. This restricts applications in real-world scenarios where parts of the image may come from different sources or have been edited. We introduce a deep-learning model for localized image watermarking, dubbed the Watermark Anything Model (WAM). The WAM embedder imperceptibly modifies the input image, while the extractor segments the received image into watermarked and non-watermarked areas and recovers one or several hidden messages from the areas found to be watermarked. The models are jointly trained at low resolution and without perceptual constraints, then post-trained for imperceptibility and multiple watermarks. Experiments show that WAM is competitive with state-of-the art methods in terms of imperceptibility and robustness, especially against inpainting and splicing, even on high-resolution images. Moreover, it offers new capabilities: WAM can locate watermarked areas in spliced images and extract distinct 32-bit messages with less than 1 bit error from multiple small regions - no larger than 10% of the image surface - even for small $256\times 256$ images.

  </details>

  - **Comments:** Under review. Code at this https URL
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR)

- **Title:** [GROOT: Generating Robust Watermark for Diffusion-Model-Based Audio Synthesis](https://arxiv.org/abs/2407.10471)
  - **Authors:** Weizhi Liu, Yue Li, Dongdong Lin, Hui Tian, Haizhou Li
  - <details>
    <summary>Abstract</summary>

    Amid the burgeoning development of generative models like diffusion models, the task of differentiating synthesized audio from its natural counterpart grows more daunting. Deepfake detection offers a viable solution to combat this challenge. Yet, this defensive measure unintentionally fuels the continued refinement of generative models. Watermarking emerges as a proactive and sustainable tactic, preemptively regulating the creation and dissemination of synthesized content. Thus, this paper, as a pioneer, proposes the generative robust audio watermarking method (Groot), presenting a paradigm for proactively supervising the synthesized audio and its source diffusion models. In this paradigm, the processes of watermark generation and audio synthesis occur simultaneously, facilitated by parameter-fixed diffusion models equipped with a dedicated encoder. The watermark embedded within the audio can subsequently be retrieved by a lightweight decoder. The experimental results highlight Groot's outstanding performance, particularly in terms of robustness, surpassing that of the leading state-of-the-art methods. Beyond its impressive resilience against individual post-processing attacks, Groot exhibits exceptional robustness when facing compound attacks, maintaining an average watermark extraction accuracy of around 95%.

  </details>

  - **Comments:** Accepted by ACM MM 2024
  - **Subjects:** Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Sound (cs.SD); Audio and Speech Processing (eess.AS)

- **Title:** [Invisible Image Watermarks Are Provably Removable Using Generative AI](https://arxiv.org/abs/2306.01953)
  - **Authors:** Xuandong Zhao, Kexun Zhang, Zihao Su, Saastha Vasan, Ilya Grishchenko, Christopher Kruegel, Giovanni Vigna, Yu-Xiang Wang, Lei Li
  - <details>
    <summary>Abstract</summary>

    Invisible watermarks safeguard images' copyrights by embedding hidden messages only detectable by owners. They also prevent people from misusing images, especially those generated by AI models. We propose a family of regeneration attacks to remove these invisible watermarks. The proposed attack method first adds random noise to an image to destroy the watermark and then reconstructs the image. This approach is flexible and can be instantiated with many existing image-denoising algorithms and pre-trained generative models such as diffusion models. Through formal proofs and extensive empirical evaluations, we demonstrate that pixel-level invisible watermarks are vulnerable to this regeneration attack. Our results reveal that, across four different pixel-level watermarking schemes, the proposed method consistently achieves superior performance compared to existing attack techniques, with lower detection rates and higher image quality. However, watermarks that keep the image semantically similar can be an alternative defense against our attacks. Our finding underscores the need for a shift in research/industry emphasis from invisible watermarks to semantic-preserving watermarks. Code is available at this https URL

  </details>

  - **Comments:** NeurIPS 2024
  - **Subjects:** Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [WAVES: Benchmarking the Robustness of Image Watermarks](https://arxiv.org/abs/2401.08573)
  - **Authors:** Bang An, Mucong Ding, Tahseen Rabbani, Aakriti Agrawal, Yuancheng Xu, Chenghao Deng, Sicheng Zhu, Abdirisak Mohamed, Yuxin Wen, Tom Goldstein, Furong Huang
  - <details>
    <summary>Abstract</summary>

    In the burgeoning age of generative AI, watermarks act as identifiers of provenance and artificial content. We present WAVES (Watermark Analysis Via Enhanced Stress-testing), a benchmark for assessing image watermark robustness, overcoming the limitations of current evaluation methods. WAVES integrates detection and identification tasks and establishes a standardized evaluation protocol comprised of a diverse range of stress tests. The attacks in WAVES range from traditional image distortions to advanced, novel variations of diffusive, and adversarial attacks. Our evaluation examines two pivotal dimensions: the degree of image quality degradation and the efficacy of watermark detection after attacks. Our novel, comprehensive evaluation reveals previously undetected vulnerabilities of several modern watermarking algorithms. We envision WAVES as a toolkit for the future development of robust watermarks. The project is available at this https URL

  </details>

  - **Comments:** Accepted by ICML 2024
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR); Machine Learning (cs.LG)

- **Title:** [Steganalysis on Digital Watermarking: Is Your Defense Truly Impervious?](https://arxiv.org/abs/2406.09026)
  - **Authors:** Pei Yang, Hai Ci, Yiren Song, Mike Zheng Shou
  - <details>
    <summary>Abstract</summary>

    Digital watermarking techniques are crucial for copyright protection and source identification of images, especially in the era of generative AI models. However, many existing watermarking methods, particularly content-agnostic approaches that embed fixed patterns regardless of image content, are vulnerable to steganalysis attacks that can extract and remove the watermark with minimal perceptual distortion. In this work, we categorize watermarking algorithms into content-adaptive and content-agnostic ones, and demonstrate how averaging a collection of watermarked images could reveal the underlying watermark pattern. We then leverage this extracted pattern for effective watermark removal under both graybox and blackbox settings, even when the collection contains multiple watermark patterns. For some algorithms like Tree-Ring watermarks, the extracted pattern can also forge convincing watermarks on clean images. Our quantitative and qualitative evaluations across twelve watermarking methods highlight the threat posed by steganalysis to content-agnostic watermarks and the importance of designing watermarking techniques resilient to such analytical attacks. We propose security guidelines calling for using content-adaptive watermarking strategies and performing security evaluation against steganalysis. We also suggest multi-key assignments as potential mitigations against steganalysis vulnerabilities.

  </details>

  - **Comments:** N/A
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [The Efficacy of Transfer-based No-box Attacks on Image Watermarking: A Pragmatic Analysis](https://arxiv.org/abs/2412.02576)
  - **Authors:** Qilong Wu, Varun Chandrasekaran
  - <details>
    <summary>Abstract</summary>

    Watermarking approaches are widely used to identify if images being circulated are authentic or AI-generated. Determining the robustness of image watermarking methods in the ``no-box'' setting, where the attacker is assumed to have no knowledge about the watermarking model, is an interesting problem. Our main finding is that evading the no-box setting is challenging: the success of optimization-based transfer attacks (involving training surrogate models) proposed in prior work~\cite{hu2024transfer} depends on impractical assumptions, including (i) aligning the architecture and training configurations of both the victim and attacker's surrogate watermarking models, as well as (ii) a large number of surrogate models with potentially large computational requirements. Relaxing these assumptions i.e., moving to a more pragmatic threat model results in a failed attack, with an evasion rate at most $21.1\%$. We show that when the configuration is mostly aligned, a simple non-optimization attack we propose, OFT, with one single surrogate model can already exceed the success of optimization-based efforts. Under the same $\ell_\infty$ norm perturbation budget of $0.25$, prior work~\citet{hu2024transfer} is comparable to or worse than OFT in $11$ out of $12$ configurations and has a limited advantage on the remaining one. The code used for all our experiments is available at \url{this https URL}.

  </details>

  - **Comments:** We find that the success of existing transfer-based attacks in evading image watermarking in the no-box setting depends on unrealistic assumptions and find a much more inexpensive optimization-free alternative
  - **Subjects:** Cryptography and Security (cs.CR)

## 2023

- **Title:** [Tree-Ring Watermarks: Fingerprints for Diffusion Images that are Invisible and Robust](https://arxiv.org/abs/2305.20030)
  - **Authors:** Yuxin Wen, John Kirchenbauer, Jonas Geiping, Tom Goldstein
  - <details>
    <summary>Abstract</summary>

    Watermarking the outputs of generative models is a crucial technique for tracing copyright and preventing potential harm from AI-generated content. In this paper, we introduce a novel technique called Tree-Ring Watermarking that robustly fingerprints diffusion model outputs. Unlike existing methods that perform post-hoc modifications to images after sampling, Tree-Ring Watermarking subtly influences the entire sampling process, resulting in a model fingerprint that is invisible to humans. The watermark embeds a pattern into the initial noise vector used for sampling. These patterns are structured in Fourier space so that they are invariant to convolutions, crops, dilations, flips, and rotations. After image generation, the watermark signal is detected by inverting the diffusion process to retrieve the noise vector, which is then checked for the embedded signal. We demonstrate that this technique can be easily applied to arbitrary diffusion models, including text-conditioned Stable Diffusion, as a plug-in with negligible loss in FID. Our watermark is semantically hidden in the image space and is far more robust than watermarking alternatives that are currently deployed. Code is available at this https URL.

  </details>

  - **Comments:** 16 pages, 8 figures, code is available at this https URL, fixed the repo link
  - **Subjects:** Machine Learning (cs.LG); Cryptography and Security (cs.CR); Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [TrustMark: Universal Watermarking for Arbitrary Resolution Images](https://arxiv.org/abs/2311.18297)
  - **Authors:** Tu Bui, Shruti Agarwal, John Collomosse
  - <details>
    <summary>Abstract</summary>

    Imperceptible digital watermarking is important in copyright protection, misinformation prevention, and responsible generative AI. We propose TrustMark - a GAN-based watermarking method with novel design in architecture and spatio-spectra losses to balance the trade-off between watermarked image quality with the watermark recovery accuracy. Our model is trained with robustness in mind, withstanding various in- and out-place perturbations on the encoded image. Additionally, we introduce TrustMark-RM - a watermark remover method useful for re-watermarking. Our methods achieve state-of-art performance on 3 benchmarks comprising arbitrary resolution images.

  </details>

  - **Comments:** N/A
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)

- **Title:** [A Recipe for Watermarking Diffusion Models](https://arxiv.org/abs/2303.10137)
  - **Authors:** Yunqing Zhao, Tianyu Pang, Chao Du, Xiao Yang, Ngai-Man Cheung, Min Lin
  - <details>
    <summary>Abstract</summary>

    Diffusion models (DMs) have demonstrated advantageous potential on generative tasks. Widespread interest exists in incorporating DMs into downstream applications, such as producing or editing photorealistic images. However, practical deployment and unprecedented power of DMs raise legal issues, including copyright protection and monitoring of generated content. In this regard, watermarking has been a proven solution for copyright protection and content monitoring, but it is underexplored in the DMs literature. Specifically, DMs generate samples from longer tracks and may have newly designed multimodal structures, necessitating the modification of conventional watermarking pipelines. To this end, we conduct comprehensive analyses and derive a recipe for efficiently watermarking state-of-the-art DMs (e.g., Stable Diffusion), via training from scratch or finetuning. Our recipe is straightforward but involves empirically ablated implementation details, providing a foundation for future research on watermarking DMs. The code is available at this https URL.

  </details>

  - **Comments:** N/A
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Cryptography and Security (cs.CR); Machine Learning (cs.LG)

- **Title:** [The Stable Signature: Rooting Watermarks in Latent Diffusion Models](https://arxiv.org/abs/2303.15435)
  - **Authors:** Pierre Fernandez, Guillaume Couairon, Hervé Jégou, Matthijs Douze, Teddy Furon
  - <details>
    <summary>Abstract</summary>

    Generative image modeling enables a wide range of applications but raises ethical concerns about responsible deployment. This paper introduces an active strategy combining image watermarking and Latent Diffusion Models. The goal is for all generated images to conceal an invisible watermark allowing for future detection and/or identification. The method quickly fine-tunes the latent decoder of the image generator, conditioned on a binary signature. A pre-trained watermark extractor recovers the hidden signature from any generated image and a statistical test then determines whether it comes from the generative model. We evaluate the invisibility and robustness of the watermarks on a variety of generation tasks, showing that Stable Signature works even after the images are modified. For instance, it detects the origin of an image generated from a text prompt, then cropped to keep $10\%$ of the content, with $90$+$\%$ accuracy at a false positive rate below 10$^{-6}$.

  </details>

  - **Comments:** Published at ICCV 2023. Code at this https URL - webpage at this https URL
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)

- **Title:** [Watermarking Diffusion Model](https://arxiv.org/abs/2305.12502)
  - **Authors:** Yugeng Liu, Zheng Li, Michael Backes, Yun Shen, Yang Zhang
  - <details>
    <summary>Abstract</summary>

    The availability and accessibility of diffusion models (DMs) have significantly increased in recent years, making them a popular tool for analyzing and predicting the spread of information, behaviors, or phenomena through a population. Particularly, text-to-image diffusion models (e.g., DALLE 2 and Latent Diffusion Models (LDMs) have gained significant attention in recent years for their ability to generate high-quality images and perform various image synthesis tasks. Despite their widespread adoption in many fields, DMs are often susceptible to various intellectual property violations. These can include not only copyright infringement but also more subtle forms of misappropriation, such as unauthorized use or modification of the model. Therefore, DM owners must be aware of these potential risks and take appropriate steps to protect their models. In this work, we are the first to protect the intellectual property of DMs. We propose a simple but effective watermarking scheme that injects the watermark into the DMs and can be verified by the pre-defined prompts. In particular, we propose two different watermarking methods, namely NAIVEWM and FIXEDWM. The NAIVEWM method injects the watermark into the LDMs and activates it using a prompt containing the watermark. On the other hand, the FIXEDWM is considered more advanced and stealthy compared to the NAIVEWM, as it can only activate the watermark when using a prompt containing a trigger in a fixed position. We conducted a rigorous evaluation of both approaches, demonstrating their effectiveness in watermark injection and verification with minimal impact on the LDM's functionality.

  </details>

  - **Comments:** N/A
  - **Subjects:** Cryptography and Security (cs.CR)

- **Title:** [RoSteALS: Robust Steganography using Autoencoder Latent Space](https://arxiv.org/abs/2304.03400)
  - **Authors:** Tu Bui, Shruti Agarwal, Ning Yu, John Collomosse
  - <details>
    <summary>Abstract</summary>

    Data hiding such as steganography and invisible watermarking has important applications in copyright protection, privacy-preserved communication and content provenance. Existing works often fall short in either preserving image quality, or robustness against perturbations or are too complex to train. We propose RoSteALS, a practical steganography technique leveraging frozen pretrained autoencoders to free the payload embedding from learning the distribution of cover images. RoSteALS has a light-weight secret encoder of just 300k parameters, is easy to train, has perfect secret recovery performance and comparable image quality on three benchmarks. Additionally, RoSteALS can be adapted for novel cover-less steganography applications in which the cover image can be sampled from noise or conditioned on text prompts via a denoising diffusion process. Our model and code are available at \url{this https URL}.

  </details>

  - **Comments:** accepted to CVPR WMF 2023
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV)

- **Title:** [Intellectual Property Protection of Diffusion Models via the Watermark Diffusion Process](https://arxiv.org/abs/2306.03436)
  - **Authors:** Sen Peng, Yufei Chen, Cong Wang, Xiaohua Jia
  - <details>
    <summary>Abstract</summary>

    Diffusion models have rapidly become a vital part of deep generative architectures, given today's increasing demands. Obtaining large, high-performance diffusion models demands significant resources, highlighting their importance as intellectual property worth protecting. However, existing watermarking techniques for ownership verification are insufficient when applied to diffusion models. Very recent research in watermarking diffusion models either exposes watermarks during task generation, which harms the imperceptibility, or is developed for conditional diffusion models that require prompts to trigger the watermark. This paper introduces WDM, a novel watermarking solution for diffusion models without imprinting the watermark during task generation. It involves training a model to concurrently learn a Watermark Diffusion Process (WDP) for embedding watermarks alongside the standard diffusion process for task generation. We provide a detailed theoretical analysis of WDP training and sampling, relating it to a shifted Gaussian diffusion process via the same reverse noise. Extensive experiments are conducted to validate the effectiveness and robustness of our approach in various trigger and watermark data configurations.

  </details>

  - **Comments:** N/A
  - **Subjects:** Cryptography and Security (cs.CR); Machine Learning (cs.LG)

## 2022

- **Title:** [Supervised GAN Watermarking for Intellectual Property Protection](https://arxiv.org/abs/2209.03466)
  - **Authors:** Jianwei Fei, Zhihua Xia, Benedetta Tondi, Mauro Barni
  - <details>
    <summary>Abstract</summary>

    We propose a watermarking method for protecting the Intellectual Property (IP) of Generative Adversarial Networks (GANs). The aim is to watermark the GAN model so that any image generated by the GAN contains an invisible watermark (signature), whose presence inside the image can be checked at a later stage for ownership verification. To achieve this goal, a pre-trained CNN watermarking decoding block is inserted at the output of the generator. The generator loss is then modified by including a watermark loss term, to ensure that the prescribed watermark can be extracted from the generated images. The watermark is embedded via fine-tuning, with reduced time complexity. Results show that our method can effectively embed an invisible watermark inside the generated images. Moreover, our method is a general one and can work with different GAN architectures, different tasks, and different resolutions of the output image. We also demonstrate the good robustness performance of the embedded watermark against several post-processing, among them, JPEG compression, noise addition, blurring, and color transformations.

  </details>

  - **Comments:** N/A
  - **Subjects:** Computer Vision and Pattern Recognition (cs.CV); Artificial Intelligence (cs.AI)

## 2021

- **Title:** [Protecting Intellectual Property of Generative Adversarial Networks from Ambiguity Attack](https://arxiv.org/abs/2102.04362)
  - **Authors:** Ding Sheng Ong, Chee Seng Chan, Kam Woh Ng, Lixin Fan, Qiang Yang
  - <details>
    <summary>Abstract</summary>

    Ever since Machine Learning as a Service (MLaaS) emerges as a viable business that utilizes deep learning models to generate lucrative revenue, Intellectual Property Right (IPR) has become a major concern because these deep learning models can easily be replicated, shared, and re-distributed by any unauthorized third parties. To the best of our knowledge, one of the prominent deep learning models - Generative Adversarial Networks (GANs) which has been widely used to create photorealistic image are totally unprotected despite the existence of pioneering IPR protection methodology for Convolutional Neural Networks (CNNs). This paper therefore presents a complete protection framework in both black-box and white-box settings to enforce IPR protection on GANs. Empirically, we show that the proposed method does not compromise the original GANs performance (i.e. image generation, image super-resolution, style transfer), and at the same time, it is able to withstand both removal and ambiguity attacks against embedded watermarks.

  </details>

  - **Comments:** Accepted at CVPR2021
  - **Subjects:** Cryptography and Security (cs.CR); Artificial Intelligence (cs.AI); Computer Vision and Pattern Recognition (cs.CV)

