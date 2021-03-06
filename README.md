# HNB-tutorial
Hierarchical Negative Binomial (HNB) for Analyzing High-Dimensional Human Microbiome Count Data

The bglm function incorporated into the R package BhGLM, available at https://github.com/nyiuab/BhGLM, allows for the fitting of Bayesian hierarchical negative binomial (HNB) models. Rather than performing numerical estimation with MCMC, these models are fit with a fast EM-IWLS algorithm dependent on maximization of posterior modes.  Several types of prior distributions can be implemented on the coefficients including double-exponential, Student's t, mixture double-exponential, and mixture Student's t. These models are particualrly useful for the analysis of high-dimensional human microbiome count data, however, can be applied to many other types of large-scale molecular data (i.e. detecting disease-associated genes or variants, predictive and prognostic modeling of diseases and traits, etc).

Author: Nengjun Yi nyi@uab.edu

Maintainer: Nengjun Yi nyi@uab.edu

Please contact Amanda H Pendegraft at alhall91@uab.edu with any questions regarding the simulation and the application of the HNB tutorial.
