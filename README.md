# 6.8300 Problem Set #5: Representation Learning and Diffusion Models

In this problem set, we'll (1) compare different strategies for representation learning and (2) do a deep-dive into diffusion models.
Much of this problem set requires GPUs--we'll be using Google Colab for GPU access.
To work on this problem set in Google Colab, copy the `pset-5` directory to your Google Drive.
When working on a particular notebook, configure the notebook to use a GPU machine with `Runtime -> Change runtime type -> T4 GPU`.

## Grading

Part 1: Representation learning
 - 20 points

Part 2: Diffusion models
 - Problem 1: 15 points
 - Problem 2: 25 points
 - Problem 3: 25 points
 - Problem 4: 15 points


## Part 1: Representation Learning

In the first part, we'll compare representations from two different representation learning methods.
For this part, we'll be working in `part1/representations.ipynb`.
To get started, open this notebook in Google Colab and follow the instructions there.

### Submission Guidelines for Part 1

The only deliverable for this problem is `part1/representations.py`.
Please submit this file to Gradescope.

## Part 2: Diffusion Models

In this part, we will be working in the four ipynb files in `part2/`, corresponding to each problem. Please submit an aggregated pdf file with answers to and figures generated in **all** problems, along with the four notebooks with your code and running outputs.

### Submission Guidelines for Part 2

Please include your answer to all problems, including formulas, proofs, and the figures generated in each problem, excluding code. You are required to submit the (single) pdf and all (four) notebooks with your code and running outputs. Do not include code in the pdf file. 

Specifically, the pdf should contain:
- Problem 1
  - Formulas and proofs for problem 1.1 and 1.2
  - 4 figures, one for each beta schedule for problem 1.3
  - Answers to the 2 short answer questions about different beta schedules in problem 1.3
- Problem 2
  - The generated figures `results/p2_train_plot.png` and `results/p2_toy_samples.png`
- Problem 3
  - The generated figures `results/mnist_train_plot.png` and `results/image_w{w}.png` (w=0.0, 0.5, 1.0, 2.0, 4.0)
  - Answer to the short answer question about the U-Net architecture
  - Answer to the short answer question about different CFG weight $w$ in problem 3.2
- Problem 4
  - The generated figures `results/sampling_comparison.png`
  - Answer to the short answer question about different samplers and number of steps

### Acknowledgement

Parts of this pset were inspired by
* Berkeley CS294-158, taught by Pieter Abbeel, Wilson Yan, Kevin Frans, and Philipp Wu;
* MIT 6.S184/6.S975, taught by Peter Holderrieth and Ezra Erives;
* The [blog post](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/) about diffusion models by Lilian Weng.
