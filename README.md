# A Survey on Interpretability in Visual Recognition

Welcome to our curated repository showcasing significant works in the field of interpretable visual recognition. This collection serves as a companion to our survey paper, **A Survey on Interpretability in Visual Recognition**, providing insights into the evolving landscape of interpretability in this dynamic domain. We welcome contributions from the community to expand and update this repository. If you have a project or paper that you believe should be included, feel free to open an issue or submit a pull request.

![](image/framework.png)

## Catalogue

- [A Survey on Interpretability in Visual Recognition](#a-survey-on-interpretability-in-visual-recognition)
  - [Catalogue](#catalogue)
  - [Related Survey](#related-survey)
  - [Badge Introduction](#badge-introduction)
  - [Paper List](#paper-list)
  - [Metrics and Toolkits](#metrics-and-toolkits)
  - [Citation](#citation)

## Related Survey

We offer a selection of survey papers pertinent to this research. For more information, please visit [https://vipl-vsu.github.io/xai-recognition/](https://vipl-vsu.github.io/xai-recognition/).

## Badge Introduction

The table below introduces various badges used to categorize papers in terms of the four key dimensions of XAI recognition methods: Intent, Object, Presentation, and Methodology. The badges help to efficiently tag and identify research papers based on their interpretability approaches.

| Badge | Description |
| :--- | :--- |
| ![](https://img.shields.io/badge/I-passive-e97132)        | **Intent** is *passive*. Methods that explain already trained models by revealing their recognition process. |
| ![](https://img.shields.io/badge/I-active-e97132)         | **Intent** is *active*. Methods that integrate interpretability during model construction, making the process inherently interpretable. |
| ![](https://img.shields.io/badge/O-local-4ea72e)          | **Object** is *local*. Explanation focused on individual samples, such as diagnostic suggestions for each patient. |
| ![](https://img.shields.io/badge/O-semilocal-4ea72e)      | **Object** is *semilocal*. Explanation that highlights common characteristics within a class of samples. |
| ![](https://img.shields.io/badge/O-global-4ea72e)         | **Object** is *global*. Explanation of the entire model's decision rules, often category-independent. |
| ![](https://img.shields.io/badge/P-scalar-0f9ed5)         | **Presentation** is *scalar*. Explanation presented in quantitative forms, such as numerical scores. |
| ![](https://img.shields.io/badge/P-attention-0f9ed5)      | **Presentation** is *attention*. Used to highlight important features or regions contributing to a decision. |
| ![](https://img.shields.io/badge/P-structure-0f9ed5)      | **Presentation** is *structured*. Explanation involving structured representations such as graphs. |
| ![](https://img.shields.io/badge/P-semantic-0f9ed5)       | **Presentation** is *semantic unit*. Explanation decomposed into human-understandable semantic concepts. |
| ![](https://img.shields.io/badge/P-exemplar-0f9ed5)       | **Presentation** is *exemplar*. Explanation through examples that illustrate specific model behaviors. |
| ![](https://img.shields.io/badge/M-association-a02b93)    | **Methodology** is *association*. Methods that model correlations to show the relationships and patterns between inputs and outputs. |
| ![](https://img.shields.io/badge/M-intervention-a02b93)   | **Methodology** is *intervention*. Methods predicting outcomes after making active changes to the model or its inputs. |
| ![](https://img.shields.io/badge/M-counterfactual-a02b93) | **Methodology** is *conterfactual*. Simulates alternative scenarios by perturbing inputs to explore the potential outcomes that could arise under different conditions. |

## Paper List

- **Explain Any Concept: Segment Anything Meets Concept-based Explanation**. *NeurIPS 2024*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **This Looks Like Those: Illuminating Prototypical Concepts Using Multiple Visualizations**. *NeurIPS 2024*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **ECLAD: Extracting Concepts with Local Aggregated Descriptors**. *Pattern Recognition 2024*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Interpretable Object Recognition by Semantic Prototype Analysis**. *WACV 2024*. [Paper](https://openaccess.thecvf.com/content/WACV2024/html/Wan_Interpretable_Object_Recognition_by_Semantic_Prototype_Analysis_WACV_2024_paper.html) [Code](https://github.com/WanQiyang/SPANet)  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Concept-Centric Transformers: Enhancing Model Interpretability Through Object-Centric Concept Learning Within a Shared Global Workspace**. *WACV 2024*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **From Attribution Maps to Human-understandable Explanations Through Concept Relevance Propagation**. *Nature Machine Intelligence 2023*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **PIP-Net: Patch-based Intuitive Prototypes for Interpretable Image Classification**. *CVPR 2023*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Don't Lie to Me! Robust and Efficient Explainability with Verified Perturbation Analysis**. *CVPR 2023*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-counterfactual-a02b93)

- **Learning Support and Trivial Prototypes for Interpretable Image Classification**. *ICCV 2023*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Optimizing Explanations by Network Canonization and Hyperparameter Search**. *CVPR 2023*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-global-4ea72e)

- **Understanding the (Extra-)ordinary: Validating Deep Model Decisions with Prototypical Concept-based Explanations**. *arXiv 2311.16681*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Harsanyinet: Computing Accurate Shapley Values in a Single Forward Propagation**. *arXiv 2304.01811*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Interpretability-aware Vision Transformer**. *arXiv 2309.08035*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **A Novel Neural-symbolic System under Statistical Relational Learning**. *arXiv 2309.08931*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Mitigating Bias: Enhancing Image Classification by Improving Model Explanations**. *arXiv 2307.01473*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Fixating on Attention: Integrating Human Eye Tracking into Vision Transformers**. *arXiv 2308.13969*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **UFO: A Unified Method for Controlling Understandability and Faithfulness Objectives in Concept-based Explanations for CNNs**. *arXiv 2303.15632*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Distance-Aware eXplanation Based Learning**. *ICTAI 2023*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Gradient Strikes Back: How Filtering Out High Frequencies Improves Explanations**. *arXiv 2307.09591*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Concept Bottleneck Model with Additional Unsupervised Concepts**. *IEEE Access 2022*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Quantifying the Knowledge in a DNN to Explain Knowledge Distillation for Classification**. *TPAMI 2022*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **SegDiscover: Visual Concept Discovery via Unsupervised Semantic Segmentation**. *arXiv 2204.10926*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **ELUDE: Generating Interpretable Explanations via a Decomposition into Labelled and Unlabelled Features**. *arXiv 2206.07690*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Neural Prototype Trees for Interpretable Fine-grained Image Recognition**. *CVPR 2021*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-structure-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Natural Language Descriptions of Deep Visual Features**. *ICLR 2021*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **This Looks Like That, Because... Explaining Prototypes for Interpretable Image Recognition**. *ECML-PKDD 2021*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/M-counterfactual-a02b93)

- **Dissect: Disentangled Simultaneous Explanations via Concept Traversals**. *arXiv 2105.15164*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Interpretable Compositional Convolutional Neural Networks**. *arXiv 2107.04474*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Best of Both Worlds: Local and Global explanations with Human-understandable Concepts**. *arXiv 2106.08641*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **A Game-theoretic Taxonomy of Visual Concepts in DNNs**. *arXiv 2106.10938*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Keep Calm and Improve Visual Feature Attribution**. *ICCV 2021*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Generating Visual Explanations with Natural Language**. *Applied AI Letters 2021*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Visualizing the Emergence of Intermediate Visual Patterns in DNNs**. *NeurIPS 2021*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Concept Bottleneck Models**. *ICML 2020*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Concept Whitening for Interpretable Image Recognition**. *Nature Machine Intelligence 2020*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **On Completeness-aware Concept-based Explanations in Deep Neural Networks**. *NeurIPS 2020*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Explaining Knowledge Distillation by Quantifying the Knowledge**. *CVPR 2020*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Interpretable CNNs for Object Classification**. *TPAMI 2020*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Interactive Explanations of Internal Representations of Neural Network Layers: An Exploratory Study on Outcome Prediction of Comatose Patients**. *KDH 2020*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-structure-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Generating Visual and Semantic Explanations with Multi-task Network**. *ECCV Workshops 2020*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **This Looks Like That: Deep Learning for Interpretable Image Recognition**. *NeurIPS 2019*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Unmasking Clever Hans Predictors and Assessing What Machines Really Learn**. *Nature Communications 2019*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Towards Automatic Concept-based Explanations**. *NeurIPS 2019*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Explaining Classifiers with Causal Concept Effect (CaCE)**. *arXiv 1907.07165*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/M-counterfactual-a02b93)

- **Interpretable Image Recognition with Hierarchical Prototypes**. *AAAI 2019*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Towards Aggregating Weighted Feature Attributions**. *arXiv 1901.10040*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Deep Features Analysis with Attention Networks**. *arXiv 1901.10042*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Visualising the Training Process of Convolutional Neural Networks for Non-experts**. *BNAIC 2019*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **A Universal Logic Operator for Interpretable Deep Convolution Networks**. *arXiv 1901.08551*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5)

- **Interpretability Beyond Feature Attribution: Quantitative Testing with Concept Activation Vectors (TCAV)**. *ICML 2018*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Deep Learning for Case-based Reasoning through Prototypes: A Neural Network that Explains Its Predictions**. *AAAI 2018*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Multimodal Explanations: Justifying Decisions and Pointing to the Evidence**. *CVPR 2018*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Interpreting Deep Visual Representations via Network Dissection**. *TPAMI 2018*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Interpretable Basis Decomposition for Visual Explanation**. *ECCV 2018*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Grounding Visual Explanations**. *ECCV 2018*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/P-exemplar-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Revisiting the Importance of Individual Units in CNNs via Ablation**. *arXiv 1806.02891*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/M-counterfactual-a02b93)

- **Unsupervised Learning of Neural Networks to Explain Neural Networks**. *arXiv 1805.07468*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Generating Post-hoc Rationales of Deep Visual Classification Decisions**. *Explainable and Interpretable Models in Computer Vision and Machine Learning, 2018*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Grad-CAM: Visual Explanations from Deep Networks via Gradient-based Localization**. *ICCV 2017*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Axiomatic Attribution for Deep Networks**. *ICML 2017*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **SmoothGrad: Removing Noise by Adding Noise**. *arXiv 1706.03825*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Network Dissection: Quantifying Interpretability of Deep Visual Representations**. *CVPR 2017*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Explaining Nonlinear Classification Decisions with Deep Taylor Decomposition**. *Pattern Recognition 2017*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Towards Interpretable Deep Neural Networks by Leveraging Adversarial Examples**. *arXiv 1708.05493*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-active-e97132) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-scalar-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Growing Interpretable Part Graphs on Convnets via Multi-shot Learning**. *AAAI 2017*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-structure-0f9ed5) ![](https://img.shields.io/badge/M-intervention-a02b93)

- **Learning Deep Features for Discriminative Localization**. *CVPR 2016*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/O-global-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **Generating Visual Explanations**. *ECCV 2016*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-semilocal-4ea72e) ![](https://img.shields.io/badge/P-semantic-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

- **On Pixel-wise Explanations for Non-linear Classifier Decisions by Layer-wise Relevance Propagation**. *PloS one 2015*. [Paper]() [Code]()  
  ![](https://img.shields.io/badge/I-passive-e97132) ![](https://img.shields.io/badge/O-local-4ea72e) ![](https://img.shields.io/badge/P-attention-0f9ed5) ![](https://img.shields.io/badge/M-association-a02b93)

## Metrics and Toolkits

- **Quantus: An Explainable AI Toolkit for Responsible Evaluation of Neural Network Explanations and Beyond**. *JMLR 2023.* [Paper](https://www.jmlr.org/papers/v24/22-0142.html) [Code](https://github.com/understandable-machine-intelligence-lab/Quantus)

## Citation

```
@article{wan2025survey,
  title={A Survey on Interpretability in Visual Recognition},
  author={Wan, Qiyang and Gao, Chengzhi and Wang, Ruiping and Chen, Xilin},
  journal={arXiv preprint arXiv:2507.11099},
  year={2025}
}
```
