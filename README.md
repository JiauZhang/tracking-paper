### Scalable Pathogen Detection from Next Generation DNA Sequencing with  Deep Learning
Next-generation sequencing technologies have enhanced the scope of Internet-of-Things (IoT) to include genomics for personalized medicine through the increased availability of an abundance of genome data collected from heterogeneous sources at a reduced cost. Given the sheer magnitude of the collected data and the significant challenges offered by the presence of highly similar genomic structure across species, there is a need for robust, scalable analysis platforms to extract actionable knowledge such as the presence of potentially zoonotic pathogens. The emergence of zoonotic diseases from novel pathogens, such as the influenza virus in 1918 and SARS-CoV-2 in 2019 that can jump species barriers and lead to pandemic underscores the need for scalable metagenome analysis. In this work, we propose MG2Vec, a deep learning-based solution that uses the transformer network as its backbone, to learn robust features from raw metagenome sequences for downstream biomedical tasks such as targeted and generalized pathogen detection. Extensive experiments on four increasingly challenging, yet realistic diagnostic settings, show that the proposed approach can help detect pathogens from uncurated, real-world clinical samples with minimal human supervision in the form of labels. Further, we demonstrate that the learned representations can generalize to completely unrelated pathogens across diseases and species for large-scale metagenome analysis. We provide a comprehensive evaluation of a novel representation learning framework for metagenome-based disease diagnostics with deep learning and provide a way forward for extracting and using robust vector representations from low-cost next generation sequencing to develop generalizable diagnostic tools. 

### Part-based Face Recognition with Vision Transformers
Holistic methods using CNNs and margin-based losses have dominated research on face recognition. In this work, we depart from this setting in two ways: (a) we employ the Vision Transformer as an architecture for training a very strong baseline for face recognition, simply called fViT, which already surpasses most state-of-the-art face recognition methods. (b) Secondly, we capitalize on the Transformer's inherent property to process information (visual tokens) extracted from irregular grids to devise a pipeline for face recognition which is reminiscent of part-based face recognition methods. Our pipeline, called part fViT, simply comprises a lightweight network to predict the coordinates of facial landmarks followed by the Vision Transformer operating on patches extracted from the predicted landmarks, and it is trained end-to-end with no landmark supervision. By learning to extract discriminative patches, our part-based Transformer further boosts the accuracy of our Vision Transformer baseline achieving state-of-the-art accuracy on several face recognition benchmarks. 

### Task-Specific Embeddings for Ante-Hoc Explainable Text Classification
Current state-of-the-art approaches to text classification typically leverage BERT-style Transformer models with a softmax classifier, jointly fine-tuned to predict class labels of a target task. In this paper, we instead propose an alternative training objective in which we learn task-specific embeddings of text: our proposed objective learns embeddings such that all texts that share the same target class label should be close together in the embedding space, while all others should be far apart. This allows us to replace the softmax classifier with a more interpretable k-nearest-neighbor classification approach. In a series of experiments, we show that this yields a number of interesting benefits: (1) The resulting order induced by distances in the embedding space can be used to directly explain classification decisions. (2) This facilitates qualitative inspection of the training data, helping us to better understand the problem space and identify labelling quality issues. (3) The learned distances to some degree generalize to unseen classes, allowing us to incrementally add new classes without retraining the model. We present extensive experiments which show that the benefits of ante-hoc explainability and incremental learning come at no cost in overall classification accuracy, thus pointing to practical applicability of our proposed approach. 

### Denoising Diffusion for Sampling SAT Solutions
Generating diverse solutions to the Boolean Satisfiability Problem (SAT) is a hard computational problem with practical applications for testing and functional verification of software and hardware designs. We explore the way to generate such solutions using Denoising Diffusion coupled with a Graph Neural Network to implement the denoising function. We find that the obtained accuracy is similar to the currently best purely neural method and the produced SAT solutions are highly diverse, even if the system is trained with non-random solutions from a standard solver. 

### Shape-Guided Diffusion with Inside-Outside Attention
Shape can specify key object constraints, yet existing text-to-image diffusion models ignore this cue and synthesize objects that are incorrectly scaled, cut off, or replaced with background content. We propose a training-free method, Shape-Guided Diffusion, which uses a novel Inside-Outside Attention mechanism to constrain the cross-attention (and self-attention) maps such that prompt tokens (and pixels) referring to the inside of the shape cannot attend outside the shape, and vice versa. To demonstrate the efficacy of our method, we propose a new image editing task where the model must replace an object specified by its mask and a text prompt. We curate a new ShapePrompts benchmark based on MS-COCO and achieve SOTA results in shape faithfulness, text alignment, and realism according to both quantitative metrics and human preferences. Our data and code will be made available at https://shape-guided-diffusion.github.io. 

### Learning Progressive Modality-shared Transformers for Effective  Visible-Infrared Person Re-identification
Visible-Infrared Person Re-Identification (VI-ReID) is a challenging retrieval task under complex modality changes. Existing methods usually focus on extracting discriminative visual features while ignoring the reliability and commonality of visual features between different modalities. In this paper, we propose a novel deep learning framework named Progressive Modality-shared Transformer (PMT) for effective VI-ReID. To reduce the negative effect of modality gaps, we first take the gray-scale images as an auxiliary modality and propose a progressive learning strategy. Then, we propose a Modality-Shared Enhancement Loss (MSEL) to guide the model to explore more reliable identity information from modality-shared features. Finally, to cope with the problem of large intra-class differences and small inter-class differences, we propose a Discriminative Center Loss (DCL) combined with the MSEL to further improve the discrimination of reliable features. Extensive experiments on SYSU-MM01 and RegDB datasets show that our proposed framework performs better than most state-of-the-art methods. For model reproduction, we release the source code at https://github.com/hulu88/PMT. 

### VIDM: Video Implicit Diffusion Models
Diffusion models have emerged as a powerful generative method for synthesizing high-quality and diverse set of images. In this paper, we propose a video generation method based on diffusion models, where the effects of motion are modeled in an implicit condition manner, i.e. one can sample plausible video motions according to the latent feature of frames. We improve the quality of the generated videos by proposing multiple strategies such as sampling space truncation, robustness penalty, and positional group normalization. Various experiments are conducted on datasets consisting of videos with different resolutions and different number of frames. Results show that the proposed method outperforms the state-of-the-art generative adversarial network-based methods by a significant margin in terms of FVD scores as well as perceptible visual quality. 

### GRiT: A Generative Region-to-text Transformer for Object Understanding
This paper presents a Generative RegIon-to-Text transformer, GRiT, for object understanding. The spirit of GRiT is to formulate object understanding as <region, text> pairs, where region locates objects and text describes objects. For example, the text in object detection denotes class names while that in dense captioning refers to descriptive sentences. Specifically, GRiT consists of a visual encoder to extract image features, a foreground object extractor to localize objects, and a text decoder to generate open-set object descriptions. With the same model architecture, GRiT can understand objects via not only simple nouns, but also rich descriptive sentences including object attributes or actions. Experimentally, we apply GRiT to object detection and dense captioning tasks. GRiT achieves 60.4 AP on COCO 2017 test-dev for object detection and 15.5 mAP on Visual Genome for dense captioning. Code is available at https://github.com/JialianW/GRiT 

### Concealed Object Detection for Passive Millimeter-Wave Security Imaging  Based on Task-Aligned Detection Transformer
Passive millimeter-wave (PMMW) is a significant potential technique for human security screening. Several popular object detection networks have been used for PMMW images. However, restricted by the low resolution and high noise of PMMW images, PMMW hidden object detection based on deep learning usually suffers from low accuracy and low classification confidence. To tackle the above problems, this paper proposes a Task-Aligned Detection Transformer network, named PMMW-DETR. In the first stage, a Denoising Coarse-to-Fine Transformer (DCFT) backbone is designed to extract long- and short-range features in the different scales. In the second stage, we propose the Query Selection module to introduce learned spatial features into the network as prior knowledge, which enhances the semantic perception capability of the network. In the third stage, aiming to improve the classification performance, we perform a Task-Aligned Dual-Head block to decouple the classification and regression tasks. Based on our self-developed PMMW security screening dataset, experimental results including comparison with State-Of-The-Art (SOTA) methods and ablation study demonstrate that the PMMW-DETR obtains higher accuracy and classification confidence than previous works, and exhibits robustness to the PMMW images of low quality. 

### AstroSLAM: Autonomous Monocular Navigation in the Vicinity of a  Celestial Small Body -- Theory and Experiments
We propose AstroSLAM, a standalone vision-based solution for autonomous online navigation around an unknown target small celestial body. AstroSLAM is predicated on the formulation of the SLAM problem as an incrementally growing factor graph, facilitated by the use of the GTSAM library and the iSAM2 engine. By combining sensor fusion with orbital motion priors, we achieve improved performance over a baseline SLAM solution. We incorporate orbital motion constraints into the factor graph by devising a novel relative dynamics factor, which links the relative pose of the spacecraft to the problem of predicting trajectories stemming from the motion of the spacecraft in the vicinity of the small body. We demonstrate the excellent performance of AstroSLAM using both real legacy mission imagery and trajectory data courtesy of NASA's Planetary Data System, as well as real in-lab imagery data generated on a 3 degree-of-freedom spacecraft simulator test-bed. 

### Why Are Conditional Generative Models Better Than Unconditional Ones?
Extensive empirical evidence demonstrates that conditional generative models are easier to train and perform better than unconditional ones by exploiting the labels of data. So do score-based diffusion models. In this paper, we analyze the phenomenon formally and identify that the key of conditional learning is to partition the data properly. Inspired by the analyses, we propose self-conditioned diffusion models (SCDM), which is trained conditioned on indices clustered by the k-means algorithm on the features extracted by a model pre-trained in a self-supervised manner. SCDM significantly improves the unconditional model across various datasets and achieves a record-breaking FID of 3.94 on ImageNet 64x64 without labels. Besides, SCDM achieves a slightly better FID than the corresponding conditional model on CIFAR10. 

### A method of moments estimator for interacting particle systems and their  mean field limit
We study the problem of learning unknown parameters in stochastic interacting particle systems with polynomial drift, interaction and diffusion functions from the path of one single particle in the system. Our estimator is obtained by solving a linear system which is constructed by imposing appropriate conditions on the moments of the invariant distribution of the mean field limit and on the quadratic variation of the process. Our approach is easy to implement as it only requires the approximation of the moments via the ergodic theorem and the solution of a low-dimensional linear system. Moreover, we prove that our estimator is asymptotically unbiased in the limits of infinite data and infinite number of particles (mean field limit). In addition, we present several numerical experiments that validate the theoretical analysis and show the effectiveness of our methodology to accurately infer parameters in systems of interacting particles. 

### ViewNet: Unsupervised Viewpoint Estimation from Conditional Generation
Understanding the 3D world without supervision is currently a major challenge in computer vision as the annotations required to supervise deep networks for tasks in this domain are expensive to obtain on a large scale. In this paper, we address the problem of unsupervised viewpoint estimation. We formulate this as a self-supervised learning task, where image reconstruction provides the supervision needed to predict the camera viewpoint. Specifically, we make use of pairs of images of the same object at training time, from unknown viewpoints, to self-supervise training by combining the viewpoint information from one image with the appearance information from the other. We demonstrate that using a perspective spatial transformer allows efficient viewpoint learning, outperforming existing unsupervised approaches on synthetic data, and obtains competitive results on the challenging PASCAL3D+ dataset. 

### ViewNeRF: Unsupervised Viewpoint Estimation Using Category-Level Neural  Radiance Fields
We introduce ViewNeRF, a Neural Radiance Field-based viewpoint estimation method that learns to predict category-level viewpoints directly from images during training. While NeRF is usually trained with ground-truth camera poses, multiple extensions have been proposed to reduce the need for this expensive supervision. Nonetheless, most of these methods still struggle in complex settings with large camera movements, and are restricted to single scenes, i.e. they cannot be trained on a collection of scenes depicting the same object category. To address these issues, our method uses an analysis by synthesis approach, combining a conditional NeRF with a viewpoint predictor and a scene encoder in order to produce self-supervised reconstructions for whole object categories. Rather than focusing on high fidelity reconstruction, we target efficient and accurate viewpoint prediction in complex scenarios, e.g. 360{\deg} rotation on real data. Our model shows competitive results on synthetic and real datasets, both for single scenes and multi-instance collections. 

### CUNI Non-Autoregressive System for the WMT 22 Efficient Translation  Shared Task
We present a non-autoregressive system submission to the WMT 22 Efficient Translation Shared Task. Our system was used by Helcl et al. (2022) in an attempt to provide fair comparison between non-autoregressive and autoregressive models. This submission is an effort to establish solid baselines along with sound evaluation methodology, particularly in terms of measuring the decoding speed. The model itself is a 12-layer Transformer model trained with connectionist temporal classification on knowledge-distilled dataset by a strong autoregressive teacher model. 

### Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model
Most existing Image Restoration (IR) models are task-specific, which can not be generalized to different degradation operators. In this work, we propose the Denoising Diffusion Null-Space Model (DDNM), a novel zero-shot framework for arbitrary linear IR problems, including but not limited to image super-resolution, colorization, inpainting, compressed sensing, and deblurring. DDNM only needs a pre-trained off-the-shelf diffusion model as the generative prior, without any extra training or network modifications. By refining only the null-space contents during the reverse diffusion process, we can yield diverse results satisfying both data consistency and realness. We further propose an enhanced and robust version, dubbed DDNM+, to support noisy restoration and improve restoration quality for hard tasks. Our experiments on several IR tasks reveal that DDNM outperforms other state-of-the-art zero-shot IR methods. We also demonstrate that DDNM+ can solve complex real-world applications, e.g., old photo restoration. 

### Ghost-free High Dynamic Range Imaging via Hybrid CNN-Transformer and  Structure Tensor
Eliminating ghosting artifacts due to moving objects is a challenging problem in high dynamic range (HDR) imaging. In this letter, we present a hybrid model consisting of a convolutional encoder and a Transformer decoder to generate ghost-free HDR images. In the encoder, a context aggregation network and non-local attention block are adopted to optimize multi-scale features and capture both global and local dependencies of multiple low dynamic range (LDR) images. The decoder based on Swin Transformer is utilized to improve the reconstruction capability of the proposed model. Motivated by the phenomenal difference between the presence and absence of artifacts under the field of structure tensor (ST), we integrate the ST information of LDR images as auxiliary inputs of the network and use ST loss to further constrain artifacts. Different from previous approaches, our network is capable of processing an arbitrary number of input LDR images. Qualitative and quantitative experiments demonstrate the effectiveness of the proposed method by comparing it with existing state-of-the-art HDR deghosting models. Codes are available at https://github.com/pandayuanyu/HSTHdr. 

### Finetune like you pretrain: Improved finetuning of zero-shot vision  models
Finetuning image-text models such as CLIP achieves state-of-the-art accuracies on a variety of benchmarks. However, recent works like WiseFT (Wortsman et al., 2021) and LP-FT (Kumar et al., 2022) have shown that even subtle differences in the finetuning process can lead to surprisingly large differences in the final performance, both for in-distribution (ID) and out-of-distribution (OOD) data. In this work, we show that a natural and simple approach of mimicking contrastive pretraining consistently outperforms alternative finetuning approaches. Specifically, we cast downstream class labels as text prompts and continue optimizing the contrastive loss between image embeddings and class-descriptive prompt embeddings (contrastive finetuning). 

### One-shot recognition of any material anywhere using contrastive learning  with physics-based rendering
We present MatSim: a synthetic dataset, a benchmark, and a method for computer vision based recognition of similarities and transitions between materials and textures, focusing on identifying any material under any conditions using one or a few examples (one-shot learning). The visual recognition of materials is essential to everything from examining food while cooking to inspecting agriculture, chemistry, and industrial products. In this work, we utilize giant repositories used by computer graphics artists to generate a new CGI dataset for material similarity. We use physics-based rendering (PBR) repositories for visual material simulation, assign these materials random 3D objects, and render images with a vast range of backgrounds and illumination conditions (HDRI). We add a gradual transition between materials to support applications with a smooth transition between states (like gradually cooked food). We also render materials inside transparent containers to support beverage and chemistry lab use cases. We then train a contrastive learning network to generate a descriptor that identifies unfamiliar materials using a single image. We also present a new benchmark for a few-shot material recognition that contains a wide range of real-world examples, including the state of a chemical reaction, rotten/fresh fruits, states of food, different types of construction materials, types of ground, and many other use cases involving material states, transitions and subclasses. We show that a network trained on the MatSim synthetic dataset outperforms state-of-the-art models like Clip on the benchmark, despite being tested on material classes that were not seen during training. The dataset, benchmark, code and trained models are available online. 

### maplab 2.0 -- A Modular and Multi-Modal Mapping Framework
Integration of multiple sensor modalities and deep learning into Simultaneous Localization And Mapping (SLAM) systems are areas of significant interest in current research. Multi-modality is a stepping stone towards achieving robustness in challenging environments and interoperability of heterogeneous multi-robot systems with varying sensor setups. With maplab 2.0, we provide a versatile open-source platform that facilitates developing, testing, and integrating new modules and features into a fully-fledged SLAM system. Through extensive experiments, we show that maplab 2.0's accuracy is comparable to the state-of-the-art on the HILTI 2021 benchmark. Additionally, we showcase the flexibility of our system with three use cases: i) large-scale (approx. 10 km) multi-robot multi-session (23 missions) mapping, ii) integration of non-visual landmarks, and iii) incorporating a semantic object-based loop closure module into the mapping framework. The code is available open-source at https://github.com/ethz-asl/maplab. 

### Complexity Blowup for Solutions of the Laplace and the Diffusion  Equation
In this paper, we investigate the computational complexity of solutions to the Laplace and the diffusion equation. We show that for a certain class of initial-boundary value problems of the Laplace and the diffusion equation, the solution operator is unbounded as a mapping from the space of polynomial-time computable functions into itself in the sense that there exists polynomial-time (Turing) computable input data such that the solution is not polynomial-time computable, unless $FP=\#P$. In this case, we can, in general, not simulate the solution of the Laplace or the diffusion equation on a digital computer without having a complexity blowup, i.e., the computation time for obtaining an approximation of the solution with up to a finite number of significant digits grows exponentially in the number of digits. This shows that the computational complexity of the solution operator is intrinsically high, independent of the numerical algorithm that is used to obtain a solution. This indicates that there is a fundamental problem in computing a solution on a digital hardware. 

### Explainable Artificial Intelligence for Improved Modeling of Processes
In modern business processes, the amount of data collected has increased substantially in recent years. Because this data can potentially yield valuable insights, automated knowledge extraction based on process mining has been proposed, among other techniques, to provide users with intuitive access to the information contained therein. At present, the majority of technologies aim to reconstruct explicit business process models. These are directly interpretable but limited concerning the integration of diverse and real-valued information sources. On the other hand, Machine Learning (ML) benefits from the vast amount of data available and can deal with high-dimensional sources, yet it has rarely been applied to being used in processes. In this contribution, we evaluate the capability of modern Transformer architectures as well as more classical ML technologies of modeling process regularities, as can be quantitatively evaluated by their prediction capability. In addition, we demonstrate the capability of attentional properties and feature relevance determination by highlighting features that are crucial to the processes' predictive abilities. We demonstrate the efficacy of our approach using five benchmark datasets and show that the ML models are capable of predicting critical outcomes and that the attention mechanisms or XAI components offer new insights into the underlying processes. 

### Score Jacobian Chaining: Lifting Pretrained 2D Diffusion Models for 3D  Generation
A diffusion model learns to predict a vector field of gradients. We propose to apply chain rule on the learned gradients, and back-propagate the score of a diffusion model through the Jacobian of a differentiable renderer, which we instantiate to be a voxel radiance field. This setup aggregates 2D scores at multiple camera viewpoints into a 3D score, and repurposes a pretrained 2D model for 3D data generation. We identify a technical challenge of distribution mismatch that arises in this application, and propose a novel estimation mechanism to resolve it. We run our algorithm on several off-the-shelf diffusion image generative models, including the recently released Stable Diffusion trained on the large-scale LAION dataset. 

### Improving Zero-Shot Models with Label Distribution Priors
Labeling large image datasets with attributes such as facial age or object type is tedious and sometimes infeasible. Supervised machine learning methods provide a highly accurate solution, but require manual labels which are often unavailable. Zero-shot models (e.g., CLIP) do not require manual labels but are not as accurate as supervised ones, particularly when the attribute is numeric. We propose a new approach, CLIPPR (CLIP with Priors), which adapts zero-shot models for regression and classification on unlabelled datasets. Our method does not use any annotated images. Instead, we assume a prior over the label distribution in the dataset. We then train an adapter network on top of CLIP under two competing objectives: i) minimal change of predictions from the original CLIP model ii) minimal distance between predicted and prior distribution of labels. Additionally, we present a novel approach for selecting prompts for Vision & Language models using a distributional prior. Our method is effective and presents a significant improvement over the original model. We demonstrate an improvement of 28% in mean absolute error on the UTK age regression task. We also present promising results for classification benchmarks, improving the classification accuracy on the ImageNet dataset by 2.83%, without using any labels. 

### Multi-Class Segmentation from Aerial Views using Recursive Noise  Diffusion
Semantic segmentation from aerial views is a vital task for autonomous drones as they require precise and accurate segmentation to traverse safely and efficiently. Segmenting images from aerial views is especially challenging as they include diverse view-points, extreme scale variation and high scene complexity. To address this problem, we propose an end-to-end multi-class semantic segmentation diffusion model. We introduce recursive denoising which allows predicted error to propagate through the denoising process. In addition, we combine this with a hierarchical multi-scale approach, complementary to the diffusion process. Our method achieves state-of-the-art results on UAVid and on the Vaihingen building segmentation benchmark. 

### SparseFusion: Distilling View-conditioned Diffusion for 3D  Reconstruction
We propose SparseFusion, a sparse view 3D reconstruction approach that unifies recent advances in neural rendering and probabilistic image generation. Existing approaches typically build on neural rendering with re-projected features but fail to generate unseen regions or handle uncertainty under large viewpoint changes. Alternate methods treat this as a (probabilistic) 2D synthesis task, and while they can generate plausible 2D images, they do not infer a consistent underlying 3D. However, we find that this trade-off between 3D consistency and probabilistic image generation does not need to exist. In fact, we show that geometric consistency and generative inference can be complementary in a mode-seeking behavior. By distilling a 3D consistent scene representation from a view-conditioned latent diffusion model, we are able to recover a plausible 3D representation whose renderings are both accurate and realistic. We evaluate our approach across 51 categories in the CO3D dataset and show that it outperforms existing methods, in both distortion and perception metrics, for sparse-view novel view synthesis. 

### Unite and Conquer: Cross Dataset Multimodal Synthesis using Diffusion  Models
Generating photos satisfying multiple constraints find broad utility in the content creation industry. A key hurdle to accomplishing this task is the need for paired data consisting of all modalities (i.e., constraints) and their corresponding output. Moreover, existing methods need retraining using paired data across all modalities to introduce a new condition. This paper proposes a solution to this problem based on denoising diffusion probabilistic models (DDPMs). Our motivation for choosing diffusion models over other generative models comes from the flexible internal structure of diffusion models. Since each sampling step in the DDPM follows a Gaussian distribution, we show that there exists a closed-form solution for generating an image given various constraints. Our method can unite multiple diffusion models trained on multiple sub-tasks and conquer the combined task through our proposed sampling strategy. We also introduce a novel reliability parameter that allows using different off-the-shelf diffusion models trained across various datasets during sampling time alone to guide it to the desired outcome satisfying multiple constraints. We perform experiments on various standard multimodal tasks to demonstrate the effectiveness of our approach. More details can be found in https://nithin-gk.github.io/projectpages/Multidiff/index.html 

### Scaling Language-Image Pre-training via Masking
We present Fast Language-Image Pre-training (FLIP), a simple and more efficient method for training CLIP. Our method randomly masks out and removes a large portion of image patches during training. Masking allows us to learn from more image-text pairs given the same wall-clock time and contrast more samples per iteration with similar memory footprint. It leads to a favorable trade-off between accuracy and training time. In our experiments on 400 million image-text pairs, FLIP improves both accuracy and speed over the no-masking baseline. On a large diversity of downstream tasks, FLIP dominantly outperforms the CLIP counterparts trained on the same data. Facilitated by the speedup, we explore the scaling behavior of increasing the model size, data size, or training length, and report encouraging results and comparisons. We hope that our work will foster future research on scaling vision-language learning. 

