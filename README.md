# Explanation-Based-Handwriting-Verification
Developed a Multi-Task Learning model consisting of Auto-Encoder which maps the input image to 15 features provided by experts. Designed the model to provide a measure of confidence and explanations for this measure of confidence of whether the given handwritten samples are written by the same or different writer; Explanations were provided using cosine similarity method and probabilistic graphical models.


### Objective
<p> The goal of the project is to provide a measure of confidence whether the given handwritten samples are written by the same or different writer and provide explanations for this confidence. We generate explanations for the confidence provided by convolu-tional neural network (CNN) which maps the input image to 15 annotations (features)provided by experts. Our system comprises of: (1) Feature learning network (FLN),a differentiable system, (2) Inference module for providing explanations. Furthermore,inference module provides two types of explanations: (a) Based on cosine similaritybetween categorical probabilities of each feature, (b) Based on Log-Likelihood Ratio(LLR) using directed probabilistic graphical model. We perform experiments using acombination of feature learning network (FLN) and each inference module. We evaluateour system using XAI-AND dataset, containing 13700 handwritten samples and 15 cor-responding expert examined features for each sample. The methods can be extended to provide explanations on other verification tasks like face verification and bio-medical comparison. </p>

### Results
* The accuracy obtained using Cosine-similarity method for explainability using different datasets:
! (https://github.com/ravi-teja-sunkara/Explanation-Based-Handwriting-Verification/blob/master/Images/Accuracies.JPG)
