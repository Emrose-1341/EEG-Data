# EEG Data Analysis Project

This repository contains EEG (electroencephalography) data analysis code and raw data for various cognitive tasks and resting state recordings. This project was completed for class.

## Repository Structure

This repository is organized into multiple branches:

### Branches

- **`main`**: Main repository branch
- **`Raw-resting-State`**: Contains raw resting state EEG data files
- **`Task-Analysis`**: Contains Jupyter notebooks and code for processing and analyzing task-based EEG data

## Task-Analysis Branch

The `Task-Analysis` branch contains comprehensive analysis notebooks for various EEG experiments:

### Analysis Notebooks

- **`Org_data_&_visualize.ipynb`**: Data organization and visualization utilities
- **`Working_Memory_Data_Analysis.ipynb`**: Analysis of working memory task EEG data
- **`Lexcial_ERP.ipynb`**: Event-related potential (ERP) analysis for lexical tasks
- **`MW_ERP.ipynb`**: Mind-wandering ERP analysis
- **`Sleep_Data.ipynb`**: Sleep stage analysis from EEG recordings
- **`FallPrac.ipynb`**: Fall practice task analysis
- **`FallStopSig.ipynb`**: Stop signal task analysis
- **`Img_Demographics.ipynb`**: Image task demographics analysis
- **`Liam_WM.ipynb`**: Additional working memory analysis

### Technologies Used

- **Python**: Primary programming language
- **Jupyter Notebooks**: Interactive data analysis environment
- **Google Colab**: Cloud-based notebook execution
- **Libraries**:
  - `numpy`: Numerical computations
  - `pandas`: Data manipulation and analysis
  - `matplotlib`: Data visualization
  - `seaborn`: Statistical data visualization
  - `scipy`: Scientific computing and statistical functions
  - `openpyxl`: Excel file handling

## Raw-resting-State Branch

Contains raw EEG data files from resting state recordings. These files serve as the foundation for baseline comparisons and resting state network analysis.

## Skills Learned

Through this project, I developed proficiency in:

1. **EEG Data Processing**: Working with neurophysiological time-series data
2. **Event-Related Potential (ERP) Analysis**: Extracting and analyzing brain responses to specific events
3. **Statistical Analysis**: Applying statistical methods to neuroimaging data using Python
4. **Data Visualization**: Creating informative plots and visualizations for EEG data using matplotlib and seaborn
5. **Working Memory Research**: Understanding cognitive task design and analysis for working memory paradigms
6. **Sleep Stage Analysis**: Processing and classifying sleep stages from EEG recordings
7. **Data Organization**: Structuring and managing large datasets for reproducible research
8. **Jupyter Notebook Workflow**: Developing interactive analysis pipelines
9. **Version Control**: Using Git branches to organize different aspects of a research project
10. **Python Data Science Stack**: Mastering pandas, numpy, and visualization libraries for neuroscience applications

## Future Improvements

If continuing this project, I would implement the following improvements:

1. **Automated Preprocessing Pipeline**: Create a standardized preprocessing pipeline for all EEG data (filtering, artifact removal, epoching)
2. **Modular Code Structure**: Refactor notebooks into reusable Python modules and functions for better code organization
3. **Quality Control Metrics**: Implement automated quality control checks for data integrity and artifact detection
4. **Statistical Analysis Enhancement**: Add more sophisticated statistical analyses (e.g., cluster-based permutation tests, multiple comparisons correction)
5. **Documentation**: Add detailed docstrings and markdown explanations within notebooks for better reproducibility
6. **Data Versioning**: Implement proper data versioning and tracking of preprocessing steps
7. **Visualization Improvements**: Create publication-ready figures with consistent styling and formatting
8. **Machine Learning Integration**: Explore machine learning approaches for classification tasks (e.g., sleep stage classification, ERP component detection)
9. **Reproducibility**: Add requirements.txt and environment setup instructions for easier replication
10. **Cross-Task Comparisons**: Develop analysis pipelines to compare findings across different cognitive tasks
11. **Interactive Dashboards**: Create interactive visualizations using Plotly or similar tools for exploratory data analysis
12. **Automated Report Generation**: Build automated report generation for analysis results

## Getting Started

To work with this repository:

1. Clone the repository
2. Check out the desired branch:
   ```bash
   git checkout Raw-resting-State  # For raw data
   git checkout Task-Analysis      # For analysis code
   ```
3. Open the Jupyter notebooks in Google Colab or a local Jupyter environment
4. Ensure required Python packages are installed (numpy, pandas, matplotlib, seaborn, scipy, openpyxl)

## Note

This project was completed for class and represents work in EEG data analysis and cognitive neuroscience research.
