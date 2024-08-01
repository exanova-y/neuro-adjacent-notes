
## Computational foundations 
Time estimated: 2 weeks

**Sources** 
pre-reqs refresher and intro to modelling in neuromatch academy https://compneuro.neuromatch.io/tutorials/intro.html
Look in the nma discord server for math prerequisite sources

Tutorials: https://training.incf.org/tutorials

Mathematics for neuroscience: https://www.ictp-saifr.org/wp-content/uploads/2015/05/MathNsci.pdf

- Neuroscience refresher and the types of neuroimaging techniques 
- Linear algebra 
	- Eigen decomposition and singular value decomposition 
	- Matrix calculus and its applications in optimization 
	- Tensor algebra basics 
	- Deliverable: Implement PCA and apply it to neural data 
- Probability and Statistics
	- Maximum likelihood estimation
	- Bayesian inference and parameter estimation 
	- Statistical hypothesis testing in neuroscience
	- Information theoretic measures (entropy, mutual information)
	- Deliverable: Implement a Bayesian decoder for neural spikes 
- Information Theory and Coding
	- Kolmogorov complexity and minimum description length 
	- Rate-distortion theory and its applications in neuroscience
	- Deliverable: Analyze neural coding efficiency using information theoretic measures
- Differential equations for neural modeling
	- Stability analysis of nonlinear systems 
	- Bifurcation theory basics 
	- Numerical methods for solving ODEs/PDEs
	- Deliverable: Analyze the dynamics of a neural mass model
- Optimization theory
	- convex optimization techniques 
	- Gradient descent variants and adaptive methods
	- Deliverable: Implement and compare optimization algorithms for neural network training 
- Model types
	- Modelling practice
why/use: 
code the mathematical concepts to solidify understanding and for interactivity. To gain an intermediate level of understanding, solve problem sets, relate these methods to how they're used in comp neuro papers.
the goal is to reach an intermediate level because this will help you understand the applications in neuroscience more deeply and understand the reasoning between concepts.

### Brain mapping and connectomics
- Neural signal types (action potentials, local field potentials)
- Brain imaging techniques
    - MRI, fMRI, and DTI
    - Electron microscopy for connectomics
    - Optical imaging methods (two-photon microscopy, light-sheet microscopy)
    - Optogenetics and chemogenetics
- Connectomics 
    - Structural and functional connectomes
    - High-resolution connectomics techniques
    - Large-scale brain initiatives: Human Brain Project, BRAIN Initiative, China Brain Project
    - brain emulations at different scales
    - Emulation strategies: bottom-up vs. top-down approaches
    - Computational challenges in WBE
    - Deliverable: Create a small-scale neural network simulation based on connectomic data (12 hours)
- Graph theory
    - Graph theoretical analysis of brain networks
    - Hub identification and rich-club organization
- Brain atlasing and parcellation
    - Standard brain atlases (e.g., Allen Brain Atlas)
    - Automated parcellation techniques
    - Multi-modal integration of brain maps
---
The below concept list is still work in progress
### BCI concepts
- Non-invasive BCI paradigms (P300, SSVEP, Motor Imagery) (1 day)
- Neuromodulation techniques (TMS, tDCS, DBS) (1 day)
### Neural signal processing
Estimated time: 1 week
- Introduction: the future of neurotechnology. https://milan.cvitkovic.net/writing/the_goals_of_neurotechnology/, https://forum.effectivealtruism.org/posts/Qhn5nyRf93dsXodsw/cause-area-differential-neurotechnology-development
- Advanced Fourier techniques (wavelets, multi-taper methods) (1 day)
- Hilbert transform and instantaneous phase/frequency (1 day) 
- Deliverable: Implement a time-frequency analysis tool for EEG data (6 hours)
- Advanced time-frequency analysis 
- Source localization algorithms (EEG/MEG) 
- Blind source separation techniques 
- Adaptive filtering for real-time BCI 
Deliverable: __

To be refined...

### Machine learning in neuro
Time: 4 days
source: https://compneuro.neuromatch.io/tutorials/intro.html machine learning module
Generative models, rl and kernel methods: __
- Kernel methods for neural data
- Generalized linear models
- Dimensionality reduction
- Deep learning
- Reinforcement learning for BCI control
- Generative models
- Autoencoders
Deliverable: Implement a deep learning model for EEG decoding from one of the open datasets.



### Computational models of brain function
- Cognitive architectures
    - ACT-R, SOAR, and other symbolic approaches
    - Hybrid cognitive architectures
    - Emerging neural-symbolic approaches
- Memory systems and models
    - Working memory models
    - Episodic and semantic memory simulations
    - Hippocampal-cortical interactions
- Computational psychiatry
    - Models of neurological and psychiatric disorders
    - Bayesian approaches to brain function and dysfunction
    - Reinforcement learning in mental health
### BCI and WBE fundamentals
Sources: 
- General: 
	- WBE workshop 2023: https://foresight.org/whole-brain-emulation-workshop-2023/ These contain 10 minute clips
	- Benchmarking: https://milan.cvitkovic.net/writing/neurotechnology_numbers_worth_knowing/, dimensionless numbers in brain science: https://www.youtube.com/watch?v=AwXnRTNLAhw
- Signal acquisition and processing. 
	- Recovering missing information during scanning. https://foresight.org/summary/presentation-group-7-recovering-function-from-missing-information-during-scanning-wbe-2023/
- Neural decoding algorithms
- Brain-computer communication protocols
- Emulation models and techniques


---
Extras
### Future of neuro
Sources: Alexandra Elbakyan, lesswrong blog posts 
Whole brain emulation workshop 2024: https://foresight.org/2024-foresight-neurotech-bci-and-wbe-for-safe-ai-workshop/
- Neural steganography 
- brain-to-brain interfaces and security
- secure neural prosthetics
- cryptographic protocols for mind uploading
- overclocking one's brain
- biometrics 
- Digital consciousness philosophy articles

---
Good sources:
BCI
https://sccn.ucsd.edu/wiki/Introduction_To_Modern_Brain-Computer_Interface_Design
https://github.com/NeuroTechX/awesome-bci
https://direct.mit.edu/books/monograph/4013/Analyzing-Neural-Time-Series-DataTheory-and

WBE:
foresight institute workshops

Comp neuro:
Neuromatch Academy - more rigourous