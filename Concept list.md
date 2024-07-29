### Fundamentals of Cryptography
Sources
1. Intro to cryptography: https://www.youtube.com/channel/UC1usFRN4LCMcfIV7UjHNuQg. Use the companion book: Understanding cryptography textbook for students by Christof Paar.
2. Harvard intensive course: https://intensecrypto.org/public/index.html
For each topic, understand the theoretical concept to be able to explain it, solve simple exercises
- Encryption and decryption
- Symmetric Key Cryptography 
    - Block ciphers (focus on e.g., AES)
    - Stream ciphers
    - Modes of operation (ECB, CBC, CTR, GCM)
- Public Key Cryptography 
    - RSA algorithm
    - Elliptic Curve Cryptography (ECC)
    - Diffie-Hellman key exchange
- Hash Functions
    - Properties (collision resistance, preimage resistance)
    - Common algorithms (SHA-2, SHA-3)
- Message Authentication Codes (MACs) and Digital Signatures 
    - HMAC
    - RSA and ECDSA signatures
- Random Number Generation
    - True random vs. pseudorandom number generators
    - Cryptographically secure PRNGs
- Key Management 
    - Key generation, distribution, and storage
    - Public Key Infrastructure (PKI)
- Cryptographic Protocols
    - TLS/SSL
- Basic Cryptanalysis
    - Common attack vectors (e.g., man-in-the-middle, replay attacks)
    - Principles of secure system design
- Information Theory Basics
    - Entropy
    - Perfect secrecy and one-time pads
- Zero-Knowledge Proofs 
    - Basic concepts and applications


### Emerging cryptographic techniques
Sources: Conceptual intro here. Read before each topic to get general idea. [https://cdn.governance.ai/Garfinkel_Tour_Of_Emerging_Cryptographic_Technologies.pdf](https://cdn.governance.ai/Garfinkel_Tour_Of_Emerging_Cryptographic_Technologies.pdf)Go through this content: https://intensecrypto.org/public/lec_17_SFE.html
Cryptography boot camp from simons institute for modern research. https://simons.berkeley.edu/workshops/cryptography-boot-camp#simons-tabs
- Homomorphic encryption
- Zero-knowledge proofs
- Secure multi-party computation
- Post-quantum cryptography

### Mathematical foundations
Sources: https://introtcs.org/public/lec_00_1_math_background.html
https://www.khanacademy.org/computing/computer-science/cryptography read the parts of modular arithmetic
Aim to get a conceptual understanding for the concepts below with several  examples
- Number theory: Modular arithmetic + Prime numbers and factorization, Euler's totient function
- Abstract algebra: Finite fields, group theory, elliptic curves
	- Intro to Galois fields: https://youtu.be/x1v2tX4_dkQ?si=F8LE78fnRXpXgBg5
- Probability/statistics: information theory, statistical tests for randomness. 
	- https://www.khanacademy.org/computing/computer-science/informationtheory Focus on modern information theory, learn mental models and be able to give a few examples
- Linear algebra: Matrix operations, vector spaces, eigenvalues and eigenvectors
- Complexity theory: NP-completeness, quantum complexity theory
- Discrete Mathematics: graph theory, combinatorics
- Signal processing: fourier transform, wavelet analysis

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

### Future of neuro
Sources: Alexandra Elbakyan, lesswrong blog posts 
Overview: the future of neurotechnology: https://milan.cvitkovic.net/writing/the_goals_of_neurotechnology/, https://forum.effectivealtruism.org/posts/Qhn5nyRf93dsXodsw/cause-area-differential-neurotechnology-development
Whole brain emulation workshop 2024: https://foresight.org/2024-foresight-neurotech-bci-and-wbe-for-safe-ai-workshop/
- Neural steganography 
- brain-to-brain interfaces and security
- secure neural prosthetics
- cryptographic protocols for mind uploading
- overclocking one's brain
- biometrics 
- Digital consciousness philosophy articles

### Privacy in neurotechnology
read a few review papers on this:
Steinhagen 2020
- Neurorights
- Cognitive liberty
- Mental privacy
- Thought protection
- regulatory frameworks
- dual-use concerns in neurocryptography

_Other content_
### Security basics concepts
- Secure communication protocols
- Virtual Private Networks (VPNs)
- Firewalls and intrusion detection systems
- Man-in-the-middle attacks
### Neuromorphic Computing
- Spiking neural networks
- Neuromorphic hardware
- Brain-inspired algorithms
---
### Projects ideas
Lightweight homomorphic encryption for BCI data processing
Secure Multi-Party Computation for multiplayer BCI uses (to be specified)
Zero-knowledge proofs for BCI authentication
