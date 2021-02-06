#### 4. Deep reinforcement learning for automated reinforced concrete structure design

Computer-aided civil structure design methods have been investigated for decades with various optimization techniques and neural networks. This study proposes a novel concept to aid structural design procedures using a reinforcement learning (RL) based approach, with a particular focus on the reinforced concrete (RC) beam design as a case study. We trained an RL agent called Deep deterministic policy gradient (DDPG) with a convolutional neural network (CNN) function approximators. The agent was successfully trained to design simply supported RC beams subject to the American concrete institute (ACI 318) provision without any data-driven supervision. A python-based RC beam design environment was developed and used to simulate RC beam designs with custom reward functions that encourage the agent to minimize the cost by maximizing the reward. The DDPG agent self-learned the cost-effective RC beam design through the 100,000 randomly generated design cases during the training procedure. The trained agent was able to design the RC beam in a cost-effective way with consideration of flexural and shear reinforcement arrangements.

<img src="https://github.com/jhjeongaa/jhjeongaa.github.io/blob/master/_data/r4_rc_rl.png?raw=true" alt="drawing" height="300"/>

* Jeong J. H, Jo H., Deep reinforcement learning for automated reinforced concrete structure design Computer-Aided Civil and Infrastructure Engineering, (in review)

#### 3. Convolutional neural networks for pavement roughness assessment using calibration-free vehicle dynamics

Road roughness is a measure of how uncomfortable a ride is, and provides an important indicator for the needs of roadway maintenance or repavement, which is closely
tied to the state and federal budget prioritization. As such, accurate and timely monitoring of deteriorating road conditions and following maintenance are essential to
improve the overall ride quality on the road. Various technologies, including vehiclemounted laser profiling systems, have been developed and adopted for road roughness
(e.g., IRI—International Roughness Index) measurement; however, their high cost limits their use. While recent advances in smartphone technologies allow us to
use their embedded accelerometers for road roughness monitoring, the complicated process of necessary vehicle calibration hinders the widespread use of the technology
in the actual practices. In this work, a deep learning IRI estimation method is proposed with the goal of using anonymous (i.e., calibration-free) vehicles and their responses
measured by smartphones as road roughness sensors.

<img src="https://github.com/jhjeongaa/jhjeongaa.github.io/blob/master/_data/r3_iri1.png?raw=true?raw=true" alt="drawing" height="300"/>

* Jeong J. H., Jo H., Ditzler G. (2020) Convolutional neural networks for pavement roughness assessment using calibration-free vehicle dynamics. Computer-Aided Civil and Infrastructure Engineering.121.,https://doi.org/10.1111/mice.12546


#### 2. Real-time generic target tracking for structural displacement monitoring under environmental uncertainties via deep learning

While structural displacement provides essential information about static and/or low-frequency dynamic characteristics of structural behaviors, full-scale measurement of absolute displacement in field structures is extremely challenging because of the requirement of fixed reference in most cases. Recent computer vision-based sensing technologies have advanced to the level of reference-free monitoring of full-scale dynamic displacement using generic features of the structure. However, current generic feature-based methods have limited to only short-term or campaign-type monitoring applications due to the intrinsic limitations of the computer-vision sensing under variable environmental conditions. This study investigates deep learning-based approaches for real-time computer-vision sensing that enables displacement monitoring using generic features under harsh environmental uncertainties. Siamese neural networks have been employed among others to address the environmental uncertainty issues, particularly caused by luminous condition change and obstructed vision, without sacrificing real-time processing capability.

<iframe width="600" height = "350" src="https://www.youtube.com/embed/jZO9daNlfEI" frameborder="0" allowfullscreen></iframe>

* Jeong J. H., Jo H., Real-time generic target tracking for long-term structural displacement monitoring under environmental uncertainties via deep learning Structural control and health monitoring, (in review)


#### 1. Wireless soft elastomeric capacitive strain sensor node development

Conventional resistive-type strain sensing methods have limitations in large-area sensing due to their relatively small size. The soft elastomeric capacitive (SEC) sensor is a capacitance-based stretchable electronic strain sensor developed by Dr. Simon Laflamme. SEC has shown distinct advantages for mesoscale sensing over conventional strain-based structural health monitoring (SHM) due to its wide surface coverage capability.

<iframe width="600" height = "350" src="https://www.youtube.com/embed/gAyZwUM00N0" frameborder="0" allowfullscreen></iframe>

Conventional resistive-type strain sensing methods have limitations in large-area sensing due to their relatively small size. The soft elastomeric capacitive (SEC) sensor is a capacitance-based stretchable electronic strain sensor that has larger-area coverage up to several thousand mm2 and easy-to-install capabilities over complex geometries due to its highly elastic characteristics. Recent studies has demonstrated that the SEC sensor has a linearity up to measuring 20% strain and sufficient durability for structural crack monitoring, promising the performance in mesoscale sensing of static/dynamic strain responses for both concrete and steel structures
 While recent advances in wireless sensor technologies have provided an attractive alternative to wired and centralized SHM, the capacitive strain sensing methods have not benefitted from the wireless approaches due to the lack of appropriate hardware element. This study develops a wireless sensor board to use the SEC sensor in combination with a wireless sensor network for SHM by addressing key implementation challenges.

<img src="https://github.com/jhjeongaa/jhjeongaa.github.io/blob/master/_data/r1_sensorboard.png?raw=true" alt="drawing" height="300"/>

<img src="https://github.com/jhjeongaa/jhjeongaa.github.io/blob/master/_data/figureVoltPCAP.png?raw=true" alt="drawing" height="300"/>

* Jeong, J. H., Xu, J., Jo, H., Li, J., Kong, X., Collins, W., ... & Lafamme, S. (2018). Development of wireless sensor node hardware for large-area capacitive strain monitoring. Smart Materials and Structures, 28(1), 015002., https://doi.org/10.1088/1361-665X/aaebc6
