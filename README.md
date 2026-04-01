# Fractional-Order Modeling in Epidemic Dynamics

This repository presents a project on the use of **fractional-order optimal control models** for infectious diseases, along with their numerical simulation for disease prevention and control.


## Motivation

Classical epidemic models (such as SIR-type models) are typically based on **integer-order differential equations**, which assume that the rate of change of a system depends only on its current state.

However, real-world phenomena, especially in epidemiology, often exhibit:
- **Memory effects**
- **Hereditary behavior**
- **Non-local dynamics**

These characteristics cannot be fully captured using standard models.


## Why Fractional Derivatives?

**Fractional derivatives** generalize classical derivatives to non-integer orders, allowing models to incorporate **history-dependent dynamics**.

In contrast to classical models:
- The future evolution depends not only on the present state, but also on the **entire past trajectory**
- This provides a more realistic description of many biological and physical systems


##  Applications in Infectious Disease Modeling

Fractional-order models have proven particularly useful in epidemiology:

### 1. Modeling Memory Effects
- Disease progression often depends on past exposure and immune response
- Fractional derivatives naturally encode **long-term memory**


### 2. Capturing Complex Transmission Dynamics
- Real epidemics do not always follow simple exponential growth/decay
- Fractional models can better describe:
  - Sub-exponential spread
  - Delayed peaks
  - Persistent infection tails

### 3. Improving Model Accuracy
- Better fitting to real epidemiological data
- More flexibility in representing diverse disease behaviors


### 4. Optimal Control of Epidemics
Fractional models enhance control strategies by allowing:
- More realistic evaluation of interventions (vaccination, treatment, quarantine)
- Incorporation of delayed effects of policies
- Improved prediction of long-term outcomes


##  Role in Prevention and Control

Using fractional-order models, we can:

- Design **optimal intervention strategies**
- Evaluate the **timing and intensity** of control measures
- Reduce infection spread while minimizing economic or social costs

This is particularly relevant for:
- Pandemic preparedness
- Public health policy planning
- Resource allocation in healthcare systems


##  Numerical Simulation

Fractional differential equations are generally **not solvable analytically**, making numerical methods essential.

Key challenges include:
- Non-local operators (dependence on entire history)
- Higher computational cost
- Stability and convergence of numerical schemes

This repository includes:
- Implementation of fractional-order models
- Numerical schemes for simulation
- Experiments demonstrating control strategies


##  Further Reading

For a deeper understanding of fractional derivatives and their applications in epidemic modeling, the reader is encouraged to consult the following references:

-  [Paper 1 Title](https://github.com/AminAPNA/Fractional-Order-Modeling-in-Epidemic-Dynamics/blob/main/Original_Paper.pdf)  
-  [Paper 2 Title](https://github.com/AminAPNA/Fractional-Order-Modeling-in-Epidemic-Dynamics/blob/main/A-Faghih.pdf)
-  [Paper 2 Title](https://github.com/AminAPNA/Fractional-Order-Modeling-in-Epidemic-Dynamics/blob/main/A.%20Faghih.pdf)  

These works provide detailed theoretical foundations and applications of **fractional-order models** in real-world systems.


##  Code Availability

The numerical simulation codes for several **fractional dynamical models of infectious diseases** are available here:

-  [Mathematica / Implementation Repository](https://github.com/AminAPNA/Fractional-Order-Modeling-in-Epidemic-Dynamics/tree/main/mathematica_codes)




