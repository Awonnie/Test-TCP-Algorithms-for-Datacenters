# TCP Congestion Control Experiments

## Overview
This repository contains various experiments and simulations related to TCP congestion control, including AIMD (Additive Increase, Multiplicative Decrease), AI-based TCP optimization, and alternative congestion control algorithms for high-speed data centers.

## Features
- **AIMD Simulations**: Traditional and modified AIMD algorithms including logarithmic and square-root-based increase functions.
- **AI-Based TCP Parameter Optimization**: Uses OpenAI API to dynamically optimize congestion control parameters.
- **Graphical Analysis**: Plots and visualizations of congestion window dynamics and fairness metrics.

## Installation
Download Dependencies:
```sh
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook or Python script to execute different experiments:
```sh
python tcp_experiments.py
```

For AI-based parameter tuning, ensure you have an OpenAI API key set up in a `.env` file:
```sh
OPENAI_API_KEY=your_api_key_here
```

## Files
- `tcp_experiments.ipynb` – Jupyter Notebook containing all experiments.
- `requirements.txt` – List of dependencies for the project.
- `.env` – Environment file to store API keys.
- `.svg` – Files of diagrams plotted.

## Results
The project generates plots visualizing TCP congestion window behavior under different scenarios. The AI-assisted approach suggests optimized congestion control parameters for improved fairness and efficiency.

## Acknowledgments
- OpenAI API for AI-based optimization.
- Standard TCP congestion control mechanisms as referenced in networking literature.
