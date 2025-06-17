# MCTT_Autodiff_CRN
# Learning Chemical Reaction Networks (CRNs)

## Affiliation
**UM-DAE Centre for Excellence in Basic Sciences, Mumbai**  
**Max Planck Institute of Molecular Cell Biology and Genetics, Dresden**  
**Center for Systems Biology Dresden**

## Author
- **Vishvas RANJAN**  
  UM-DAE Centre for Excellence in Basic Sciences, Mumbai

## Supervisors
- **Dr. Abhishek BEHERA**  
  Max Planck Institute of Molecular Cell Biology and Genetics, Dresden
- **Prof. Dr. Ivo F. SBALZARINI**  
  Max Planck Institute of Molecular Cell Biology and Genetics, Dresden

## Thesis Overview
This research explores how living systems learn and adapt through molecular interactions, using Chemical Reaction Networks (CRNs) as a mathematical framework to bridge microscopic chemical processes and macroscopic biological behaviors. The work focuses on stochastic CRNs as computational models for biological learning, particularly in single-celled organisms.

## Research Questions
This thesis explores fundamental questions about biological learning mechanisms:
- How do living systems learn and adapt?
- How can abstract mathematical models unravel molecular complexity?
- Can chemical systems be mathematically "learnable"?
- How can CRNs capture spatial dynamics (e.g., molecular diffusion)?
- What are CRNs' limitations in representing complex systems?

## Research Focus
- **Framework:** Stochastic Chemical Reaction Networks (CRNs)
- **Approach:** Direct application of Markov Chain Tree Theorem (MCTI) to:
  - Compute parameter likelihoods
  - Derive stationary distributions
  - Avoid PDE approximations of chemical master equations
- **Key Insight:** Stochastic CRNs induce finite Markov chains on discrete integer lattices when excluding species birth/death reactions

## Methodology
1. **Inverse Problem Framework:**  
   Recover reaction rate parameters from observed stationary distributions or target distributions
2. **Computational Techniques:**
   - Markov Chain Tree Theorem (MCTI) for distribution calculation
   - Gradient descent with **automatic differentiation** for optimization
   - Gillespie Algorithm verification (\(1/\sqrt{n}\) convergence achieved)
   - Developed learning rule to recover reaction rate from a target data or a target distribution
3. **Learning Approaches:**
   - Brute-force combinatorial search
   - Automatic differentiation + gradient descent
   - Gradient computation using Clamping

## Key Findings
1. Demonstrated mathematical "learnability" of small chemical systems
2. Established MCTI's validity for stationary distributions
3. Developed parameter learning framework for reaction rate constants
4. Executed Clamping method as Sampling in CRN
5. Identified scalability limitations for complex systems

## Challenges and Future Directions
- **Challenge:** Complex distribution forms resist closed-form solutions
- **Challenge:** Computational scalability beyond small systems
- **Path Forward:** Imposing additional structures on CRNs for tractability
- **Biological Relevance:** Focus on cellular-scale learning in single-celled organisms ("chemical soup" abstraction)

## Research Significance
Opens new avenues for modeling biological learning through CRNs, bridging microscopic molecular interactions and macroscopic behaviors in:
- Cellular process modeling
- Nature-inspired AI systems
- Adaptive chemical computing

---
*Thanks for checking out our work!*