# LipNet Implementation via PyTorch

A fully working [LipNet](https://arxiv.org/abs/1611.01599) implementation using PyTorch. This repository provides a complete pipeline—from dataset preprocessing to model training—designed to work on the [GRID](https://zenodo.org/records/3625687) dataset.

## Overview

LipNet is a deep learning model for lip-reading that utilizes spatiotemporal convolutions and recurrent networks. This implementation aims to serve as a clear, modular, and extendable reference for both research and practical applications.

## Features

- **Complete Pipeline:** End-to-end code covering dataset preprocessing, model definition, training, and evaluation.
- **PyTorch Implementation:** Leverages PyTorch for flexibility and ease of use.
- **GRID Dataset Support:** Ready-to-run scripts for the GRID dataset.
- **Model Compression (WIP):** Exploration of quantization and pruning techniques.  
  _Note:_ Initial experiments with tools like [Distiller](https://github.com/IntelLabs/distiller) and [MCT](https://github.com/sony/model_optimization) were limited by non-existent RNN support. Future updates may include custom solutions.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/PlatDrake2875/LipNet/
   cd LipNet
   ```
2. **Create a Virtual Environment (Optional but Recommended):**
    ```bash
    python -m venv venv
    source .\venv\Scripts\activate
    ```
3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## TODO
- More detailed documentation
- Add GUI demo
- Finish the model compression
