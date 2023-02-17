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
    * Outcomes: 
        - The student Sidhart Baveja created a blog on ML for security. [Check it here](https://ml-to-cs.sidharthbaveja.com/)
        - The student Sidharth Anil created a mind map for this paper. [Check it here](https://gitmind.com/app/docs/mo1h217e)

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
