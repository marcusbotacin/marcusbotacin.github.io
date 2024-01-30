---
title: "Machine Learning-Based CyberDefenses"
collection: teaching
type: "Topics"
permalink: /teaching/ml-1
venue: "TAMU"
date: 2023-01-01
location: "USA"
---

In this course, we will navigate through the applications of ML in the security field: the pros, the cons, and the future yet to come.

## What to expect

* Lots of malware analysis stuff (50% of the course).
* Discussions about ML limits in general.
* To be requested to map the introduced concepts to your own work.

## Topics

* Pitfalls of ML, dataset size, generalization, and more.
* Malware detection, streams, concept drift.
* Adversarial ML (attacks and defenses)
* Biometrics, Authentication, and related applications.
* Large Language Models, GPT-3, and other fun stuff.

## Evaluation/Format
	
* Seminar presentation + competition

### The competition

Let's make a small version of the [MLSEC](mlsec.io) competition, with students playing together to create attacks and defenses.

## Official Course Link

TAMU students can already enroll in CSCE689 via the Howdy! system.

## Course Progress

* Topic 1.1 [Machine Learning for Malware Detection](https://media.kaspersky.com/en/enterprise-security/Kaspersky-Lab-Whitepaper-Machine-Learning.pdf)
    * Concepts:
        - Static vs. Dynamic analysis.
        - Endpoint vs. Cloud-based strategies.
        - Locality Sensitive Hashing (LSH).
        - The role of AV updates.
        - AV scans in the cloud.
        - Non-negative Neural Networks (NNs) against evasion.
    * Outcomes (2023): 
        - The student Sidhart Baveja created a blog on ML for security. [Check it here](https://ml-to-cs.sidharthbaveja.com/)
        - The student Sidharth Anil created a mind map for this paper. [Check it here](https://gitmind.com/app/docs/mo1h217e)
    * Outcomes (2024):
        - The student Ali Seyed created a blog on ML for security. [Check it here](https://medium.com/@seyyedaliayati/machine-learning-for-malware-detection-597067ba00f3)
        - The student Ayushri Jaim created a blog on ML for security. [Check it here](https://ayushrijain.hashnode.dev/machine-learning-for-malware-detection)
* Topic 1.2 [Malware Detection on Highly Imbalanced Data through Sequence Modeling](https://dl.acm.org/doi/10.1145/3338501.3357374)
    * Concepts:
        - Traditional Machine Learning (ML) vs. Deep Learning (DL) algorithms.
        - Imbalance in endpoint files vs. Imbalance in malware repositories.
        - Malware detection as a Natural Language Processing (NLP) problem.
        - The need for having very low False Positives (FPs).
    * Outcomes:
        - The student Soumyajyoti Dutta has been coding some examples on imbalanced data. [Check it here](https://github.com/Soumyajyotidutta/MLProjects/blob/main/MLCyber.ipynb)                                                                   

* Topic 2.1 [Machine Learning (In) Security: A Stream of Problems (1/2)](https://arxiv.org/abs/2010.16045)
	* Concepts:
		- Problem space vs. Feature space.
		- Data leakage and Temporal inconsistency.
		- Label flipping.
		- Under- and Over- sampling (temporally-accurate).
		- Dataset size vs. Dataset diversity.
		- FPR as a target metric.
    * Outcomes:
        - The student Soumyajyoti Dutta created a mind map for this paper. [Check it here](https://soumyajejyoti.netlify.app/Mind%20map.pdf)

* Topic 2.2 [Machine Learning (In) Security: A Stream of Problems (2/2)](https://arxiv.org/abs/2010.16045)
    * Concepts:
		- Concept drift vs. Concept evolution.
		- Cost-sensitive learning.
		- Ensembling and Bagging.
		- The RandomForest non-linearity and the AdaptiveRandomForest drift retraining.
		- One-class classifiers.
		- White-box and Black-box attacks.
		- Substitute model and offline attacks.
		- Gradient-descent attacks in images and malware classifiers.
		- Adversarial retraining.
		- What is a 0-day.
		- Penetration testing: Blue vs. Red teams.
    * Outcomes:
        - The student Dutta created a discussion outline for this paper. [Check it here](https://soumyajejyoti.netlify.app/)

* Topic 3.1 [Dos and Don'ts of Machine Learning in Computer Security (1/2)](https://www.usenix.org/system/files/sec22summer_arp.pdf)
	* Concepts:
		- Sampling bias.
		- AV labels shifting.
		- Base Rate Fallacy.
		- Regional datasets implications.
		- Threat Models.
		- Website fingerprinting.
		- Infection vectors: USB sticks and Autorun.
		- Stuxnet malware.
		- Hardware Trojans.

* Topic 3.2 [Dos and Don'ts of Machine Learning in Computer Security (2/2)](https://www.usenix.org/system/files/sec22summer_arp.pdf)
	* Concepts:
		- Vulnerabilities vs. Malware.
		- Malware campaigns, variants, and attribution.
		- Reputation-based mechanisms: AV whitelisting.
		- Outlier detection: profile-based and abnormal behavior detection.

* Topic 4.1 [Fast & Furious: On the modelling of malware detection as an evolving data stream](https://www.sciencedirect.com/science/article/abs/pii/S0957417422016463)
	* Concepts:
		- Feature extractor retraining.
		- Encodings: 1-hot encoding.
		- Embeddings: TF-IDF, Word2Vec, Graph embeddings.
		- Graph Representations: Call Graphs (CGs), Control Flow Graphs (CFGs), Data Dependency Graphs (DDGs).
		- Concept drift: vocabulary changes.
		- Software Repositories: Dynamic analysis in application marketplaces.
		- Android malware: SMS fraud.
		- Web malware: Clickjacking.
		- Evasion strategies: Dead code insertion
		- Limits of static analysis: Opaque constants.

* Topic 4.2 [DroidEvolver: Self-Evolving Android Malware Detection System](https://ieeexplore.ieee.org/document/8806731)
	* Concepts:
		- Pool of classifiers.
		- Confidence levels.
		- Pseudo-labels.
		- Model poisoning.
		- Backdooring ML models.
		- MLOps and DevSecOps.
		- AV telemetry.

* Topic 5.1 [Transcend: Detecting Concept Drift in Malware Classification Models](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/jordaney)
	* Concepts:
		- Conformal Evaluation.
		- Statistics vs. Probabilities.
		- P-values.
		- Classifider credibility vs. Prediction confidence.
* Topic 5.2 [Transcending TRANSCEND: Revisiting Malware Classification in the Presence of Concept Drift](https://ieeexplore.ieee.org/document/9833659)
	* Concepts:
		- Pipeline of detection strategies.
		- FPs in spam detection.
		- PDF malware, Word malware, and macros.
		- What is a file packer.
		- Evasion techniques: Anti-VM and Sandbox fingerprinting.
		- Attacker strategy: File format migration
		- Server-side Polymorphism.
		- Attack opportunity window and AV response time.
		- Malware types: Botnets and Remote Access Trojans (RATs).      
		- Command and Control (C&C or C2).
		- Infection vectors: 1-click vs. 0-click vulnerability exploits.
* Topic 6.1 [Shallow Security: on the Creation of Adversarial Variants to Evade Machine Learning-Based Malware Detectors](https://dl.acm.org/doi/10.1145/3375894.3375898)
	* Concepts:
		- Raw bytes vs. Feature-based models.
		- MalConv vs. Non-negative MalConv.
		- Adversarial Attacks: Data appending and Data hiding.
		- Packers: Compressors, Crypters, Droppers, and Injectors.
		- Malware Downloaders and URL obfuscation.
		- PE Loading: OS internals, PE headers, fake timestamps, and checksum recomputation..
		- ML biases: Detecting UPX as malware regardless of its content.
		- C&C strategies: domain fronting. 
* Topic 6.2 [No Need to Teach New Tricks to Old Malware: Winning an Evasion Challenge with XOR-based Adversarial Samples](https://dl.acm.org/doi/10.1145/3433667.3433669)
	* Concepts:
		- Obfuscation strategies: XOR encoding and Base64 encoding.
		- Mimicry attacks: Dead imports and Dynamic library resolving.
* Topic 7.1 [Functionality-Preserving Black-Box Optimization of Adversarial Windows Malware](https://ieeexplore.ieee.org/document/9437194)
	* Concepts:
		- Intrusion Detection: The need for minimizing the number of adversarial queries.
		- Adversarial Attacks: Hard-labels vs. Soft-labels.
		- ML Evasion as an optimization problem.
		- Genetic algorithms for minimizing complex formulas.
		- PE files: Entry points vs. Main functions.
		- PE files: Code caves, Slack spaces, Padding, and Patching..
		- Real-world attacks: Malware as a Service.
		- Threat Models: AVs assuming pristine OS installations.
* Topic 7.2 [Mal-LSGAN: An Effective Adversarial Malware Example Generation Model"](https://ieeexplore.ieee.org/document/9685442)
	* Concepts:
		- Generative Adversarial Networks (GANs).
		- Attack Transferability.
		- Image generation: "This person does not exist".
		- Moving Target Defense (MTD).

* Topic 8.1 [EvadeDroid: A Practical Evasion Attack on Machine Learning for Black-box Android Malware Detection](https://arxiv.org/abs/2110.03301)
	* Concepts:
		- Android Reverse Engineering: Smali code.
		- Assembly vs. Bytecode: Compiled vs. Interpreted languages.
		- Attacks: Code gadgets.
		- ML Classification: Markov models and text generation.
		- Android models: GANs against permission-based classifiers.
		- Access control: The absence of native manifest files in Windows.
	* Outcomes
		- The student Brandon Gathright presented a small implementation of the paper approach.

* Topic 8.2 [Adversarial Machine Learning in Image Classification: A Survey Toward the Defender’s Perspective](https://dl.acm.org/doi/10.1145/3485133)
	* Concepts:
		- Adversarial attacks in images: Invisible perturbations.
		- Physical adversarial attacks: Autonomous vehicles.
		- Explainable AI: Shapley values.
		- Optical Character Recognition (OCR)-based SQL Injection.
* Topics 9.1 [Pop Quiz! Can a Large Language Model Help With Reverse Engineering?](https://arxiv.org/abs/2202.01142)
	* Concepts:
		- Reverse Engineering: Concepts and applications.
		- GPT-3 Playground, ChatGPT, Github Copilot, and other LLM-based applications.
		- Davinci, Codex, and other training sets.
		- One-shot vs. Few-shot learning.
		- Discussion on Large Models: Generalization or Overfitting?
		- Google Captcha and OCR.
		- Oracles in query-response systems.
		- Sentiment analysis in textual documents.
		- Usable Security: Pattern-based authentication.
		- Language-based modeling: Grammar-based fuzzing.
* Topic 9.2 [TrojanPuzzle: Covertly Poisoning Code-Suggestion Models](https://arxiv.org/abs/2301.02344)
	* Concepts:
		- Poisoning attacks against LLMs.
		- Discussion: LLMs in the real-world.
		- Sybil attacks.
		- Common Weaknesses Enumeration (CWEs).
		- Popular Vulnerabilities: Path Traversal.
		- Downgrade Attacks: ECB-mode cryptography.
		- Supply Chain attacks: Open-source repository trojanization.
* Topic 10.1 [Examining Zero-Shot Vulnerability Repair with Large Language Models](https://arxiv.org/abs/2112.02125)
	* Concepts:
		- LLMs for bug fix: Should they be perfect or better than humans?
		- LLM's temperature and the amount of randomness.
		- Discussion: Is LLM coding the same as LLM learning the code?
		- Hardware bugs: Glitches.
		- (Secure) Software Engineering: (Security) Regression Testing.
* Topic 10.2 [Lost at C: A User Study on the Security Implications of Large Language Model Code Assistants](https://arxiv.org/abs/2208.09727)
	* Concepts:
		- Complexity metrics: Lines of Code (LoCs) vs. Bugs per Line vs. etc.
		- Bugs vs. Vulnerabilities.
		- Trusted Code Base (TCB).
		- Vulnerability Discovery: Fuzzing.
		- Common Weaknesses Enumeration (CWE).
	* Outcomes:
		- The student Amith Mattar coded an automatic code generation tool. ([Source](https://github.com/amithmkini/codesecurely)) ([Page](https://codesecurely.vercel.app/))

* Topic 11.1 [Online Binary Models are Promising for Distinguishing Temporally Consistent Computer Usage Profile](https://ieeexplore.ieee.org/document/9786768)
	* Concepts:
		- Authentication vs. Authorization.
		- Continuous Authentication.
		- Research Methodology: Online vs. Offline experiments.
		- Malware vs. Goodware: Keyloggers vs. Keystroke authenticators. 
* Topic 11.2 [Passphrase and keystroke dynamics authentication: Usable security](https://www.sciencedirect.com/science/article/pii/S0167404820302017)
	* Concepts:
		- Keystroke Dynamics.
		- Secret Types: Passwords and Passphrashes.
		- Password policies: Best practices and Usable Security.
		- Password Strength: Shannon Entropy.
		- Security Threats: Password leakage.
		- Password Breaking: Brute-force, dictionary, and rainbow tables.
		- Password Storage: Hashing and Salting.
		- Security Threats II: Typosquatting.
* Topic 12.1 [Automatic Yara Rule Generation Using Biclustering](https://arxiv.org/abs/2009.03779)
	* Concepts:
		- Pattern Matching: YARA rules.
		- Taxonomy: 0 days, 1-day, N-day.
		- Efficient rule storage: Bloom filters.
		- Efficient rule matching: Aho-Corasick algorithm.
* Topic 12.2 [DeepSign: Deep learning for automatic malware signature generation and classification](https://ieeexplore.ieee.org/document/7280815)
	* Concepts:
		- ML construction: Denoising AutoEncoder.
		- Malware Behaviors: Behavioral Signatures.
		- Behavior Masking: Distributed Threats.

## Challenge

* Results
	* Defense
		- Syed Wall and Yasir Farrukh won the defense challenge!
	* Attack
		- Veronika Maragulova, Sidharth Baveja, Sidharth Anil, and Soumyajyoti Dutta won the attack challenge!
		- See the winner report [here](https://ml-to-cs.sidharthbaveja.com/competition/)
	

## ChatGPT Fun

* Results:
	* Syed Rizvi and Yasir Farrukh were able tp ,ale ChatGPT to create a Python Ransomware.
		- Prompt: ![Prompt](https://marcusbotacin.github.io/teaching/FIGS/chat-python.png)
		- Execution: ![Sandbox Execution](https://marcusbotacin.github.io/teaching/FIGS/SS.png)

	* Amith KMattar, Chunkai Fu, amd Mason Jerome were able to make ChatGPT create a Dropper.
		- The Tool: ![Tool](https://marcusbotacin.github.io/teaching/FIGS/GPT-1-1.png)
		- Code Generation: ![Code](https://marcusbotacin.github.io/teaching/FIGS/GPT-1-1.png)
