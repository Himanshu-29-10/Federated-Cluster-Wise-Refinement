# Federated Cluster-Wise Refinement

## Project Overview
This project simulates a federated learning environment where multiple clients perform local clustering on their datasets and then share and compare their models. The goal is to explore how federated learning can be applied to clustering tasks, allowing clients to benefit from each other's models without sharing raw data.

## Project Aim
The primary aim of this project is to simulate and analyze local data clustering by different clients in a federated learning setup. The project demonstrates how clients can perform clustering on their local datasets and then compare their models through reconstruction errors, enhancing overall model performance without compromising data privacy.

## Observations
- **Client-Specific Clustering:** Each client performs clustering on its dataset, tailored to its specific data distribution.
- **Model Sharing:** Clients share their clustering models rather than raw data, preserving data privacy.
- **Reconstruction Error:** A method for evaluating and comparing the performance of different client models.

## Project Structure
1. **Simulating Local Data Clustering:** Demonstrates how clients perform clustering on their local datasets.
2. **Sharing and Comparing Models:** Simulates the process of sharing models between clients and comparing them using reconstruction error.

## Installation
To set up the project on your local machine, please follow the instructions below:

1. Clone the repository.
2. Run this command on the command prompt (cmd) to install the required dependencies:

   ```bash
   pip install -r requirements.txt
