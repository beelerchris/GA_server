# Server-Based Genetic Algorithm

This repository contains code for running a Server-Based Genetic Algoritm (SGA) with workers based on MongoDB for communicating policy seeds.

- The main (or conductor) code generates/loads the initial population, sorts population by average score, performs mutation opterations, and monitors the status of policies.
- The worker code generates the network-based policy from the random seeds and evaluates them on the desired environment.
