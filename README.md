# ENGS 27X25 Final Project
By: Camry Gach, Mia Jones, and Abhinav Reddy

## Prerequisites
- Python 3.x
- `uv` package manager (install via [astral](https://docs.astral.sh/uv/getting-started/installation/))

## Setup with uv

1. Create and activate a new virtual environment:
   ```bash
   uv venv
   source .venv/bin/activate  # On Unix/macOS
   # or
   .venv\Scripts\activate     # On Windows
   ```

2. Install project dependencies:
   ```bash
   uv sync
   ```

## Project Structure
- `corpus/`: Directory containing training data
  - `brown-train-sentences.txt`: Training corpus
- `noisy_channel_results.json`: Results from the noisy channel model
- `ENGS_27_Final_Project_Starter.ipynb`: Jupyter notebook with project code and analysis, only accepts lower case letters

Or open the Jupyter notebook for interactive analysis:
```bash
jupyter notebook ENGS_27_Final_Project_Starter.ipynb
```

## Managing Dependencies
- To add a new package:
  ```bash
  uv add package-name
  ```
