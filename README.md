This repository contains exercises I designed for the Machine Learning Lecture held by Prof. Dr. Christian Rieß at the Friedrich-Alexander-University Erlangen-Nürnberg.
The solutions are excluded for obvious reasons.

These exercises cover only parts of the lecture.
The repository contains exercises on gradient inversion attacks in federated learning and dataset poisoning.

For gradient inversion, we implement the approach described in "Inverting Gradients - How easy is it to break privacy in federated learning?" by Jonathan Geiping et al. (https://arxiv.org/abs/2003.14053).
Students are tasked to implement the attack and encouraged to experiment with different hyperparameters to reconstruct images from the gradients they produced during a single training round.
First, the images are known to the students to verify the implementation.
Later, the students receive only the gradients and must reconstruct the images without knowing them beforehand.
The task descriptions, supplementary material, and hints are provided in the `mlsec-ue-grad-inversion` folder. The task description can be found [here](mlsec-ue-grad-inversion/e04.pdf).


For poisoning, we first implement a simple dirty label backdoor attack and evaluete its effectiveness.
Then, we implement a more advanced clean label backdoor attack based on the approach described in "Hidden Trigger Backdoor Attacks" by Aniruddha Saha et al. (https://doi.org/10.1609/aaai.v34i07.6871).
The task descriptions, supplementary material, and hints are provided in the `mlsec-ue-backdoor` folder.
The task description can be found [here](mlsec-ue-backdoor/e03.pdf).