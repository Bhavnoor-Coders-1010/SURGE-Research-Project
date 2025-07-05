# SURGE-Files

## Aim:

Traditionally, reward processing in the brain has been attributed to regions such as the basal ganglia and prefrontal cortex.  However, recent findings indicate that the primary motor cortex (M1) directly receives reward-related signals, suggesting a localized reinforcement learning (RL) mechanism for movement adaptation. Additionally, certain subpopulations of M1 neurons are sensitive to specific reward types, providing a novel opportunity to enhance brain-computer interfaces (BCIs). By leveraging these reward signals, adaptive BCIs can be developed to improve user control, minimize adaptation difficulty, and enhance real-time neurotechnology applications. 


## Progress:
1. Produced epochs using EEG markers, applying baseline correction, and normalizing signals to allow for faster convergence.
2. Implemented LSTM, EEGNET, and DSCNN+LSTM architectures using categorical cross-entropy loss and Adam optimizer for 200 epochs and obtained a maximum accuracy of 45% using EEGNET approaching the accuracies of S.O.T.A models.
3. Developing Deep Learning models for quantifying M1 reward signals to be used as a reward function for an RL agent.
