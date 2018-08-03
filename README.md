# Concept tagging with WFSTs, SVMs, CRFs, and neural networks
This is the repository for the paper "Concept Tagging for Natural Language Understanding: Two Decadelong Algorithm Development", http://arxiv.org/abs/1807.10661.
Please refer to this paper when using this code for your papers or reports.
It started as a course project for the course of Language Understanding Systems (2017-2018), part of the master course of computer science of the University of Trento.
The course is held by Professor Giuseppe Riccardi, the material can be found at http://disi.unitn.it/~riccardi/page7/page13/page13.html.

In this project we tried out concept tagging on two datasets, ATIS and NL-SPARQL, with many different
architectures, the aim of the project was not to obtain the highest possible F1 score but to test the same task
under many different models, taking into consideration the number of parameters, ease of setup, etc.


For each type of model, we have tried to keep things easy and concise, so that anyone can either
modify them and run on these datasets, or just copy the specific model they need and repurpose it for their own
task.
Most of the scripts are really simple, once they have been run they should either work or tell you
what arguments you are currently not providing, and what you should/could provide.

# Architectures:
    
  - WFSTs, requirements: opengrm, openfst
  - SVMs, requirements: YAMCHA
  - CRFs, requirements: pycrfsuite
  - neural models, requirements: pytorch

![Alt text](/struct.png?raw=true "structure of the repository")
