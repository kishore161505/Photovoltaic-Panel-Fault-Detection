# Photovoltaic Fault Detection using Machine Learning

## Overview

This project focuses on detecting faults in photovoltaic (PV) systems using machine learning techniques. The notebook performs data preprocessing, exploratory data analysis, model training, evaluation, and prediction of PV system faults.

## Features

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine Learning model training
- Fault prediction
- Model evaluation using performance metrics
- Visualization of results

## Project Structure

```
.
├── Photovoltaic_Fault_Detection.ipynb
├── results/
│   └── <.png files>
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation

Clone the repository:

```bash
git clone https://github.com/kishore161505/photovoltaic-fault-detection.git
```

Navigate to the project directory:

```bash
cd photovoltaic-fault-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Open Jupyter Notebook.

```bash
jupyter notebook
```

2. Open:

```
Photovoltaic_Fault_Detection.ipynb
```

3. Run all cells sequentially.

## Dataset

kaggle: https://www.kaggle.com/datasets/gitenavnath/solar-augmented-dataset

Dataset from kaggle

This dataset contains categorized images of solar panels under various physical and environmental conditions. It is intended for machine learning and computer vision tasks focused on fault detection and classification in solar energy systems.

Directory Structure: The dataset is organized into 6 image folders, each representing a different panel condition:

Clean – Panels with no visible obstructions or faults.

Dusty – Panels partially or fully covered with dust.

Bird_drop_generateds – Panels affected by bird droppings (synthetically generated).

Electrical_damage_generated – Images showing burn marks, hotspots, or grid anomalies (synthetically generated).

Physcial_damage_generated – Cracks, breakage, or physical faults (synthetically generated).

Snow_covered_generated– Panels with snow accumulation (synthetically generated).

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Pytorch

## Results

The notebook trains machine learning models to classify photovoltaic system faults and evaluates their performance using standard classification metrics.

## Future Improvements

- Deep Learning models
- Real-time fault monitoring
- IoT integration
- Web dashboard deployment

## License

This project is intended for educational and research purposes.