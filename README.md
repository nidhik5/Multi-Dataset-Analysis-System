**Multi-Dataset Analysis System**

**Overview**

This Multi-Agent Data Analysis System is an autonomous tool that processes and analyzes datasets from Hugging Face, performs comprehensive Exploratory Data Analysis (EDA), and generates meaningful insights. The system supports multiple datasets, highlights key patterns and anomalies, and produces rich visualizations and reports.
This project is built using the AutoGen framework to emulate inter-agent communication, ensuring modular, intelligent, and autonomous data analysis.
Features

**Multi-Dataset Support**:

Analyze multiple datasets seamlessly in a single execution, saving time and effort.
It allows handling datasets of varying formats and structures effortlessly.
Automatic Report Generation:
Generates detailed, structured analysis reports for each dataset in Markdown format.
Reports include key insights, statistics, and visual outputs for easy understanding.
Visualization:
Creates insightful visualizations like histograms and correlation heatmaps.
These visual aids help uncover trends, anomalies, and relationships in the data.
Extensible Design:
Designed with modularity, making it easy to integrate new datasets or analysis types.
Developers can add custom analysis logic to expand its capabilities over time.

**Supported Datasets**

Currently, the system supports the following datasets:
- emotion: Text emotion classification dataset
- imdb: Movie review sentiment dataset

**Requirements**

The following libraries are required:
Core Data Libraries
datasets>=2.14.0
pandas>=2.0.0
numpy>=1.24.0

Visualization Libraries
matplotlib>=3.7.0
seaborn>=0.12.0
Utilities
python-dateutil>=2.8.2

**Prerequisites**

- Python 3.7+
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn
  - transformers (optional, for advanced NLP tasks)

**Installation**

1. Install required dependencies:
   pip install -r requirements.txt
   
**Output**

For each dataset, the system generates:
- Comprehensive analysis report
- Performance metrics
- Visualizations of key insights
