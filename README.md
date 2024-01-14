# SpamEmailDetection
## Overview

This project implements a Spam Email Detection system using the Multinomial Naive Bayes (MNB) model. It includes both a custom implementation and the Scikit-Learn library's MNB for comparison.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Custom Implementation](#custom-implementation)
- [Scikit-Learn Implementation](#scikit-learn-implementation)
- [Results](#results)
- [Next Steps](#next-steps)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Email spam detection is a common application of machine learning. This project explores the development and comparison of custom and Scikit-Learn implementations of the Multinomial Naive Bayes model for spam detection.

## Installation

 1. Clone the repository:
   ```bash
     git clone https://github.com/yashal-ali/SpamEmailDetection.git
     cd SpamEmailDetection
    #Create a virtual environment (optional but recommended):
    python -m venv venv

 2. Activate the virtual environment:
        
        Windows: venv\Scripts\activate
        Unix or MacOS: source venv/bin/activate

3. Install dependencies:
pip install -r requirements.txt


## Usage
Preprocess your email dataset and save it as a CSV file with columns 'text' and 'label' (1 for spam, 0 for ham).

Train and evaluate the custom implementation:
  python custom_spam_detector.py --dataset your_dataset.csv
Train and evaluate the Scikit-Learn implementation:
  python scikit_learn_spam_detector.py --dataset your_dataset.csv
Results
Detailed results and discussions are provided in the Results & Discussion section of the project documentation.

Next Steps
Explore opportunities for further optimization, hyperparameter tuning, and experimentation with alternative models to enhance spam detection accuracy.

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License.

Contact
For questions or inquiries, please contact yashalalifarooqui30@gmail.com
