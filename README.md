# ICA Analysis - Dallas AI Summer School

Example code for Dallas AI Summer School 2025 guest lecture. Here I perform ideal customer avatar analysis on (real) unstructured data using text embeddings.

Resources
- [Slides](https://drive.google.com/file/d/1E2DdSh6Gc_l59rV6Lexvc_P4_sDrlV93/view?usp=sharing)

## 🚀 QuickStart

### Prerequisites
- Python 3.12 or higher
- UV package manager (or pip)
- OpenAI API key (saved in .env file)

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ica-analysis-dallasai
```

2. Install dependencies:
```bash
# Using UV (recommended)
uv sync

# Or using pip
pip install -r requirements.txt
```

3. Start Jupyter Lab:
```bash
jupyter lab
```

## 📁 Project Structure

```
├── 1-data_prep.ipynb          # Data preparation and preprocessing
├── 2-ica_analysis.ipynb       # Independent Component Analysis
├── data/
│   ├── reviews.csv            # Review data
│   ├── students_reviews.csv   # Student review data
│   └── students.csv           # Student information
├── pyproject.toml             # Project configuration
└── requirements.txt           # Dependencies
```

## Notebooks

1. **Data Preparation**: Run `1-data_prep.ipynb` to clean and prepare the dataset
2. **ICA Analysis**: Execute `2-ica_analysis.ipynb` to perform Independent Component Analysis