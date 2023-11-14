# Air_Quality_Detection_ML

## Introduction
The "Predicting Air Quality for Health Risk Assessment: A Machine Learning Approach" project aims to classifiy the Air Quality Index (AQI) into various categories in line with Sustainability Goals. By utilizing  Decision Trees, Support Vector Machine (SVM) with Radial Basis Function (RBF) kernel, and XGBoost Models along with ARIMA for time series forecasting, this project aims to provide accurate AQI bucket classifications, which are crucial for monitoring environmental quality and public health.

## Features
- Efficient feature selection.
- Use of oversampling techniques to handle imbalanced datasets.
- Cross Validation.
- Implementation of SVM with RBF kernel for high-accuracy classification (before and after oversampling).
- Implementation of Decision Tree Model
- Implementation of XGBoost Model

## Dataset
- Includes a wide range of air quality parameters collected from various monitoring stations. It has been preprocessed and partitioned into training, validation, and test sets to ensure a robust learning process.
- Source: Air quality observations spanning from January 15, 2015, to July 1, 2020 obtained from the Central Pollution Control Board (CPCB), India. 

## Prerequisites
Before running this project, ensure you have the following installed:
- Python
- Pip/Anaconda/Conda for Package Management
- JupyterLab/Jupyter Notebook IDE

Package Requirements:
- Scikit-learn
- Imbalanced-learn (For Oversampling)
- Pandas (For reading data and data manipulation)
- NumPy (For data manipulation
- Matplotlib, Seaborn (For Visualisations)

## Installation
To set up the project environment:

1. Clone the repository:
   ```shell
   git clone https://github.com/divneela/Air_Quality_Detection_ML.git

2. Navigate to the project directory:
   ```shell
   cd Air_Quality_Detection_ML

3. Install the required Python packages. You can do this by running:
   ```shell
   pip install -r requirements.txt

5. Remember to navigate to each folder to view our Notebooks with complete documentation.

## Usage

After installation, you can run the Jupyter Notebooks to see the analysis and models in action:
1. Start JupyterLab or Jupyter Notebook from Anaconda or Terminal:
   ```shell
   jupyter lab
   jupyter notebook
2. Open the .ipynb files within the Jupyter interface in your browser to view and run the code cells.
3. Suggestion: If you want to skip ahead to Model Evaluation, open the ModelEvaluation notebook and run it with access to the saved models.

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgements
* The authors extend their heartfelt thanks to Professor Vishnu Pendyala, whose commitment to intuition-based and continuous learning has profoundly shaped their academic journey in Machine Learning. His approach of emphasizing critical thinking significantly enriched the authors' understanding and contributed to the robustness of this project. The intellectual curiosity sparked in his classes was invaluable.
* Thanks to all the contributors who spend time to help improve this project.
* Special thanks to the data providers and researchers who have made their work available to the community.

## Authors
- Divya Neelamegam - [@divneela](https://github.com/divneela)
- Poojitha Venkat Ram - [@poojithavenkatram](https://github.com/poojithavenkatram)
- Shruti Badrinarayanan - [@shruti-badri-14](https://github.com/shruti-badri-14)
- Sourabh Suresh Kumar - [@](https://github.com/)
- Padhmavathy Cebolu Srinivasan - [@PadhmaCebolu](https://github.com/PadhmaCebolu)
