Experimental Results

Project Configuration

- Dataset: PathMNIST
- Federated clients: 5
- Data distribution: Non-IID Dirichlet (alpha = 0.3)
- Label noise: 40% on Client 0
- Communication rounds: 20
- Local epochs: 1
- Algorithms: FedAvg and FedProx
- FedProx mu: 0.01
- Random seed: 42

Accuracy Comparison

Metric| FedAvg| FedProx
Global Accuracy| 72.12%| 67.63%
Client 0| 79.52%| 75.67%
Client 1| 77.88%| 74.46%
Client 2| 76.45%| 77.81%
Client 3| 52.90%| 43.56%
Client 4| 79.40%| 67.46%

Conclusion

In this experiment, FedAvg achieved higher global accuracy (72.12%) than FedProx (67.63%). FedProx achieved higher accuracy on Client 2. These results reflect the selected dataset partition, noise setting, and training configuration.

Result Files

- "final_accuracy_summary.json"
- "global_accuracy_comparison.png"
- "client_accuracy_comparison.png"

Weights & Biases

"W&B Project Dashboard" (https://forge.coreweave.com/wandb/bushrafarhinshaik-mallareddy-college-of-engineering-and/pathmnist-fedavg-fedprox)

"FedAvg Run" (https://forge.coreweave.com/wandb/bushrafarhinshaik-mallareddy-college-of-engineering-and/pathmnist-fedavg-fedprox/runs/tyuqkhq2)

"FedProx Run" (https://forge.coreweave.com/wandb/bushrafarhinshaik-mallareddy-college-of-engineering-and/pathmnist-fedavg-fedprox/runs/1wtceg0m)
