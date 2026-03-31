# EE 123 Lab 3: Sampling & Compression — Audio + Image

This lab connects sampling, resampling, and quantization with transform compression (a JPEG-like pipeline).

## Prerequisites

- Python 3.x

## Environment Setup

Install the required packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Lab Structure

| File | Description |
|------|-------------|
| `lab3-sampling-compression.ipynb` | Main lab notebook (Part 0–5) |
| `assets/` | Audio assets (orchestra clip, 44.1 kHz) |

## Getting Started

1. Open `lab3-sampling-compression.ipynb` and work through Parts 0–5
2. Fill in all `# TODO` sections and answer the questions

## Notes

- This lab is a take-home assignment.
- Use `IPython.display.Audio` to listen to audio clips directly in the notebook
- For the JPEG-like compressor, do not call Pillow's JPEG encoder except in the one task where you compare against it
