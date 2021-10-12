---
feature_text: |
    # Research
feature_image: /assets/img/background/landscape.png
excerpt: "An overview of my research"
---

### Projects


##### Learning the reaction cooridnate on-the-fly 

Finding reaction coordinates (RCs) is the key to the success of most enhanced sampling methods. Usually, the finding of RCs requires prior knowledge or human intuition which is not always reliable. I am developing new methods to automate the finding of RC to accelerate the sampling of the configuration space of complex (bio)molecular systems, making it possible to calculate various thermodynamic and kinetic observables. I also apply these methods to study the conformational changes of proteins and ligand dissociation from RNAs or proteins.

The final goal is to develop an algorithm that can automatically achieve efficient sampling of rare events in most biomolecular systems, especially in cases where we have little prior knowledge of the system.

##### Generation of samples from high-dimensional distribution

Generating samples from a high-dimensional distribution is challenging due to the complicated correlation between different degrees of freedom. The development of generative AI provides solutions to this problem. And I want to explore the possibility of applying these AI techniques to the study of biomolecular systems.

From this perspective, I applied the diffusion probabilistic model to learn from MD trajectories. One application of this model is to improve the sampling quality of replica exchange molecular dynamics (REMD). I have shown that this model could learn from replica exchange simulation trajectory and generate samples at any target temperature. 

Besides learning the distribution of structures, I am exploring how to apply this model to learn the distribution of trajectories to capture dynamic information. 



### Publications 

9. [2021]**Wang**, Parmar, Schneekloth Jr. and Tiwary, "Interrogating RNA-small molecule interactions with structure probing and AI augmented-molecular simulations" [[bioRxiv]](https://www.biorxiv.org/content/10.1101/2021.09.28.462207v1.full.pdf) 

8. [2021]**Wang** and Tiwary, "Denoising diffusion probabilistic models for replica exchange" [[arXiv]](https://arxiv.org/pdf/2107.07369.pdf) [[code]](https://github.com/tiwarylab/DDPM_REMD) [[more]](/research/2021/07/15/DDPM_REMD/) 

7. [2020]Pant, **Wang**, Smith, Tajkhorshid and Tiwary, "Confronting pitfalls of AI-augmented molecular dynamics using statistical physics", J. Chem. Phys. (Featured article and issue cover) [[bioRxiv]](https://www.biorxiv.org/content/10.1101/2020.06.11.146985v3.full.pdf)

6. [2020]Smith, **Wang**, Ravindra, Cooley and Tiwary, "Discovering loop conformational flexibility in T4 lysozyme mutants through artificial intelligence aided molecular dynamics", J. Phys. Chem. (special issue on "Machine Learning in Physical Chemistry") [[bioRxiv]](https://www.biorxiv.org/content/10.1101/2020.04.08.032748v2.full.pdf)

5. [2020]**Wang** and Tiwary, "Understanding the role of predictive time delay and biased propagator in RAVE", J. Chem. Phys. (special issue on "Machine Learning Meets Chemical Physics") [[arXiv]](https://arxiv.org/pdf/2002.06099.pdf) 

4. [2020]**Wang**, Ribeiro and Tiwary, "Machine learning approaches for analyzing and enhancing molecular dynamics simulations", Curr. Op. Struc. Bio. [[arXiv]](https://arxiv.org/pdf/1909.11748.pdf) 

3. [2019]**Wang**, Ribeiro and Tiwary, "Past-future information bottleneck framework for simultaneously sampling biomolecular reaction coordinate, thermodynamics and kinetics", Nature Communications [[bioRxiv]](https://www.biorxiv.org/content/10.1101/507822v1.full.pdf) [[code]](https://github.com/tiwarylab/RAVE) 

2. [2018]Ribeiro, Tsai, Pramanik, **Wang** and Tiwary, "Kinetics of Ligand-Protein Dissociation from All-Atom Simulations: Are We There Yet?", Biochemistry (Future of Biochemistry: The international issue), invited perspective article) 

1. [2018]Ribeiro, Bravo, **Wang** and Tiwary, "Reweighted Autoencoded Variational Bayes for Enhanced Sampling (RAVE)", J. Chem. Phys. [[arXiv]](https://arxiv.org/pdf/1802.03420.pdf)
