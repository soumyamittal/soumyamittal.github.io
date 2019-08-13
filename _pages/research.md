---
permalink: /research/
title: Research
tags: {soumya, mittal, cmu, carnegie, mellon, university, diagnosis, atpg, yield, failure, pfa, machine learning, graduate, phd, roorkee, intel, globalfoundries}
---

Our research is focused towards the development of advanced techniques and algorithms to improve the design, test and diagnosis of integrated circuits, and in turn, facilitate yield analysis and learning. It can be divided in three categories.
{: .text-justify}

---

### Test chip design, test and diagnosis

+ **Ben Niewenhuis, <span style="color:blue">Soumya Mittal</span>, R.D. Blanton, "Multiple-defect diagnosis for logic characterization vehicles", *IEEE European Test Symposium (ETS), 2017***  
   *Abstract*: Previous work on the Carnegie Mellon Logic Characterization Vehicle (CM-LCV) has emphasized the diagnosability properties of a specific class of regular circuits called functional unit block arrays (FUB arrays). This paper describes a multiple-defect, two-level diagnosis procedure that leverages these unique properties of the FUB array to significantly improve diagnosis. This custom diagnosis procedure is implemented and evaluated against commercial diagnosis using a simulated fault-injection experiment involving pairs of injected faults. Custom diagnosis is accurate in 98.2% of the simulations with resolution of at most five for 94.1% of the simulations, improving upon the commercial results of 70.7% accurate and 85.0% with the same level of resolution.
   {: .text-justify}

+ Phillip Fynan, Zeye Liu, ben Niewenhuis, **Soumya Mittal**, Marcin Strojwas, R.D. Blanton, "Logic characterization vehicle design reflection via layout rewiring", *IEEE International Test Conference (ITC), 2016*  
   *Abstract*: Continued scaling of semiconductor fabrication processes has made achieving yield targets increasingly difficult. The design and fabrication of various types of test vehicles is one approach for enabling fast yield learning. Recent work introduced the Carnegie Mellon logic characterization vehicle (CM-LCV). The CM-LCV design methodology uses regularity and existing testability theory to produce logic-based designs that are both highly testable and diagnosable. For the CM-LCV to be effective for yield learning, it must reflect the design characteristics of actual product layouts. Previous work enables incorporation of a standard-cell distribution derived from product designs into an LCV while simultaneously ensuring optimal testability. In this work, a new method is proposed for constructing a CM-LCV that reflects the design characteristics of a product through rewiring either the entire layout or some portion thereof. Four different approaches for rewiring are examined, and the results of each approach are evaluated using a variety of metrics. Experiment results reveal that a product layout can be easily rewired to construct an LCV with reasonable wirelength with reasonable CPU time. Rewiring has many advantages including the transformation of an actual product front-end to a logic-based test chip that has significant transparency to failure. Consequently, this means that front-end masks from an actual product can be re-used to create an effective LCV that is both more reflective and inexpensive to fabricate.
   {: .text-justify}

+  **Soumya Mittal**, Zeye Liu, Ben Niewenhuis, R.D. Blanton, "Test chip design for optimal cell-aware diagnosability", *IEEE International Test Conference (ITC), 2016*  
   *Abstract*: Rapid yield learning in a new manufacturing process via test chips is greatly enhanced with a “Design for Diagnosis” methodology. Prior work on logic-based test chip design demonstrated an implementation flow that ensures 100% intra-cell fault coverage using a minimal test set. However, testability alone does not guarantee good diagnosability. Since diagnosis is inherently a function of design, it is crucial that the design flow ensures defect-level diagnosis resolution and accuracy. This work describes an enhanced implementation methodology for the Carnegie-Mellon Logic Characterization Vehicle (CM-LCV) that ensures optimal cell-aware diagnosability by design. Experiments comparing intra-cell defect diagnosability of the CM-LCV and various benchmark circuits demonstrate the efficacy.
   {: .text-justify}

+  Ben Niewenhuis, Zeye Liu, **Soumya Mittal**, R.D. Blanton, "Logic characterization vehicle design for yield learning", *SEMI Advanced Semiconductor Manufacturing Conference (ASMC), 2016*  
   *Abstract*: A comprehensive investigation of new integrated circuit (IC) design and fabrication technologies is crucial for yielding reliable ICs. This work describes the state of a novel test chip design methodology that results in a test chip referred to as the Carnegie Mellon Logic Characterization Vehicle (CM-LCV). Experiments show that the CM-LCV is able to achieve single stuck line fault coverage of up to 99.4% using an optimal, minimal test set.
   {: .text-justify}

+  Zeye Liu, Ben Niewenhuis, **Soumya Mittal**, R.D. Blanton, "Achieving 100% cell-aware coverage by design", *Design, Automation & Test in Europe Conference & Exhibition (DATE), 2016*  
   *Abstract*: A comprehensive investigation of new integrated circuit design and fabrication technologies is crucial for yielding reliable parts. Prior work proposed a novel logic characterization vehicle called the Carnegie Mellon Logic Characterization Vehicle (CM-LCV), and an implementation flow that ensures a test chip to be product-like with near optimal testability and diagnosability. This work describes an enhanced implementation methodology for CM-LCV that not only guarantees 100% intra-cell defect testability for all standard cells but also reflects the user-specified design characteristics. Experiments comparing intra-cell defect testability between a CM-LCV and various benchmark circuits demonstrate the efficacy of this approach. Specifically, the CM-LCV achieves 92.4% overall input pattern fault coverage and 100% cell-aware fault coverage using an optimal, minimal test set.
   {: .text-justify}

### Logic circuit diagnosis, failure analysis and yield learning
### Machine learning in circuit diagnosis
