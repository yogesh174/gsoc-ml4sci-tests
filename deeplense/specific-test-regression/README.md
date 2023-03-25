# Challenge - Learning Mass of Dark Matter Halo

Gravitational lensing has been a cornerstone in many cosmology experiments and studies since it was discussed in Einstein’s calculations back in 1936 and discovered in 1979, and one area of particular interest is the study of dark matter via substructure in strong lensing images. In this challenge, we focus on exploring the potential of supervised models in learning the mass of dark matter based on simulated strong lensing images.

### Dataset

The data set consists of strong lensing images for cold dark matter with subhalo substructure. For each lensing image the corresponding fraction of mass in dark matter substructure is provided.

Link to the Dataset: https://drive.google.com/file/d/1hu472ALwGPBcTCXSAM0VoCWmTktg9j-j/view

### Evaluation Metrics

MSE (Mean Squared Error)

The given dataset is divided into 80% of training samples, 10% of validation samples and 10% of test samples.

Train MSE: 5.47e-05

Validation MSE: **5.93e-05** \
Validation R2 score: 0.718

Test MSE: **6.07e-05** \
Test R2 score: 0.717

Tracking the metrics on Weights and Biases: https://wandb.ai/yogesh174/deeplense-regression-test/runs/fhi6j2ij

### Model
A Resnet18 is finetuned to this dataset and the trained model weights can found at - https://drive.google.com/file/d/14H55qDf-wYUlI-WJT6q1qCzucgt2Xk_T/view?usp=sharing
