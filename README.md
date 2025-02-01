```markdown
# Fake Profile Detection in Social Media

This project leverages machine learning techniques to identify fake profiles on social media platforms, with a primary focus on Twitter. The system uses web scraping, behavioral analysis, and machine learning algorithms to detect fake accounts, minimize online fraud, reduce misinformation, and enhance privacy.

## Project Overview

Fake accounts on social media platforms pose a significant threat to digital security, privacy, and the authenticity of online information. In this project, we have implemented a framework that utilizes web scraping (with Selenium), machine learning (with XGBoost), and behavioral analysis to detect fake profiles in real time.

### Key Features:
- **Web Scraping**: Data extraction using Selenium to collect user profile data.
- **Behavioral Analysis**: Identifies patterns in user behavior to detect anomalies.
- **Machine Learning**: XGBoost classifier, Grid Search CV, SHAP values for interpretability.
- **Real-Time Monitoring**: Constantly scrapes and analyzes profiles in real-time to detect suspicious accounts.
- **Modular Design**: Easily integrates into existing social media platforms.
- **Accuracy and Precision**: High detection accuracy, precision, and recall on real-world datasets.

## Project Setup

To run this project, follow the instructions below to install the necessary dependencies and set up the environment.

### Prerequisites

Ensure you have Python 3.x installed on your system. You can verify your installation with:

```bash
python --version
```

### Installation

1. **Clone the repository:**

   Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/vanshyelekar04/Ml-powered-Fake-Account-Detection--Twitter.git
   cd Ml-powered-Fake-Account-Detection--Twitter
   ```

2. **Create a virtual environment (optional but recommended):**

   Create a new virtual environment to isolate the dependencies:

   ```bash
   python -m venv fake-profile-env
   ```

   Activate the virtual environment:
   - On Windows:
     ```bash
     .\fake-profile-env\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source fake-profile-env/bin/activate
     ```

3. **Install the required dependencies:**

   Use `pip` to install all the dependencies listed in the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

### Files and Structure

- **`app.py`**: The main script where the system starts. It uses the trained model to detect fake profiles.
- **`requirements.txt`**: Contains a list of Python packages required for the project.
- **`data/`**: Directory containing datasets used for training and testing.
- **`html/`**: Folder where output HTML files are saved.
- **`pdf/`**: Folder where output PDF files are saved.
- **`notebooks/`**: Jupyter Notebooks for data analysis and experimentation.
- **`src/`**: Code files for the main program logic (model training, scraping, etc.).

### Usage

1. **Run the script using IPython Notebook (recommended):**

   ```bash
   ipython notebook
   ```

   Open any `.ipynb` file in your browser and run the code.

2. **Run the script using Python:**

   Alternatively, you can run any `.py` script using the terminal:

   ```bash
   python app.py
   ```

### Real-Time Profile Monitoring

This project includes real-time monitoring capabilities, allowing you to scrape and parse profile data continuously to detect suspicious profiles as they emerge.

### Experimental Results

All the experimental results and outputs have been saved in HTML and PDF formats in the `html/` and `pdf/` folders. You can view the detailed performance of the model, including the confusion matrix, ROC curves, and other metrics, there.

### Contributing

Feel free to fork the repository, make changes, and contribute. Pull requests are welcome!

### License

This project is licensed under the MIT License.

### Acknowledgments

- **Machine Learning Libraries**: XGBoost, Scikit-learn, PyBrain, etc.
- **Web Scraping**: Selenium
- **Visualization**: Matplotlib
- **Shapley Additive Explanations**: For model interpretability.

### References

For more details, you can explore the project repository:

[GitHub Repository - Ml-powered-Fake-Account-Detection--Twitter](https://github.com/vanshyelekar04/Ml-powered-Fake-Account-Detection--Twitter)
```
