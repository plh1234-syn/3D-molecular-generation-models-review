# 3D molecular and materials generation model catalogue

[Back to README](README.md) · [Download the Excel dataset](3D_molecular_generation_models.xlsx?raw=true)

Literature and implementation links grouped by the categories in the accompanying workbook. Titles and years follow the source collection; a paper may appear in more than one category. Use GitHub's document outline or your browser's Find function to navigate.

**Updated: 19 November 2026.** This catalogue contains 223 distinct normalized title strings, including title variants of the same work. Repeated identical titles within each category are displayed once. This is not a count of 223 independent models.

`—` indicates that no code/resource link is listed. The resource column can include author-provided implementations, trained models and other research resources.

## Contents

- [Generative adversarial networks](#generative-adversarial-networks)
- [Variational autoencoders](#variational-autoencoders)
- [Autoregressive models](#autoregressive-models)
- [Diffusion models](#diffusion-models)
- [Flow models](#flow-models)
- [Energy-based models](#energy-based-models)
- [Text-based models](#text-based-models)
- [Multimodal models](#multimodal-models)
- [Multiple frameworks](#multiple-frameworks)
- [Multi-objective optimization](#multi-objective-optimization)
- [Materials generation](#materials-generation)
- [Additional entries](#additional-entries)

## Generative adversarial networks

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| A dual-population multi-objective evolutionary algorithm driven by generative adversarial networks for benchmarking and protein-peptide docking | 2024 | [Paper](https://www.sciencedirect.com/science/article/pii/S0010482523011927) | — |
| A pocket-based 3D molecule generative model fueled by experimental electron density | 2022 | [Paper](https://www.nature.com/articles/s41598-022-19363-6) | — |
| WGAN-based molecular clumps generation | 2025 | [Paper](https://www.sciencedirect.com/science/article/pii/S1384107625001009) | — |
| Functional Protein Structure Annotation Using a Deep Convolutional Generative Adversarial Network | 2022 | [Paper](https://arxiv.org/abs/2104.08969) | [Code](https://github.com/drexelai/protein-nets) |
| Generative multiscale analysis of de novo proteome-inspired molecular structures and nanomechanical optimization using a VoxelPerceiver transformer model | 2023 | [Paper](https://doi.org/10.1016/j.jmps.2022.105098) | — |
| TopMT-GAN: a 3D topology-driven generative model for efficient and diverse structure-based ligand design | 2025 | [Paper](https://doi.org/10.1039/d4sc05211k) | [Code](https://github.com/aeghnnsw/TopMT.git) |
| The development of the generative adversarial supporting vector machine for molecular property generation | 2025 | [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-025-01052-x) | [Code](https://github.com/LQchem/GASVM.git) |
| Generative adversarial networks for transition state geometry prediction | 2021 | [Paper](https://doi.org/10.1063/5.0055094) | [Code](https://github.com/ekraka/TS-GAN) |
| Chemistry-Informed Generative Model for Classical Dynamics Simulations | 2024 | [Paper](https://pubs.acs.org/doi/10.1021/acs.jpclett.3c03114) | — |
| Generative Adversarial Learning of Protein Tertiary Structures | 2021 | [Paper](https://www.mdpi.com/1420-3049/26/5/1209) | — |
| Application scenario-oriented molecule generation platform developed for drug discovery | 2024 | [Paper](https://doi.org/10.1016/j.ymeth.2023.12.009) | — |
| HelixGAN: a deep-learning methodology for conditional de novo design of α-helix structures | 2023 | [Paper](https://academic.oup.com/bioinformatics/article/39/1/btad036/6991169) | [Code](https://github.com/xxiexuezhi/helix_gan) |
| Direct generation of protein conformational ensembles via machine learning | 2023 | [Paper](https://www.nature.com/articles/s41467-023-36443-x) | [Code](https://github.com/feiglab/idpgan) |
| DNMG: Deep molecular generative model by fusion of 3D information for de novo drug design | 2023 | [Paper](https://www.sciencedirect.com/science/article/pii/S1046202323000245) | — |
| Generating 3D molecules conditional on receptor binding sites with deep generative models | 2022 | [Paper](https://pubs.rsc.org/en/content/articlelanding/2022/sc/d1sc05976a) | [Code](https://github.com/mattragoza/liGAN) |

## Variational autoencoders

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Ig-VAE: Generative modeling of protein structure by direct 3D coordinate generation | 2022 | [Paper](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010271) | [Code](https://github.com/ProteinDesignLab/IgVAE) |
| Variational autoencoder-based chemical latent space for large molecular structures with 3D complexity | 2023 | [Paper](https://www.nature.com/articles/s42004-023-01054-6) | [Code](https://github.com/toshikiochiai/NPVAE) |
| Efficient 3D Molecular Design with an E(3) Invariant Transformer VAE | 2023 | [Paper](https://pubs.acs.org/doi/full/10.1021/acs.jpca.3c04188) | — |
| 3DLinker: An E(3) Equivariant Variational Autoencoder | 2022 | [Paper](https://arxiv.org/abs/2205.07309) | — |
| Generative molecule evolution using 3D pharmacophore for efficient Structure-Based Drug Design | 2025 | [Paper](https://arxiv.org/abs/2507.20130) | — |
| MOLUCINATE:AGenerative Model for Molecules in 3D Space | 2021 | [Paper](https://arxiv.org/abs/2109.15308) | — |
| Towards Unified and Lossless Latent Space for 3D Molecular Latent Diffusion Modeling | 2025 | [Paper](https://arxiv.org/abs/2503.15567) | — |
| Inverse mapping of quantum properties to structures for chemical space of small organic molecules | 2024 | [Paper](https://www.nature.com/articles/s41467-024-50401-1) | [Code](https://github.com/AleFalla/Properties-to-molecules-Inverse-Mapping) |
| Multimodal protein representation learning and target-aware variational auto-encoders for protein-binding ligand generation | 2024 | [Paper](https://iopscience.iop.org/article/10.1088/2632-2153/ad3ee4) | [Code](https://github.com/HySonLab/Ligand_Generation) |
| Structure Language Models for Protein Conformation Generation | 2025 | [Paper](https://arxiv.org/abs/2410.18403) | [Code](https://github.com/lujiarui/esmdiff) |
| Towards Unified Latent Space for 3D Molecular Latent Diffusion Modeling | 2025 | [Paper](https://arxiv.org/abs/2503.15567) | — |
| Geometry-Based Molecular Generation With Deep Constrained Variational Autoencoder | 2024 | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9714718) | — |
| Towards Deep Generative Backmapping of Coarse-Grained Molecular Systems | 2025 | [Paper](https://doi.org/10.1145/3663976.3664026) | — |
| Deep generative priors for biomolecular 3D heterogeneous reconstruction from cryo-EM projections | 2024 | [Paper](https://doi.org/10.1016/j.jsb.2024.108073) | [Code](https://github.com/benjamin3344/DGP-SPR) |
| Generating tertiary protein structures via interpretable graph variational autoencoders | 2021 | [Paper](https://doi.org/10.1093/bioadv/vbab036) | [Code](https://github.com/anonymous1025/CO-VAE) |
| Deep generative models of protein structure uncover distant relationships across a continuous fold space | 2024 | [Paper](https://www.nature.com/articles/s41467-024-52020-2) | [Code](http://github.com/bouralab/DeepUrfold) |
| 3D molecular generative framework for interaction-guided drug design | 2024 | [Paper](https://www.nature.com/articles/s41467-024-47011-2) | [Code](https://github.com/ACE-KAIST/DeepICL) |

## Autoregressive models

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Symmetry-adapted generation of 3d point sets for the targeted discovery of molecules | 2019 | [Paper](https://dl.acm.org/doi/abs/10.5555/3454287.3454967) | [Code](https://github.com/atomistic-machine-learning/G-SchNet) |
| Inverse design of 3d molecular structures with conditional generative neural networks | 2022 | [Paper](https://www.nature.com/articles/s41467-022-28526-y) | [Code](http://www.github.com/atomistic-machine-learning/cG-SchNet) |
| Pocket2Mol: Efficient Molecular Sampling Based on 3D Protein Pockets | 2025 | [Paper](https://arxiv.org/abs/2205.07249) | [Code](https://github.com/pengxingang/Pocket2Mol) |
| An Autoregressive Flow Model for 3D Molecular Geometry Generation from Scratch | 2022 | [Paper](https://openreview.net/forum?id=C03Ajc-NS5W) | [Code](https://github.com/divelab/DIG) |
| PocketFlow is a data-and-knowledge-driven structure-based molecular generative model | 2024 | [Paper](https://www.nature.com/articles/s42256-024-00808-8) | [Code](https://github.com/Saoge123/PocketFlow) |
| Semi-equivariant conditional normalizing flows, with applications to target-aware molecule generation | 2023 | [Paper](https://iopscience.iop.org/article/10.1088/2632-2153/ace58c) | [Code](https://github.com/EyalRozenberg1/se_conditional_flows) |
| MolFORM: Multi-modal Flow Matching for Structure-Based Drug Design | 2025 | [Paper](https://arxiv.org/abs/2507.05503) | [Code](https://github.com/huang3170/MolForm) |
| Not-So-Optimal Transport Flows for 3D Point Cloud Generation | 2025 | [Paper](https://arxiv.org/abs/2502.12456) | — |
| Exploring Discrete Flow Matching for 3D De Novo Molecule Generation | 2025 | [Paper](https://arxiv.org/abs/2411.16644) | [Code](https://github.com/dunni3/FlowMol) |
| SemlaFlow -- Efficient 3D Molecular Generation with Latent Attention and Equivariant Flow Matching | 2025 | [Paper](https://arxiv.org/abs/2406.07266) | [Code](https://github.com/rssrwn/semla-flow) |
| ResGen is a pocket-aware 3D molecular generation model based on parallel multiscale modelling | 2023 | [Paper](https://www.nature.com/articles/s42256-023-00712-7) | [Code](https://github.com/HaotianZhangAI4Science/ResGen) |
| Scalable Autoregressive 3DMoleculeGeneration | 2025 | [Paper](https://arxiv.org/abs/2505.13791) | — |
| High-throughput property-driven generative design of functional organic molecules | 2023 | [Paper](https://www.nature.com/articles/s43588-022-00391-1) | [Code](https://github.com/rhyan10/G-SchNetOE62) |
| MOLUCINATE:AGenerative Model for Molecules in 3D Space | 2021 | [Paper](https://arxiv.org/abs/2109.15308) | — |
| 3D molecular generative framework for interaction-guided drug design | 2024 | [Paper](https://www.nature.com/articles/s41467-024-47011-2) | [Code](https://github.com/ACE-KAIST/DeepICL) |
| Equivariant Asynchronous Diffusion: An Adaptive Denoising Schedule for Accelerated Molecular Conformation Generation | 2026 | [Paper](https://arxiv.org/abs/2603.10093) | — |
| NEAT: Neighborhood-Guided, Efficient, Autoregressive Set Transformer for 3D Molecular Generation | 2026 | [Paper](https://arxiv.org/abs/2512.05844) | [Code](https://github.com/molinfo-vienna/NEAT) |
| FragGen: towards 3D geometry reliable fragment-based molecular generation | 2024 | [Paper](https://doi.org/10.1039/d4sc04620j) | [Code](https://github.com/HaotianZhangAI4Science/FragGen) |

## Diffusion models

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Equivariant Diffusion for Molecule Generation in 3D (EDM, ICML 2022) | 2022 | [Paper](https://arxiv.org/abs/2203.17003) | [Code](https://github.com/ehoogeboom/e3_diffusion_for_molecules) |
| Diffusion-based Molecule Generation with Informative Prior Bridges (EDM-Bridge, NeurIPS 2022) | 2022 | [Paper](https://arxiv.org/abs/2209.00865) | — |
| Equivariant Energy-Guided SDE for Inverse Molecular Design (EEGSDE, ICLR 2023) | 2023 | [Paper](https://arxiv.org/abs/2209.15408) | [Code](https://github.com/gracezhao1997/EEGSDE) |
| Geometric Latent Diffusion Models for 3D Molecule Generation (GeoLDM, ICML 2023) | 2023 | [Paper](https://arxiv.org/abs/2305.01140) | [Code](https://github.com/MinkaiXu/GeoLDM) |
| MDM: Molecular Diffusion Model for 3D Molecule Generation (MDM, AAAI 2023) | 2023 | [Paper](https://arxiv.org/abs/2209.05710) | [Code](https://github.com/tencent-ailab/MDM) |
| 3D molecule generation by denoising voxel grids (VoxMol, NeurIPS 2023) | 2023 | [Paper](https://arxiv.org/abs/2306.07473) | [Code](https://github.com/genentech/voxmol) |
| DiffMol: 3D Structured Molecule Generation with Discrete Denoising Diffusion Probabilistic Models (ICML Worshop 2023) | 2023 | [Paper](https://openreview.net/pdf?id=x43ZyXJC9q) | — |
| Guided diffusion for inverse molecular design (GaUDI, Nature Computational Science 2023) | 2023 | [Paper](https://www.nature.com/articles/s43588-023-00532-0) | [Code](https://gitlab.com/porannegroup/gaudi) |
| Zero Shot Molecular Generation via Similarity Kernels (SiMGen, arXiv 2024) | 2024 | [Paper](https://arxiv.org/abs/2402.08708) | [Code](https://github.com/RokasEl/simgen) |
| ControlMol: Adding Substructure Control To Molecule Diffusion Models (arXiv 2024) | 2024 | [Paper](https://arxiv.org/abs/2405.06659) | — |
| Latent 3D Graph Diffusion (LDM-3DG, ICLR 2024) | 2024 | [Paper](https://openreview.net/pdf?id=cXbnGtO0NZ) | [Code](https://github.com/Shen-Lab/LDM-3DG) |
| Context-Guided Diffusion for Out-of-Distribution Molecular and Protein Design (CGD, ICML 2024) | 2024 | [Paper](https://arxiv.org/abs/2407.11942) | [Code](https://github.com/leojklarner/context-guided-diffusion) |
| Equivariant Neural Diffusion for Molecule Generation (END, NeurIPS 2024) | 2024 | [Paper](https://doi.org/10.52202/079017-1564) | [Code](https://github.com/frcnt/equivariant-neural-diffusion) |
| Geometric-Facilitated Denoising Diffusion Model for 3D Molecule Generation (GFMDiff, AAAI 2024) | 2024 | [Paper](https://arxiv.org/abs/2401.02683) | — |
| Training-free Multi-objective Diffusion Model for 3D Molecule Generation (MuDM, ICLR 2024) | 2024 | [Paper](https://openreview.net/pdf?id=X41c4uB4k0) | — |
| Navigating the Design Space of Equivariant Diffusion-Based Generative Models for De Novo 3D Molecule Generation (EQGAT-diff, ICLR 2024) | 2024 | [Paper](https://arxiv.org/abs/2309.17296) | — |
| Graph Generation with Diffusion Mixture (GruM, ICML 2024) | 2024 | [Paper](https://arxiv.org/abs/2302.03596) | [Code](https://github.com/harryjo97/GruM) |
| A dual diffusion model enables 3D molecule generation and lead optimization based on target pockets | 2024 | [Paper](https://www.nature.com/articles/s41467-024-46569-1) | [Code](https://github.com/Layne-Huang/PMDM/tree/main) |
| NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation (ICLR 2025) | 2025 | [Paper](https://arxiv.org/abs/2502.12638) | [Code](https://github.com/acharkq/NExT-Mol) |
| Chemistry-Inspired Diffusion with Non-Differentiable Guidance (ChemGuide, ICLR 2025) | 2025 | [Paper](https://openreview.net/pdf?id=4dAgG8ma3B) | [Code](https://github.com/A-Chicharito-S/ChemGuide) |
| E(3)-equivariant models cannot learn chirality: Field-based molecular generation (FMG, ICLR 2025) | 2025 | [Paper](https://openreview.net/pdf?id=mXHTifc1Fn) | [Code](https://github.com/Dumitrescu-Alexandru/FMG) |
| Geometry-complete latent diffusion model for 3D molecule generation | 2025 | [Paper](https://doi.org/10.1093/bioinformatics/btaf426) | [Code](https://github.com/charlotte0104/GCLDM-for-3d-molucule-generation) |
| MDM:Molecular Diffusion Model for 3D Molecule Generation | 2022 | [Paper](https://arxiv.org/abs/2209.05710) | [Code](https://github.com/tencent-ailab/MDM) |
| Geometry-complete diffusion for 3D molecule generation and optimization | 2024 | [Paper](https://www.nature.com/articles/s42004-024-01233-z) | [Code](https://github.com/BioinfoMachineLearning/Bio-Diffusion) |
| MiDi: Mixed Graph and 3D Denoising Diffusion for Molecule Generation | 2023 | [Paper](https://link.springer.com/chapter/10.1007/978-3-031-43415-0_33) | [Code](http://www.github.com/cvignac/MiDi) |
| A 3D generation framework using diffusion model and reinforcement learning to generate multi-target compounds with desired properties | 2025 | [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-025-01035-y) | [Code](https://github.com/Xinol1024/MDRL) |
| Equivariant 3D-Conditional Diffusion Model for De Novo Drug Design | 2025 | [Paper](https://ieeexplore.ieee.org/document/10742491) | [Code](https://github.com/haichengyi/DiffFBDD) |
| Coarse-to-Fine: a Hierarchical Diffusion Model for Molecule Generation in 3D | 2023 | [Paper](https://arxiv.org/abs/2305.13266) | [Code](https://github.com/qiangbo1222/HierDiff) |
| DiffMC-Gen: A Dual Denoising Diffusion Model for Multi-Conditional Molecular Generation | 2024 | [Paper](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202417726) | — |
| Text-guided small molecule generation via diffusion model | 2024 | [Paper](https://doi.org/10.1016/j.isci.2024.110992) | [Code](https://github.com/lyc0930/TEDMol) |
| MUDiff: Unified Diffusion for Complete Molecule Generation | 2024 | [Paper](https://arxiv.org/abs/2304.14621) | [Code](https://github.com/WillHua127/mudiff) |
| MolDiff: Addressing the Atom-Bond Inconsistency Problem in 3D Molecule Diffusion Generation | 2023 | [Paper](https://arxiv.org/abs/2305.07508) | [Code](https://github.com/pengxingang/MolDiff) |
| EC-Conf: A ultra-fast diffusion model for molecular conformation generation with equivariant consistency | 2020 | [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-024-00893-2) | [Code](https://github.com/DeepLearningPS/EcConf) |
| Improving structural plausibility in diffusion-based 3D molecule generation via property-conditioned training with distorted molecules | 2025 | [Paper](https://doi.org/10.1039/d4dd00331d) | [Code](https://github.com/lucyvost/distorted_diffusion/tree/main) |
| DiSCO: Diffusion Schrödinger Bridge for Molecular Conformer Optimization | 2024 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/29238) | [Code](https://github.com/Danyeong-Lee/DiSCO) |
| GDiffRetro: Retrosynthesis Prediction with Dual Graph Enhanced Molecular Representation and Diffusion Generation | 2025 | [Paper](https://arxiv.org/abs/2501.08001) | [Code](https://github.com/sunshy-1/GDiffRetro) |
| DiffBP: generative diffusion of 3D molecules for target protein binding | 2025 | [Paper](https://pubs.rsc.org/en/content/articlelanding/2025/sc/d4sc05894a) | [Code](https://drive.google.com/drive/folders/1bSDoQBERjXXvwAFRscuZXcyiKAyjRHuI?usp=sharing) |
| 3D-EDiffMG: 3D equivariant diffusion-driven molecular generation to accelerate drug discovery | 2025 | [Paper](https://www.sciencedirect.com/science/article/pii/S2095177925000747?via%3Dihub) | [Code](https://github.com/ZheLi-Lab-Collaboration/3D-EDiffMG) |
| SE(3) diffusion model with application to protein backbone generation | 2023 | [Paper](https://proceedings.mlr.press/v202/yim23a/yim23a.pdf) | [Code](https://github.com/jasonkyuyim/se3_diffusion) |
| Protein–peptide docking with a rational and accurate diffusion generative model | 2025 | [Paper](https://www.nature.com/articles/s42256-025-01077-9) | [Code](https://github.com/huifengzhao/RAPiDock) |
| Equivariant Flow Matching with Hybrid Probability Transport for 3D Molecule Generation | 2023 | [Paper](https://arxiv.org/abs/2312.07168) | [Code](https://github.com/AlgoMole/MolFM) |
| TarMGDif: Target-specific Molecular Graphs Generation Based on Diffusion Model | 2025 | [Paper](https://ieeexplore.ieee.org/document/10998952) | — |
| KGDiff: towards explainable target-aware molecule generation with knowledge guidance | 2024 | [Paper](https://academic.oup.com/bib/article/25/1/bbad435/7457350?login=true) | [Code](https://github.com/CMACH508/KGDiff) |
| PMODiff: Physics-Informed Multi-Objective Optimization Diffusion Model for Protein-Specific 3D Molecule Generation | 2025 | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.5c00591) | [Code](https://github.com/zhangyaoxiang/PMODiff/tree/main) |
| PIDiff: Physics informed diffusion model for protein pocket-specific 3D molecular generation | 2024 | [Paper](https://www.sciencedirect.com/science/article/pii/S0010482524009508?via%3Dihub) | [Code](https://github.com/hello-maker/PIDiff) |
| Multimodal Bonds Reconstruction Towards Generative Molecular Design | 2025 | [Paper](https://doi.org/10.1101/2025.05.06.652517) | — |
| Functional-Group-Based Diffusion for Pocket-Specific Molecule Generation and Elaboration | 2025 | [Paper](https://arxiv.org/abs/2306.13769) | — |
| DecompDiff: Diffusion Models with Decomposed Priors for Structure-Based Drug Design | 2024 | [Paper](https://arxiv.org/abs/2403.07902) | — |
| BindGPT: A Scalable Framework for 3D Molecular Design via Language Modeling and Reinforcement Learning | 2025 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/34804) | [Code](https://bindgpt.github.io/) |
| DiffInt: A Diffusion Model for Structure-Based Drug Design with Explicit Hydrogen Bond Interaction Guidance | 2024 | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.4c01385) | [Code](https://github.com/sekijima-lab/DiffInt) |
| nach0-pc: Multi-task Language Model with Molecular Point Cloud Encoder | 2024 | [Paper](https://arxiv.org/abs/2410.09240) | — |
| Small-Molecule Conformer Generators: Evaluation of Traditional Methods and AI Models on High-Quality Data Sets | 2023 | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01519) | [Code](https://github.com/wangzhehyd/fastsmcg) |
| Assignment of structural domains in proteins using diffusion kernels on graphs | 2022 | [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-022-04902-9) | [Code](https://github.com/taherimo/kludo) |
| Structure-based Drug Design with Equivariant Diffusion Models | 2024 | [Paper](https://www.nature.com/articles/s43588-024-00737-x) | [Code](https://github.com/arneschneuing/DiffSBDD) |
| GEOMOL: Torsional Geometric Generation of Molecular 3D Conformer Ensembles | 2023 | [Paper](https://arxiv.org/abs/2106.07802) | [Code](https://github.com/PattanaikL/GeoMol) |
| 3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction | 2023 | [Paper](https://arxiv.org/abs/2303.03543) | [Code](https://github.com/guanjq/targetdiff) |
| Bridging the Gap between Learning and Inference for Diffusion-Based Molecule Generation | 2024 | [Paper](https://arxiv.org/abs/2411.05472) | [Code](https://github.com/HUGHNew/gapdiff) |
| In-silico 3D molecular editing through physics-informed and preference-aligned generative foundation models | 2025 | [Paper](https://www.nature.com/articles/s41467-025-61323-x) | [Code](https://github.com/issacAzazel/MolEdit) |
| A generative model for inorganic materials design | 2025 | [Paper](https://www.nature.com/articles/s41586-025-08628-5) | [Code](https://github.com/microsoft/mattergen) |
| EQUIVARIANT 3D-CONDITIONAL DIFFUSION MODELS FOR MOLECULAR LINKER DESIGN | 2022 | [Paper](https://arxiv.org/abs/2210.05274) | [Code](https://github.com/igashov/DiffLinker) |
| Lift Your Molecules: Molecular Graph Generation in Latent Euclidean Space | 2024 | [Paper](https://arxiv.org/abs/2406.10513) | — |
| Rethinking Specificity in SBDD: Leveraging Delta Score and Energy-Guided Diffusion | 2024 | [Paper](https://arxiv.org/abs/2403.12987) | — |
| Binding-Adaptive Diffusion Models for Structure-Based Drug Design | 2024 | [Paper](https://arxiv.org/abs/2402.18583) | [Code](https://github.com/YangLing0818/BindDM) |
| Interaction-based retrieval-augmented diffusion models for protein-specific 3D molecule generation | 2024 | [Paper](https://dl.acm.org/doi/10.5555/3692070.3692887) | [Code](https://github.com/YangLing0818/IRDiff) |
| Aligning Target-Aware Molecule Diffusion Models with Exact Energy Optimization | 2024 | [Paper](https://doi.org/10.52202/079017-1398) | [Code](https://github.com/MinkaiXu/AliDiff) |
| Protein-Ligand Interaction Prior for Binding-aware 3D Molecule Diffusion Models | 2024 | [Paper](https://openreview.net/forum?id=qH9nrMNTIW) | [Code](https://github.com/YangLing0818/IPDiff) |
| Transferable deep generative modeling of intrinsically disordered protein conformations | 2024 | [Paper](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012144) | — |
| Target-aware 3D molecular generation based on guided equivariant diffusion | 2025 | [Paper](https://www.nature.com/articles/s41467-025-63245-0) | [Code](https://github.com/QiaoyuHu89/DiffGui) |
| Generative design of crystal structures by point cloud representations and diffusion model | 2025 | [Paper](https://doi.org/10.1016/j.isci.2024.111659) | [Code](https://github.com/lzhelin/CrystalDiffusion) |
| Score-based 3D molecule generation with neural fields | 2025 | [Paper](https://arxiv.org/abs/2501.08508) | [Code](https://github.com/prescient-design/funcmol) |
| E(3)-EQUIVARIANT MODELS CANNOT LEARN CHIRALITY: FIELD-BASED MOLECULAR GENERATION | 2024 | [Paper](https://openreview.net/pdf?id=mXHTifc1Fn) | [Code](https://github.com/Dumitrescu-Alexandru/FMG) |
| Structure-based de novo drug design using 3D deep generative models | 2021 | [Paper](https://pubs.rsc.org/en/content/articlehtml/2021/sc/d1sc04444c) | — |
| Efficient protein structure generation with sparse denoising models | 2025 | [Paper](https://www.nature.com/articles/s42256-025-01100-z) | [Code](https://www.nature.com/articles/s42256-025-01100-z) |
| Generating 3D small binding molecules using shape-conditioned diffusion models with guidance | 2025 | [Paper](https://www.nature.com/articles/s42256-025-01030-w) | [Code](https://github.com/ninglab/DiffSMol) |
| Disentangled autoencoding equivariant diffusion model for controlled generation of 3D molecules | 2026 | [Paper](https://www.nature.com/articles/s41467-026-71441-9) | [Code](https://github.com/leetx1010/MolDiffdAE) |
| LaMGen: LLM-based 3D molecular generation for multi-target drug design | 2026 | [Paper](https://www.nature.com/articles/s41467-026-71737-w) | [Code](https://github.com/cholin01/LaMGen/tree/master) |
| An effective fragment-based dual conditional diffusion framework for molecular generation | 2026 | [Paper](https://academic.oup.com/bib/article/27/1/bbaf727/8429903?login=true&guestAccessKey=) | [Code](https://github.com/CHT713/FDC-Diff) |
| Steering semi-flexible molecular diffusion model for structure-based drug design with reinforcement learning | 2026 | [Paper](https://www.science.org/doi/full/10.1126/sciadv.ady9955) | [Code](https://github.com/divelab/MoleculeX) |
| VecMol: Vector-Field Representations for 3D Molecule Generation | 2026 | [Paper](https://arxiv.org/abs/2603.12734) | [Code](https://github.com/CHERRY-ui8/VecMol) |
| SynCoGen: Synthesizable 3D Molecule Generation via Joint Reaction and Coordinate Modeling | 2026 | [Paper](https://openreview.net/forum?id=VtPiY1TupB) | — |
| A feature-aligned diffusion model for controllable generation of 3D drug-like molecules | 2026 | [Paper](https://doi.org/10.1039/d5dd00440c) | — |
| Permutation-Symmetrized Diffusion for Unconditional Molecular Generation | 2026 | [Paper](https://arxiv.org/abs/2603.23255) | — |
| Equivariant Asynchronous Diffusion: An Adaptive Denoising Schedule for Accelerated Molecular Conformation Generation | 2026 | [Paper](https://arxiv.org/abs/2603.10093) | — |
| Distributional Priors Guided Diffusion for Generating 3D Molecules in Low Data Regimes | 2026 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/39325) | — |
| Breaking the Bottlenecks: Scalable Diffusion Models for 3D Molecular Generation | 2026 | [Paper](https://arxiv.org/abs/2601.08963) | — |
| Invariant Conditional Molecular Generation Under Distribution Shift | 2026 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/39334) | [Code](https://github.com/selena200002/IC-MOL) |
| Apo2Mol: 3D Molecule Generation via Dynamic Pocket-Aware Diffusion Models | 2026 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/37138) | [Code](https://github.com/AIDD-LiLab/Apo2Mol) |
| VEDA: Generation of 3D Molecules via Variance-Exploding Diffusion with Annealing | 2026 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/40063) | — |
| Conditional diffusion with locality-aware modal alignment for generating diverse protein conformational ensembles | 2026 | [Paper](https://www.nature.com/articles/s42256-026-01198-9) | [Code](https://github.com/Paulie-ai/Mac-Diff) |
| Equivariant 3D-conditional diffusion model for molecular linker design | 2024 | [Paper](https://www.nature.com/articles/s42256-024-00815-9) | [Code](https://github.com/igashov/DiffLinker) |
| DiffHopp: A Graph Diffusion Model for Novel Drug Design via Scaffold Hopping | 2023 | [Paper](https://arxiv.org/abs/2308.07416) | [Code](https://github.com/jostorge/diffusion-hopping) |
| TurboHopp: Accelerated Molecule Scaffold Hopping with Consistency Models | 2024 | [Paper](https://arxiv.org/abs/2410.20660) | [Code](https://github.com/orgw/TurboHopp) |

## Flow models

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| DEMO: Disentangled Molecular Graph Generation via an Invertible Flow Model | 2022 | [Paper](https://dl.acm.org/doi/abs/10.1145/3511808.3557217) | — |
| MolCRAFT: Structure-Based Drug Design in Continuous Parameter Space | 2024 | [Paper](https://arxiv.org/abs/2404.12141) | [Code](https://github.com/AlgoMole/MolCRAFT) |
| MolFORM:Multi-modal Flow Matching for Structure-Based Drug Design | 2025 | [Paper](https://arxiv.org/abs/2507.05503) | [Code](https://github.com/huang3170/MolForm) |
| Inverse design of 3d molecular structures with conditional generative neural networks | 2022 | [Paper](https://www.nature.com/articles/s41467-022-28526-y) | [Code](http://www.github.com/atomistic-machine-learning/cG-SchNet) |
| PocketFlow is a data-and-knowledge-driven structure-based molecular generative model | 2024 | [Paper](https://www.nature.com/articles/s42256-024-00808-8) | [Code](https://github.com/Saoge123/PocketFlow) |
| Equivariant Flow Matching with Hybrid Probability Transport for 3D Molecule Generation | 2023 | [Paper](https://arxiv.org/abs/2312.07168) | [Code](https://github.com/AlgoMole/MolFM) |
| Mixed Continuous and Categorical Flow Matching for 3D De Novo Molecule Generation | 2024 | [Paper](https://arxiv.org/abs/2404.19739) | [Code](https://github.com/dunni3/FlowMol) |
| Efficient 3D Molecular Generation with Flow Matching and Scale Optimal Transport | 2024 | [Paper](https://arxiv.org/abs/2406.07266) | — |
| An Autoregressive Flow Model for 3D Molecular Geometry Generation from Scratch | 2022 | [Paper](https://openreview.net/forum?id=C03Ajc-NS5W) | [Code](https://github.com/divelab/DIG) |
| Semi-equivariant conditional normalizing flows, with applications to target-aware molecule generation | 2023 | [Paper](https://iopscience.iop.org/article/10.1088/2632-2153/ace58c) | [Code](https://github.com/EyalRozenberg1/se_conditional_flows) |
| Not-So-Optimal Transport Flows for 3D Point Cloud Generation | 2025 | [Paper](https://arxiv.org/abs/2502.12456) | — |
| FlowMol3: Flow Matching for 3D De Novo Small-Molecule Generation | 2025 | [Paper](https://arxiv.org/abs/2508.12629) | [Code](https://github.com/Dunni3/FlowMol) |
| SemlaFlow -- Efficient 3D Molecular Generation with Latent Attention and Equivariant Flow Matching | 2025 | [Paper](https://arxiv.org/abs/2406.07266) | [Code](https://github.com/rssrwn/semla-flow) |
| TFG-Flow: Training-free Guidance in Multimodal Generative Flow | 2025 | [Paper](https://arxiv.org/abs/2501.14216) | [Code](https://github.com/linhaowei1/TFG-Flow) |
| APPLICATIONS OF MODULAR CO-DESIGN FOR DE NOVO 3D MOLECULE GENERATION | 2025 | [Paper](https://arxiv.org/abs/2505.18392) | — |
| SynCoGen: Synthesizable 3D Molecule Generation via Joint Reaction and Coordinate Modeling | 2026 | [Paper](https://openreview.net/forum?id=VtPiY1TupB) | — |
| Zatom-1: A Multimodal Flow Foundation Model for 3D Molecules and Materials | 2026 | [Paper](https://arxiv.org/abs/2602.22251) | [Code](https://github.com/Zatom-AI/zatom) |
| PropMolFlow: property-guided molecule generation with geometry-complete flow matching | 2026 | [Paper](https://www.nature.com/articles/s43588-025-00946-y) | [Code](https://github.com/Liu-Group-UF/PropMolFlow) |
| Unified Generative Modeling of 3D Molecules via Bayesian Flow Networks | 2024 | [Paper](https://arxiv.org/abs/2403.15441) | [Code](https://github.com/AlgoMole/GeoBFN) |
| FLOWR: Flow Matching for Structure-Aware De Novo, Interaction- and Fragment-Based Ligand Generation | 2025 | [Paper](https://arxiv.org/abs/2504.10564) | [Code](https://github.com/jcremer/flowr) |

## Energy-based models

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Energy-Based Flow Matching for Generating 3D Molecular Structure | 2025 | [Paper](https://arxiv.org/abs/2508.18949) | — |
| Generative VoxelNet: Learning Energy-Based Models for 3D Shape Synthesis and Analysis | 2022 | [Paper](https://ieeexplore.ieee.org/abstract/document/9294054) | [Code](http://www.stat.ucla.edu/~jxie/3DEBM/) |
| Hybrid Diffusions for Stable Molecular Structure Generation via Explicit Energy-based Model | 2023 | [Paper](https://openreview.net/forum?id=B2juOIstrl) | — |
| PRE-TRAINING MOLECULAR GRAPH REPRESENTATION WITH 3D GEOMETRY | 2022 | [Paper](https://arxiv.org/abs/2110.07728) | [Code](https://github.com/chao1224/GraphMVP) |
| Deep reinforcement learning as an interaction agent to steer fragment-based 3D molecular generation for protein pockets | 2023 | [Paper](https://doi.org/10.1093/bib/bbae531) | [Code](https://github.com/ispc-lab/AMG) |
| Energy-based models for atomic-resolution protein conformations | 2020 | [Paper](https://arxiv.org/abs/2004.13167) | — |
| Learning Neural Generative Dynamics for Molecular Conformation Generation | 2021 | [Paper](https://arxiv.org/abs/2102.10240) | [Code](https://github.com/DeepGraphLearning/CGCF-ConfGen) |
| Generating 3D Molecular Structures Conditional on a Receptor Binding Site with Deep Generative Models | 2020 | [Paper](https://arxiv.org/abs/2010.14442) | — |
| Meta-learning of pseudo force field generation and estimation for enhancing 3D molecular property prediction | 2025 | [Paper](https://doi.org/10.1016/j.patcog.2025.111531) | [Code](https://github.com/Yufei-Luo/Mol-MFFGE) |
| Iterated Energy-based Flow Matching for Sampling from Boltzmann Densities | 2024 | [Paper](https://arxiv.org/abs/2408.16249) | — |
| Zero shot molecular generation via similarity kernels | 2025 | [Paper](https://www.nature.com/articles/s41467-025-60963-3) | [Code](https://github.com/RokasEl/simgen) |
| EBM-Fold: Fully-Differentiable Protein Folding Powered by Energy-based Models | 2021 | [Paper](https://arxiv.org/abs/2105.04771) | — |
| VFDiff: SE(3)-Equivariant Vector Field Guided Diffusion Model for Target-Aware Molecule Generation in 3D | 2025 | [Paper](https://openreview.net/forum?id=5YLsnsjgeC) | — |
| CarbonNovo: Joint Design of Protein Structure and Sequence Using a Unified Energy-based Model | 2024 | [Paper](https://proceedings.mlr.press/v235/ren24e.html) | [Code](https://github.com/zhanghaicang/carbonmatrix_public) |

## Text-based models

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Text-guided Diffusion Model for 3D Molecule Generation | 2024 | [Paper](https://arxiv.org/abs/2410.03803) | — |
| Towards 3D Molecule-Text Interpretation in Language Models | 2024 | [Paper](https://arxiv.org/abs/2401.13923) | [Code](https://github.com/lsh0520/3D-MoLM) |
| NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation | 2025 | [Paper](https://arxiv.org/abs/2502.12638) | [Code](https://github.com/acharkq/NExT-Mol) |
| Sculpting molecules in text-3D space: a flexible substructure aware framework for text-oriented molecular optimization | 2025 | [Paper](https://link.springer.com/article/10.1186/s12859-025-06072-w) | — |
| Text-guided small molecule generation via diffusion model | 2024 | [Paper](https://doi.org/10.1016/j.isci.2024.110992) | [Code](https://github.com/lyc0930/TEDMol) |
| Generation of 3D molecules in pockets via a language model | 2024 | [Paper](https://www.nature.com/articles/s42256-023-00775-6) | [Code](https://github.com/stonewiseAIDrugDesign/Lingo3DMol) |
| Geometry Informed Tokenization of Molecules for Language Model Generation | 2024 | [Paper](https://arxiv.org/abs/2408.10120) | — |
| Towards Molecular Conformer Generation with Language Models | 2025 | [Paper](https://openreview.net/forum?id=zmOb9XQtJR) | — |
| 3DSMILES-GPT: 3D molecular pocket-based generation with token-only large language model | 2025 | [Paper](https://doi.org/10.1039/d4sc06864e) | [Code](https://github.com/ashipiling/GPT_3DSMILES) |
| From SMILES to Enhanced Molecular Property Prediction: A Unified Multimodal Framework with Predicted 3D Conformers and Contrastive Learning Techniques | 2024 | [Paper](https://pubs.acs.org/doi/full/10.1021/acs.jcim.4c01240) | [Code](https://github.com/ngphubinh/MM-DTI) |

## Multimodal models

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Chem3DLLM:3DMultimodal Large Language Models for Chemistry | 2025 | [Paper](https://arxiv.org/abs/2508.10696) | — |
| 3M-Diffusion: Latent Multi-Modal Diffusion for Language-Guided Molecular Structure Generation | 2024 | [Paper](https://arxiv.org/abs/2403.07179) | — |
| MolFM: A Multimodal Molecular Foundation Model | 2024 | [Paper](https://arxiv.org/abs/2307.09484) | [Code](https://github.com/BioFM/OpenBioMed) |
| NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation | 2025 | [Paper](https://arxiv.org/abs/2502.12638) | [Code](https://github.com/acharkq/NExT-Mol) |
| 3DGrid-LLM: Token-Level Fusion of Language and 3D Grids for Chemical Multimodal Generation | 2025 | [Paper](https://openreview.net/forum?id=Sm7MrzWHH9) | — |
| Text-guided Diffusion Model for 3D Molecule Generation | 2024 | [Paper](https://arxiv.org/abs/2410.03803) | — |
| MolBind: Multimodal Alignment of Language, Molecules, and Proteins | 2024 | [Paper](https://arxiv.org/abs/2403.08167) | — |
| nach0: multimodal natural and chemical languages foundation model | 2024 | [Paper](https://pubs.rsc.org/en/content/articlehtml/2024/sc/d4sc00966e) | [Code](https://huggingface.co/insilicomedicine/nach0_large) |
| MolLM: a unified language model for integrating biomedical text with 2D and 3D molecular representations | 2024 | [Paper](https://doi.org/10.1101/2023.11.25.568656) | [Code](https://github.com/gersteinlab/MolLM) |
| Sculpting molecules in text-3D space: a flexible substructure aware framework for text-oriented molecular optimization | 2025 | [Paper](https://link.springer.com/article/10.1186/s12859-025-06072-w) | — |
| A text-guided protein design framework | 2025 | [Paper](https://www.nature.com/articles/s42256-025-01011-z) | [Code](https://github.com/chao1224/ProteinDT) |
| Unified multimodal multidomain polymer representation for property prediction | 2025 | [Paper](https://www.nature.com/articles/s41524-025-01652-z) | [Code](https://github.com/huang-qi/Uni-Poly) |
| In-silico 3D molecular editing through physics-informed and preference-aligned generative foundation models | 2025 | [Paper](https://www.nature.com/articles/s41467-025-61323-x) | [Code](https://github.com/issacAzazel/MolEdit) |
| Advancing biomolecular understanding and design following human instructions | 2025 | [Paper](https://www.nature.com/articles/s42256-025-01064-0) | [Code](https://github.com/HICAI-ZJU/InstructBioMol) |
| SurfDock is a surface-informed diffusion generative model for reliable and accurate protein–ligand complex prediction | 2025 | [Paper](https://www.nature.com/articles/s41592-024-02516-y) | [Code](https://github.com/CAODH/SurfDock) |
| Towards 3D Molecule-Text Interpretation in Language Models | 2025 | [Paper](https://arxiv.org/abs/2401.13923) | [Code](https://github.com/lsh0520/3D-MoLM) |
| Learning Joint 2-D and 3-D Graph Diffusion Models for Complete Molecule Generation | 2024 | [Paper](https://ieeexplore.ieee.org/abstract/document/10589299) | [Code](https://github.com/GRAPH-0/JODO) |
| BioMedGPT: An Open Multimodal Large Language Model for BioMedicine | 2024 | [Paper](https://ieeexplore.ieee.org/abstract/document/10767279) | [Code](https://github.com/PharMolix/OpenBioMed) |
| Multi-modal conditional diffusion model using signed distance functions for metal-organic frameworks generation | 2025 | [Paper](https://www.nature.com/articles/s41467-024-55390-9) | [Code](https://github.com/parkjunkil/MOFFUSION) |
| MolFORM: Multi-modal Flow Matching for Structure-Based Drug Design | 2025 | [Paper](https://arxiv.org/abs/2507.05503) | [Code](https://github.com/huang3170/MolForm) |
| MolSpectLLM: A Molecular Foundation Model Bridging Spectroscopy, Molecule Elucidation, and 3D Structure Generation | 2025 | [Paper](https://arxiv.org/abs/2509.21861) | [Code](https://github.com/Eurekashen/SpecMol) |
| Unified Cross-Scale 3D Generation and Understanding via Autoregressive Modeling | 2025 | [Paper](https://arxiv.org/abs/2503.16278) | [Code](https://github.com/dptech-corp/Uni-3DAR) |
| Applications of Modular Co-Design for De Novo 3D Molecule Generation | 2025 | [Paper](https://arxiv.org/abs/2505.18392) | — |
| Generative Flows on Discrete State-Spaces: Enabling Multimodal Flows with Applications to Protein Co-Design | 2024 | [Paper](https://arxiv.org/abs/2402.04997) | — |

## Multiple frameworks

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Geometric Latent Diffusion Models for 3D Molecule Generation (GeoLDM, ICML 2023) | 2023 | [Paper](https://arxiv.org/abs/2305.01140) | [Code](https://github.com/MinkaiXu/GeoLDM) |
| Latent 3D Graph Diffusion (LDM-3DG, ICLR 2024) | 2024 | [Paper](https://openreview.net/pdf?id=cXbnGtO0NZ) | [Code](https://github.com/Shen-Lab/LDM-3DG) |
| Geometry-complete latent diffusion model for 3D molecule generation | 2025 | [Paper](https://doi.org/10.1093/bioinformatics/btaf426) | [Code](https://github.com/charlotte0104/GCLDM-for-3d-molucule-generation) |
| MolFORM: Multi-modal Flow Matching for Structure-Based Drug Design | 2025 | [Paper](https://arxiv.org/abs/2507.05503) | [Code](https://github.com/huang3170/MolForm) |
| MOLUCINATE:AGenerative Model for Molecules in 3D Space | 2021 | [Paper](https://arxiv.org/abs/2109.15308) | — |
| Equivariant Neural Diffusion for Molecule Generation (END, NeurIPS 2024) | 2024 | [Paper](https://doi.org/10.52202/079017-1564) | [Code](https://github.com/frcnt/equivariant-neural-diffusion) |
| Equivariant Flow Matching with Hybrid Probability Transport for 3D Molecule Generation | 2023 | [Paper](https://arxiv.org/abs/2312.07168) | [Code](https://github.com/AlgoMole/MolFM) |
| Scalable Autoregressive 3DMoleculeGeneration | 2025 | [Paper](https://arxiv.org/abs/2505.13791) | — |
| NExT-Mol: 3D Diffusion Meets 1D Language Modeling for 3D Molecule Generation (ICLR 2025) | 2025 | [Paper](https://arxiv.org/abs/2502.12638) | [Code](https://github.com/acharkq/NExT-Mol) |
| A dual-population multi-objective evolutionary algorithm driven by generative adversarial networks for benchmarking and protein-peptide docking | 2024 | [Paper](https://www.sciencedirect.com/science/article/pii/S0010482523011927) | — |
| PocketFlow is a data-and-knowledge-driven structure-based molecular generative model | 2024 | [Paper](https://www.nature.com/articles/s42256-024-00808-8) | [Code](https://github.com/Saoge123/PocketFlow) |

## Multi-objective optimization

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| A 3D generation framework using diffusion model and reinforcement learning to generate multi-target compounds with desired properties | 2025 | [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-025-01035-y) | [Code](https://github.com/Xinol1024/MDRL) |
| A dual-population multi-objective evolutionary algorithm driven by generative adversarial networks for benchmarking and protein-peptide docking | 2024 | [Paper](https://www.sciencedirect.com/science/article/pii/S0010482523011927) | — |
| High-throughput property-driven generative design of functional organic molecules | 2023 | [Paper](https://www.nature.com/articles/s43588-022-00391-1) | [Code](https://github.com/rhyan10/G-SchNetOE62) |
| The development of the generative adversarial supporting vector machine for molecular property generation | 2025 | [Paper](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-025-01052-x) | [Code](https://github.com/LQchem/GASVM.git) |
| Application scenario-oriented molecule generation platform developed for drug discovery | 2024 | [Paper](https://doi.org/10.1016/j.ymeth.2023.12.009) | — |
| DiffMC-Gen: A Dual Denoising Diffusion Model for Multi-Conditional Molecular Generation | 2024 | [Paper](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202417726) | — |
| PMODiff: Physics-Informed Multi-Objective Optimization Diffusion Model for Protein-Specific 3D Molecule Generation | 2025 | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.5c00591) | [Code](https://github.com/zhangyaoxiang/PMODiff/tree/main) |
| Aligning Target-Aware Molecule Diffusion Models with Exact Energy Optimization | 2024 | [Paper](https://doi.org/10.52202/079017-1398) | [Code](https://github.com/MinkaiXu/AliDiff) |
| Rethinking Specificity in SBDD: Leveraging Delta Score and Energy-Guided Diffusion | 2024 | [Paper](https://arxiv.org/abs/2403.12987) | — |
| Training-free Multi-objective Diffusion Model for 3D Molecule Generation (MuDM, ICLR 2024) | 2024 | [Paper](https://openreview.net/pdf?id=X41c4uB4k0) | — |
| A Multi-Objective Molecular Generation Method Based on Pareto Algorithm and Monte Carlo Tree Search | 2025 | [Paper](https://advanced.onlinelibrary.wiley.com/doi/full/10.1002/advs.202410640) | [Code](https://github.com/Liuyifeii/PMMG) |
| Enabling target-aware molecule generation to follow multi objectives with Pareto MCTS | 2024 | [Paper](https://www.nature.com/articles/s42003-024-06746-w) | [Code](https://github.com/CNDOTA/ParetoDrug) |
| DEMO:Diffusion-based Evolutionary Optimization for 3D Multi-Objective Molecular Generation | 2025 | [Paper](https://arxiv.org/abs/2505.11037) | — |

## Materials generation

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Crystal Diffusion Variational Autoencoder for Periodic Material Generation (CDVAE, ICLR 2022) | 2022 | [Paper](https://arxiv.org/abs/2110.06197) | [Code](https://github.com/txie-93/cdvae) |
| Towards Symmetry-Aware Generation of Periodic Materials (SyMat, NeurIPS 2023 Spotlight) | 2023 | [Paper](https://arxiv.org/abs/2307.02707) | [Code](https://github.com/divelab/AIRS) |
| Diffusion probabilistic models enhance variational autoencoder for crystal structure generative modeling (DP-CDVAE, Sci. Reports 2024) | 2024 | [Paper](https://www.nature.com/articles/s41598-024-51400-4) | — |
| Con-CDVAE: A method for the conditional generation of crystal structures (Computational Materials Today 2024) | 2024 | [Paper](https://doi.org/10.1016/j.commt.2024.100003) | [Code](https://github.com/cyye001/Con-CDVAE) |
| Crystal Structure Prediction by Joint Equivariant Diffusion (DiffCSP, NeurIPS 2023) | 2023 | [Paper](https://arxiv.org/abs/2309.04475) | [Code](https://github.com/jiaor17/DiffCSP) |
| Space Group Constrained Crystal Generation (DiffCSP++, ICLR 2024) | 2024 | [Paper](https://arxiv.org/abs/2402.03992) | [Code](https://github.com/jiaor17/DiffCSP) |
| Scalable Diffusion for Materials Generation (UniMat, ICLR 2024) | 2024 | [Paper](https://proceedings.iclr.cc/paper_files/paper/2024/hash/cea5ebedc384c5f4b4ef6b6eb29c197f-Abstract-Conference.html) | [Code](https://unified-materials.github.io/unimat/) |
| Equivariant Diffusion for Crystal Structure Prediction (EquiCSP, ICML 2024) | 2024 | [Paper](https://arxiv.org/abs/2512.07289) | [Code](https://github.com/EmperorJia/EquiCSP) |
| Vector Field Oriented Diffusion Model for Crystal Material Generation (GemsDiff, AAAI 2024) | 2024 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/30224) | [Code](https://github.com/aklipf/gemsdiff) |
| SymmCD: Symmetry-Preserving Crystal Generation with Diffusion Models (ICLR 2025) | 2025 | [Paper](https://arxiv.org/abs/2502.03638) | [Code](https://github.com/sibasmarak/SymmCD) |
| A Periodic Bayesian Flow for Material Generation (CrysBFN, ICLR 2025) | 2025 | [Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/1f09e1ee5035a4c3fe38a5681cae5815-Abstract-Conference.html) | [Code](https://github.com/wu-han-lin/CrysBFN) |
| FlowMM: Generating Materials with Riemannian Flow Matching (ICML 2024) | 2024 | [Paper](https://arxiv.org/abs/2406.04713) | [Code](https://github.com/facebookresearch/flowmm) |
| FlowLLM: Flow Matching for Material Generation with Large Language Models as Base Distributions (NeurIPS 2024) | 2024 | [Paper](https://arxiv.org/abs/2410.23405) | [Code](https://github.com/facebookresearch/flowmm) |
| Crystal structure generation with autoregressive large language modeling (CrystaLLM, Nature Commun. 2024) | 2024 | [Paper](https://www.nature.com/articles/s41467-024-54639-7) | [Code](https://github.com/lantunes/CrystaLLM) |
| Fine-Tuned Language Models Generate Stable Inorganic Materials as Text (CrystalTextLLM, ICLR 2024) | 2024 | [Paper](https://arxiv.org/abs/2402.04379) | [Code](https://github.com/facebookresearch/crystal-text-llm) |
| Space Group Informed Transformer for Crystalline Materials Generation (CrystalFormer, arXiv 2024) | 2024 | [Paper](https://arxiv.org/abs/2403.15734) | [Code](https://github.com/deepmodeling/CrystalFormer) |
| Invariant Tokenization of Crystalline Materials for Language Model Enabled Generation (Mat2Seq, NeurIPS 2024) | 2024 | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/e23133d34964a0a09f6d076fc4b922a4-Abstract-Conference.html) | [Code](https://github.com/deepmodeling/CrystalFormer) |
| MatterGen: a generative model for inorganic materials design (Nature 2025) | 2025 | [Paper](https://www.nature.com/articles/s41586-025-08628-5) | [Code](https://github.com/microsoft/mattergen) |
| MOFDiff: Coarse-grained Diffusion for Metal-Organic Framework Design (arXiv 2023) | 2023 | [Paper](https://arxiv.org/abs/2310.10732) | [Code](https://github.com/microsoft/MOFDiff) |
| GHP-MOFassemble: Diffusion modeling and high throughput screening for novel MOF discovery (arXiv 2023) | 2023 | [Paper](https://arxiv.org/abs/2306.08695) | [Code](https://github.com/hyunp2/ghp_mof) |
| MOFFlow: Flow Matching for Structure Prediction of Metal-Organic Frameworks (ICLR 2025) | 2025 | [Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/f392c6bbb14548df50092f10c9db440f-Abstract-Conference.html) | [Code](https://github.com/nayoung10/MOFFlow) |
| Generative Hierarchical Materials Search (GenMS, NeurIPS 2024) | 2024 | [Paper](https://arxiv.org/abs/2409.06762) | — |
| Periodic Materials Generation using Text-Guided Joint Diffusion Model (TGDMat, ICLR 2025) | 2025 | [Paper](https://proceedings.iclr.cc/paper_files/paper/2025/hash/24e4e3234178a836b70e0aa48827e0ff-Abstract-Conference.html) | [Code](https://github.com/kdmsit/TGDMat) |
| Data-driven discovery of 2D materials by deep generative models (CDVAE-2D, npj Comput. Mater. 2022) | 2022 | [Paper](https://www.nature.com/articles/s41524-022-00923-3) | — |
| Design of New Inorganic Crystals with the Desired Composition Using Deep Learning (JCIM 2023) | 2023 | [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00935) | — |
| Generative design of crystal structures by point cloud representations and diffusion model (PCCD, iScience 2024) | 2024 | [Paper](https://doi.org/10.1016/j.isci.2024.111659) | — |
| 3D Structure Prediction of Atomic Systems with Flow-Based Direct Preference Optimization (FlowDPO, NeurIPS 2024) | 2024 | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/c6fdc94aeb2cb3a426d510d970045dab-Abstract-Conference.html) | [Code](https://github.com/jiaor17/FlowDPO) |

## Additional entries

| Paper / model | Year | Paper | Code / resources |
| --- | --- | --- | --- |
| Assessing conformation validity and rationality of deep learning-generated 3D molecules | 2026 | [Paper](https://www.nature.com/articles/s41467-026-69303-5) | [Code](https://github.com/stonewiseAIDrugDesign/HEAD_TED) |
| 3D Molecule Generation from Rigid Motifs via SE​(3) Flows | 2026 | [Paper](https://arxiv.org/abs/2601.16955) | — |
| Unified modeling of 3D molecular generation via atomic interactions with PocketXMol | 2026 | [Paper](https://doi.org/10.1016/j.cell.2026.01.003) | [Code](https://github.com/pengxingang/PocketXMol) |

## Data notes

The Excel Summary worksheet has 236 rows including its header: 235 data rows and 219 distinct normalized title strings. The 11 category worksheets contain 269 rows with a recorded year plus one PocketFlow entry without a recorded year. Category memberships overlap, and source duplicates are retained in Excel. Nine materials subsection headings are not counted as records. The old README Summary and the uploaded Excel Summary contain the same 235 records after joining line-wrapped titles.

The Markdown catalogue adds the four title strings found only in category sheets and includes three Summary-only titles under Additional entries. Paper/code links have been reconciled by title, with corrections for identified shifted links and outdated identifiers. Where publisher metadata could not be retrieved, the original category links were retained. The accompanying Excel has the same link corrections; its titles, years, row counts and worksheets are preserved.

The catalogue and Excel dataset are shared under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Linked papers, code and other resources retain their own licences.
