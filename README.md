This repo is an implementation of a paper by Sebastian Farquhar1,2 ✉, Jannik Kossen1,2, Lorenz Kuhn1,2 & Yarin Gal1 on detecting hallucination (specifically) confabulations with Semantic Entropy.
It works by prompting an LLM on a question multiple times, each time changing the seed and grouping the responses into meaning clusters.
More meaning clusters means more uncertainty implying hallucination. The metric semantic entropy represents this uncertainty.
It is directly proportional to uncertainty.
