# BMI_ST Project

## Project Overview
The BMI_ST project is designed to analyze and process Body Mass Index (BMI) data. It includes a machine learning model, scripts, and multimedia content related to fitness and wellness.

## Directory Structure
- `.git/` - Contains the Git version control information.
- `.gitattributes` - Git attributes for handling file settings in the repository.
- `.gitignore` - Lists files and directories that Git should ignore.
- `bmi.csv` - CSV file containing BMI data.
- `bmi.py` - Python script for processing or analyzing BMI data.
- `bmi_model.pkl` - Pre-trained machine learning model for BMI prediction or analysis.
- `fit.mp3` - Audio file, possibly related to fitness exercises.
- `image1.jpg` - Image file, potentially used within the project.
- `image2.jpg` - Another image file.
- `meditate.mp4` - Video file, likely for meditation or relaxation purposes.
- `requirements.txt` - Lists all the Python dependencies required to run the project.

## Getting Started

### Prerequisites
Ensure that Python is installed on your system. You can install the required dependencies by running:
```bash
pip install -r requirements.txt
```

### Data Analysis/Processing
The `bmi.py` script can be executed to process or analyze the BMI data found in `bmi.csv`.
```bash
python bmi.py
```

### Model Usage
The `bmi_model.pkl` is a pre-trained model that can be loaded using Python to make predictions or further analysis.

Example usage:
```python
import pickle

with open('bmi_model.pkl', 'rb') as model_file:
    model = pickle.load(model_file)
    # Use the model for predictions
```

### Multimedia Content
- `fit.mp3` - Audio guide, possibly for fitness routines.
- `meditate.mp4` - Video guide, likely for meditation or relaxation.

These files can be played using any standard media player.


## Contributing

If you'd like to contribute to this project, please fork the repository on GitHub and submit a pull request.

GitHub: [Ruwanthi2000](https://github.com/Ruwanthi2000)  
Email: [wathsala22dasanayaka@gmail.com](mailto:wathsala22dasanayaka@gmail.com)

