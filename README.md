# RWC-FinTunna

**Author:** RafalW3bCraft

***

## Overview

RWC-FinTunna is a modular Google Colab–compatible project for fine-tuning and integrating Hugging Face models on a Tesla T4 GPU. This repository enables:

- **Advanced code generation** with StarCoder2-3B  
- **Text classification** using RoBERTa Base  
- **Instruction-following chat** via Flan-T5-Small  
- **Scalable extension** to multimodal and image-generation pipelines  

The notebook `RWC_FinTunna.ipynb` guides users through environment setup, data sourcing, model configuration, efficient fine-tuning with Unsloth, PEFT (LoRA), and 4-bit quantization, phase-one training, and placeholders for phase-two integration.

***

## Repository Structure

```text
.
├── RWC_FinTunna.ipynb     # Main Colab notebook with full implementation
└── README.md              # Project overview and usage instructions
```

***

## Prerequisites

- Google Colab runtime with **Tesla T4** GPU  
- Python 3.8+  
- 16 GB RAM (system) recommended  
- Hugging Face account (optional for private models)

***

## Setup & Installation

1. Open `RWC_FinTunna.ipynb` in Google Colab.  
2. Enable GPU runtime: **Runtime → Change runtime type → GPU**.  
3. Run **Cell 1** through **Cell 4** to install dependencies and configure the environment.  
4. Authenticate with Hugging Face (optional) in **Cell 6**.

***

## License

This project is released under the MIT License. See the LICENSE file for details.
