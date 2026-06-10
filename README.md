# Bachelor Internship

# Increasing Our Scientific Understanding Using ChatGPT:
## Exploring the Upcoming Research Partner

This repository contains selected notebooks from my BSc research internship in high-energy physics. 
I evaluated how ChatGPT-3.5/4 could support research workflows such as planning, code generation and debugging. 
As part of the project, I implemented and compared neural-network models for a binary classification task on 
simulated high-energy physics event data.

## Abstract
This thesis aims to investigate the impact of current state of the art large language models on increasing
scientific understanding, particularly in the field of particle physics, by developing and evaluating deep
neural networks for classifying four-top scattering events against irreducible background processes. I set
out to create fully connected (FCN), convolution (CNN) and transformer neural networks with the use
of ChatGPT-3.5 and 4. These models were trained and evaluated on simulated LHC data and compared
to reference models based on their AUC score. Most of the research has been done through prompting:
from creating a conceptual roadmap to writing specific code. The development of the different neural
networks were compared to each other to explore interesting behaviour. I found that ChatGPT was able
to produce competitive results. The best performing models achieved AUC scores of 0.8248, 0.8073 and
0.8236 for the FCN, CNN and transformer based architectures respectfully. These differ 0.48−2.5% from
their reference counterparts. ChatGPT is an excellent tool for programming purposes, code debugging
and a general major quality of life asset. It is great at applying standard problem solving methods, it
does however leave room for improvement as it does not give clear and concise responses with increasing
problem complexity. Furthermore it is prone to faulty logic and reasoning as well a lack of internal
consistency. Therefore the user must remain actively engaged, rely on their own expertise and connect
the dots themselves.

## What this repository demonstrates

- Python-based ML experimentation
- Implementation and evaluation of FCN, CNN and Transformer models
- Model comparison against reference/baseline approaches
- Critical use of LLMs for planning, coding, debugging and research assistance

## Tech stack

Python, PyTorch, NumPy, pandas, scikit-learn, Matplotlib, Jupyter notebooks

## Status

Research/coursework code from 2023, lightly cleaned and documented for readability. Not intended as production software.
