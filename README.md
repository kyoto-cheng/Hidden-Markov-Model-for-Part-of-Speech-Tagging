# Hidden-Markov-Model-for-Part-of-Speech-Tagging

## Introduction

In this notebook, you'll use the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a universal tagset. Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

## Tasks

- Review the provided interface to load and access the text corpus
  - For both Most Frequent Class (MFC) tagger and the HMM model we'll build, we need to estimate the frequency of tags & words from the frequency counts of observations in the training corpus.
- Build a Most Frequent Class (MFC) tagger to use as a baseline
  - Implement Pair Counts and Most Frequent Class
- Build an HMM Part of Speech tagger and compare to the MFC baseline
  - Implement Unigram Counts, Bigram Counts, Starting Counts, Ending Counts, and Basic HMM Tagger using the Pomegranate HMM library.
- (Optional) Improve the HMM tagger
