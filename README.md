# SNN-PINODE: Physics-Informed Neural ODE with Spiking Neural Networks

Official anonymous implementation of the **SNN-PINODE** framework for resilient spatiotemporal forecasting under out-of-distribution (OOD) weather events.

## Key Features
* **Spiking Encoder**: Energy-efficient LIF SNN temporal feature extractor.
* **Adjoint Neural ODE**: $O(1)$ memory consumption backpropagation across multi-horizon prediction spans.
* **Physics Loss Regularization**: Atmospheric state consistency constraints embedded directly into the training dynamics.

## Setup Instructions

```bash
# Clone the repository
git clone [https://github.com/ANONYMOUS/SNN-PINODE.git](https://github.com/ANONYMOUS/SNN-PINODE.git)
cd SNN-PINODE

# Install dependencies
pip install -r requirements.txt

# Run full pipeline and baseline benchmarks
python main.py
```
