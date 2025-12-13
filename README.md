# Physics-Informed Neural Networks

## Resources accompanying the talk

Physics-Informed Neural Networks (PINNs) combine differential equations with neural networks to model dynamical systems under data scarcity, noise, and physical constraints.
This page collects interactive demos, code, and references used in the talk, with an emphasis on oscillatory systems and latency prediction.

# Interactive demos

These Streamlit apps are meant to be exploratory rather than polished products. They expose model behavior, failure modes, and uncertainty directly.

## Physics-informed latency prediction
Explore how physical constraints improve extrapolation and uncertainty estimates in latency data.
https://physics-informed-latency-pred.streamlit.app/

## Manual hyperparameter tuning for a simple harmonic oscillator
A deliberately simple setting to understand how PINNs respond to architectural and loss-weight choices.
https://pinnlearning.streamlit.app/

# Code repositories

## Physics-informed latency prediction
End-to-end experiments combining simple physical structure with neural models.
https://github.com/suchitakulkarni/DataScience/tree/main/Physics_Informed_Latency_Prediction

## LSTM-PINN experiments on noisy signals
Tests on oscillatory signals with increasing noise and partial observability.
https://github.com/suchitakulkarni/DataScience/tree/main/LSTM_PINN

# Papers referenced in the talk

These range from foundational PINN work to more recent perspectives on inductive bias and scientific machine learning.

* Raissi et al., Physics-Informed Neural Networks. arXiv:1711.10561
* Greydanus et al., Hamiltonian Neural Networks. arXiv:1906.01563
* Brunton et al., Discovering governing equations from data. arXiv:1509.03580
* Chen et al., Neural Ordinary Differential Equations. arXiv:1806.07366
* Cranmer et al., Lagrangian Neural Networks. arXiv:2003.04630
* Bodner et al., arXiv:2405.13063
* Cranganore et al., arXiv:2507.11589
* Xie et al., arXiv:2504.06588

# Related implementations and teaching material

* Ben Moseley’s harmonic oscillator PINN example
https://github.com/benmoseley/harmonic-oscillator-pinn

* Mini-lecture slides on PINNs and dynamical systems
https://benmoseley.blog/uploads/slides/24_03_imperial-mini-lecture.pdf

# How to use this page

If you are new to PINNs, start with the SHO demo and Raissi et al.
If you are skeptical, inspect the latency experiments and look at where the physics helps and where it does not.
If you care about theory, the Hamiltonian and Lagrangian approaches give useful contrast to loss-based PINNs.
