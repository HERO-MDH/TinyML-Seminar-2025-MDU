# TinyML-Workshop-2025-MDU
*Building Efficient AI for the Edge.*

Seminar materials and hands-on notebooks for TinyML Workshop at Mälardalens University (2025 edition).

## What’s inside

- Notebooks
	- `notebooks/TinyML_Pruning.ipynb` — Visual introduction to pruning (unstructured vs structured) and an iterative pruning demo on MNIST using PyTorch.
	- `notebooks/TinyML_Quantization.ipynb` — Quantization concepts and practical workflow.
- Slides
	- See `Slides/` for the seminar slide deck.

## The Power of Edge AI: Key Advantages

These points reflect the seminar’s motivation for on-device ML:

- Benefit 1: Diminished Latency
	- Instantaneous Response: On-device processing eliminates the round-trip delay of sending data to a distant server.
	- Real-Time Experience: Users get rapid, seamless interactions without network lag.
	- Critical for Speed: Essential when immediate action is required (e.g., autonomous vehicles, industrial robotics).

- Benefit 2: Decreased Bandwidth Usage
	- Local Data Processing: Minimize the amount of data transmitted over the internet by processing on-device.
	- Network Efficiency: Preserve network bandwidth, enabling more devices and higher overall traffic capacity.

- Benefit 3: Real-Time Analytics & Operation
	- Immediate Insights: Run inference and basic analytics directly on the device without a central server.
	- Offline Capability: Continue operating with intermittent or no connectivity.
	- Consideration: For massive-scale AI, a hybrid edge–cloud approach may be needed to leverage cloud resources.

## Seminar flow

1. Quantization (slides)
	- Motivation for low-precision inference; numeric formats; PTQ vs QAT.
2. Pruning (slides)
	- Unstructured vs structured pruning; iterative pruning and fine-tuning.
3. Hands-on notebooks
	- `notebooks/TinyML_Quantization.ipynb`
	- `notebooks/TinyML_Pruning.ipynb`
4. NAS & Knowledge Distillation (slides)
	- Session covering NAS and KD concepts.
5. MCU demo (TinyEngine)
	- On-device inference demo using TinyEngine; see `tinyengine-main/` and `tinyengine-main/tutorial/` for references.

The notebooks prioritize pedagogy and reproducibility.

## Getting started

1. Environment: Python 3.11+, PyTorch, TorchVision, Matplotlib, Seaborn, Jupyter (VS Code works well).
2. Data: MNIST is placed under `notebooks/data/MNIST/raw/` for offline use.
3. Open the notebooks from VS Code and run cells top-to-bottom. GPU will be used automatically if available.

The Notebooks can even more conviniently run on Google Colab.


