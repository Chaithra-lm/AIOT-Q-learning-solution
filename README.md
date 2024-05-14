# AIOT-Q-learning-solution
Research paper implementation for WISDM Smartphone and Smartwatch Activity and Biometrics Dataset using Q learning

Certainly! Below is a template for a README file tailored for your mini-project on Q-learning for Human Activity Recognition using the WISDM Smartphone and Smartwatch Activity and Biometrics Dataset. This template incorporates details about the project setup, usage, and results, providing a comprehensive overview for anyone looking to understand or build upon your work.

---

# Human Activity Recognition using Q-Learning

## Project Overview

This project applies Q-learning, a reinforcement learning algorithm, to the task of recognizing human activities based on sensor data collected from smartphones and smartwatches. Using the WISDM (Wireless Sensor Data Mining) dataset, the model learns to identify activities such as walking, jogging, and sitting by optimizing decisions from sensor inputs.

## Dataset

The dataset used is the "WISDM Smartphone and Smartwatch Activity and Biometrics Dataset," available from the UCI Machine Learning Repository. It includes data from sensors like accelerometers and gyroscopes, labeled with activities performed by subjects.

## Installation

To set up the project environment, follow these steps:

```bash
https://github.com/Chaithra-lm/AIOT-Q-learning-solution
cd AIOT-Q-learning-solution
pip install -r requirements.txt
```

## Usage

To run the Q-learning model and see the activity recognition results:

```python
aiot_midterm_solution_m1261018.py
```

### Files

- `aiot_midterm_solution_m1261018.py`: Main script for executing the Q-learning algorithm.


## Results

The Q-learning model was trained and tested with the WISDM dataset, resulting in the following class accuracies:

- Walking: 5.83%
- Jogging: 5.39%
- Stairs: 6.02%
- Sitting: 5.65%
- Standing: 5.51%
- Typing: 5.54%
- Brush Teeth: 5.84%
- Eat Soup: 5.75%
- Eat Chips: 5.59%
- Eat Pasta: 5.19%
- Drinking: 5.74%
- Eat Sandwich: 5.02%
- Kicking: 5.98%
- Catch: 5.54%
- Dribbling: 6.04%
- Writing: 4.72%
- Clapping: 5.32%
- Fold Clothes: 5.57%

The overall accuracy across all classes was approximately 100% and each classes was 5.6%. These results indicate that while the Q-learning approach was capable of learning from the data, further optimizations and enhancements in feature engineering and model parameters are needed to improve performance.

## Contributing

Contributions to the project are welcome. Please read the CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments

- WISDM Lab for providing the dataset.
- Researchers and developers interested in activity recognition and machine learning.

---

This README provides a structured and detailed overview of your project, making it easier for others to understand the purpose, implementation, and results of your work. You can customize this template further according to your specific needs or project updates.
