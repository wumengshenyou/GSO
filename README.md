# GSO
Our proposed framework, Global Search Optics (GSO), eliminates the need for manual initialization and explores optimal solutions for compact computational imaging systems autonomously.

GSO encompasses two main components: the Fused Optimization Method for Automatic Optical Design (OptiFusion) and the Efficient Physic-aware Joint Optimization (EPJO). 
OptiFusion integrates Simulated Annealing (SA), Genetic Algorithm (GA), and ADAM to automatically search for initial structures with sufficient diversity based on traditional optical design metrics. 
EPJO includes an enhanced differentiable simulation model along with customized memory-efficient techniques, enabling parallel joint optimization of initial structures and image reconstruction networks. 
Furthermore, it accounts for the complex physical constraints of optical systems and the categorical nature of glass materials to ensure manufacturability.

The source code will be made publicly available after the paper is accepted.

![image](overview.pdf)
