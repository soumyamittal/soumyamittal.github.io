---
permalink: /research/
title: PhD Research
tags: {soumya, mittal, cmu, carnegie, mellon, university, diagnosis, atpg, yield, failure, pfa, machine learning, graduate, phd, roorkee, intel, globalfoundries}
classes: wide
---

My research was focused towards the development of advanced techniques and algorithms to improve the design, test and diagnosis of integrated circuits, and in turn, facilitate yield analysis and learning. It can be divided in three categories.

+ [Logic circuit diagnosis, failure analysis and yield learning](#1)
+ [Machine learning in circuit diagnosis](#2)
+ [Test chip design, test and diagnosis](#3)


## <a name="1"></a>Logic circuit diagnosis, failure analysis and yield learning

Software-based diagnosis analyzes the observed response of a failing circuit to pinpoint potential defect locations and deduce their respective behaviors. It plays a crucial role in finding the root cause of failure so as to minimize (and ideally eliminate) the need for physical failure analysis (PFA), and subsequently facilitates yield analysis, learning and optimization. To improve the quality of diagnosis at a logic-level, a hybrid deterministic-statistical physically-aware two-phase diagnosis methodology called [LearnX](https://ieeexplore.ieee.org/document/8791512) is developed. It identifies defects that resemble known fault behaviors in Phase 1, and applies machine learning to distinguish the correct candidate from incorrect ones in Phase 2.


To further improve the resolution and accuracy of diagnosis, LearnX is strengthened by a back-end layout analysis technique called [PADLOC (Physically-aware Defect Localization and Characterization)](https://ieeexplore.ieee.org/document/8267889) and a front-end approach called [NOIDA (NOise-resistant Intra-cell DiAgnosis)](https://ieeexplore.ieee.org/document/8368664). Both methods are applicable to any defect type and can handle defects exhibiting arbitrary characteristics. Instead of using a particular fault model to locate defects, they derive the defect behavior by analyzing the logic activity of the nets surrounding its location.

[Patent](https://patents.google.com/patent/US20210042644A1/en){: .btn .btn--success}
[Book](https://www.amazon.com/Machine-Learning-Support-Diagnosis-System/dp/3031196384){: .btn .btn--success}
[Dissertation](https://kilthub.cmu.edu/articles/thesis/Learning_Enhanced_Diagnosis_of_Logic_Circuit_Failures/11962164){: .btn .btn--success}
[VTS'20](https://ieeexplore.ieee.org/document/9107603){: .btn .btn--success}
[ETS'19](https://ieeexplore.ieee.org/document/8791512){: .btn .btn--success}
[VTS'18](https://ieeexplore.ieee.org/document/8368664){: .btn .btn--success}
[ATS'17](https://ieeexplore.ieee.org/document/8267889){: .btn .btn--success}

## <a name="2"></a>Machine learning for volume diagnostics throughput

Logic diagnosis, the process of identifying and locating possible defects in failing integrated circuits, is a key step in yield learning for both technology development and high-volume manufacturing. However, resources can be easily wasted if diagnosis results in no meaningful information, or if the type of diagnostic result is not actionable. It would therefore be very beneficial to have a comprehensive preview of diagnostic outcomes beforehand, which allows diagnosis resources to be prioritized in a more reasonable and effective way.


We have developed a methodology to predict whether a fail log for a given design will result in a diagnosis outcome that is meaningful for the purpose at hand. Different aspects of potential diagnosis outcomes such as the existence of multiple defects, the magnitude of diagnosis resolution, the amount of time a single diagnosis run  takes, and the type of defect (logic vs. scan chain) are predicted using random forest classification and regression.

[TODAES'20](https://dl.acm.org/doi/abs/10.1145/3398267){: .btn .btn--success}
[VTS'19](https://ieeexplore.ieee.org/document/8758642){: .btn .btn--success}
[ITC'18](https://ieeexplore.ieee.org/document/8624884){: .btn .btn--success}

## <a name="3"></a>Test chip design, test and diagnosis

A comprehensive investigation of new integrated circuit (IC) design and fabrication technologies is crucial for yielding reliable ICs. A novel test chip design methodology called the Carnegie Mellon Logic Characterization Vehicle (CM-LCV) is developed that

+ Reflects design characteristics of actual product layouts
+ Guarantees 100% intra-cell defect testability for all standard cells
+ Ensures optimal cell-aware diagnosability by design
+ Diagnoses multiple defects effectively

[EDFA'19](https://www.asminternational.org/web/edfas/news/edfa/-/journal_content/56/10192/36324098/MAGAZINE){: .btn .btn--success}
[ETS'17](https://ieeexplore.ieee.org/document/7968231){: .btn .btn--success}
[ITC'16 (1)](https://ieeexplore.ieee.org/document/7805849){: .btn .btn--success}
[ITC'16 (2)](https://ieeexplore.ieee.org/document/7805850){: .btn .btn--success}
[ASMC'16](https://ieeexplore.ieee.org/document/7491080){: .btn .btn--success}
[DATE'16](https://ieeexplore.ieee.org/document/7459289){: .btn .btn--success}
