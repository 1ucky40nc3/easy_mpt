# easy_mpt
Easy access to the MPT-7B models from Mosaic ML, Inc.

## Installation

Dependencies:
- [Python](https://www.python.org/)
- [Anaconda](https://www.anaconda.com/) or [miniconda](https://docs.conda.io/en/latest/miniconda.html)
### Frontend

Install the frontend with the following commands:
```bash
conda env create -f environment.yml
```

## Usage

### Frontend

#### Manual Usage

You can start the gradio frontend manually with the following commands:
```bash
conda activate easy_mpt-frontend
python src/frontend/app.py
```