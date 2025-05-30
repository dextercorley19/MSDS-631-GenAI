# Homework Assignment: Beta-VAE on the CelebA Dataset

## Overview

In this assignment, you will train a Beta-VAE (BVAE) on the CelebA dataset using the codebase provided in the [PyTorch-VAE repository](https://github.com/AntixK/PyTorch-VAE). You will set up the environment, prepare the dataset, modify the necessary configurations, run the training process, and analyze the results. Your work will be documented and submitted in a single Jupyter notebook.

## Prerequisites

- Basic knowledge of Python and PyTorch.
- Understanding of Variational Autoencoders (VAEs) and Beta-VAEs.
- Familiarity with Jupyter notebooks and working in a command-line environment.

## Repository

The code you will use is located in the [PyTorch-VAE repository](https://github.com/AntixK/PyTorch-VAE). Specifically, you will work with the Beta-VAE implementation in `models/beta_vae.py`.

If for any reason you have difficulty running the above repo, you can use a helper notebook that I created to help you running the beta VAE network without errors. This notebook is given here: [BetaVAE](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Beta_VAE_Helper.ipynb)

## Steps

### 1. Clone the Repository Or Use the helper notebook

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/AntixK/PyTorch-VAE.git
cd PyTorch-VAE
```

If the you cannot runt he above repo, you can alternativly use the a notebook that I created for you to help you start training a beta VAE.

The helper notebook is given here [BetaVAE](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Beta_VAE_Helper.ipynb)
You can use the above notebook for your homework as a starting point.

### 2. Prepare the CelebA Dataset

Download the small CelebA dataset from the [Kaggle website](https://www.kaggle.com/datasets/therealcyberlord/50k-celeba-dataset-64x64). Extract the dataset and place it in a directory, noting the path.


### 3. Create a Jupyter Notebook

Create a new Jupyter notebook in the root directory of the cloned repository. 



### 4. Document Your Workflow

In your Jupyter notebook, document your entire workflow:

1. **Introduction**: Briefly explain the goal of the assignment and the concept of Beta-VAE.
2. **Data Preparation**: Show how you downloaded and prepared the CelebA dataset.
3. **Training**: Include the code to train the Beta-VAE model. You may use the `[run.py](https://github.com/AntixK/PyTorch-VAE/blob/master/run.py)` script provided in the repository. But you can also use a similar training VAE loop to the one we used in the class. Alterntivly you can use the helper notebook [BetaVAE](https://github.com/USFCA-MSDS/MSDS-631-GenAI/blob/main/Beta_VAE_Helper.ipynb) for your starting point.
4. **Results Analysis**: Visualize the reconstructed images, latent space traversals, and loss curves. Discuss your findings.
5. **Experimentation**: Experiment with different beta values and analyze their impact on the results.


After training completes, analyze the results:

- Visualize the reconstructed images and latent space representations.
- Evaluate the model performance using reconstruction loss and KLD loss.
- Experiment with different values of beta to observe its effect on the disentanglement of learned features.

### 5. Conclusion

Summarize your findings and insights gained from the experiment. Include any challenges you faced and how you overcame them.

### 6. Submission

Submit the Jupyter notebook (.ipynb file) that contains all the above sections.

## Notes

- Ensure you follow best practices for coding and experimentation.
- Your notebook should be well-documented and easy to follow.
- Include visualizations and analyses that clearly demonstrate your understanding of Beta-VAE and the CelebA dataset.

## References

- [Beta-VAE Paper](https://openreview.net/forum?id=Sy2fzU9gl)
- [Original Repository](https://github.com/AntixK/PyTorch-VAE)

Good luck with your assignment!

---
