[![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io/)
[![TensorFlow 2.9](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/?hl=pt-br)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=ffffff)](https://jupyter.org/)
[![Python3](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3106/)

# Manuscript Digits Recogition
 
Application of Machine Learning and AI methods, such as Convolutional Neural Networks (CNN) and some preprocessing techniques for building a model capable of recoginizing manuscript digits precisely (PA 4 from Artificial Intelligence Course - DCOMP - UFSJ).

# 1. Requirements

- [Python3](https://python.org) and [pip](https://pip.pypa.io/en/stable/installation/) package manager:

      sudo apt install python3 python3-pip build-essential python3-dev
 
- [virtualenv](https://virtualenv.pypa.io/en/latest/) tool:

      pip install virtualenv

- Libraries: [Keras](https://keras.io/), [TensorFlow](https://www.tensorflow.org/?hl=pt-br), [scikit-learn](https://scikit-learn.org/stable/index.html), [Matplotlib](https://matplotlib.org/), [numpy](https://numpy.org/), [gdown](https://pypi.org/project/gdown/) and [OpenCV](https://opencv.org/);

- Environments: [Jupyter](https://jupyter.org/).

# 2. Setting the Environment

1. Clone the repository

       git clone https://github.com/juliorodrigues07/manuscript_digit_recognition.git

2. Enter the repository's directory

       cd manuscript_digit_recognition

2. Create a virtual environment

       python3 -m venv .venv

3. Activate the virtual environment

       source .venv/bin/activate

4. Install the dependencies

       pip install -r requirements.txt

# 3. Execution

- To visualize the notebook online and run it ([Google Colaboratory](https://colab.research.google.com/)), [click here](https://colab.research.google.com/github/juliorodrigues07/manuscript_digit_recognition/blob/tuning/notebooks/digit_recognition.ipynb):

- To run the notebook locally, run the following command in the _notebooks_ directory:

      jupyter notebook digit_recognition.ipynb

# 4. Project Structure

    .
    ├── README.md                       # Project's documentation
    ├── requirements.txt                # File containing all the required dependencies to run the project
    ├── plots                           # Directory containing all the graph plots generated
    ├── docs                            
    |   ├── Documentação.pdf            <- Detailed documentation about the project
    |   └── LaTeX           
    ├── notebooks                       # Directory containing project's main jupyter notebook
    |   └── digit_recognition.ipynb
    ├── datasets                        # Directory containing all used or generated datasets in the project
    |   └── digits                      # Directory containing own made digits for testing models
    └── models                          # Directory containing all generated models in the project    
        
# 5. Outro

- To uninstall all dependencies, run the following command:

      pip uninstall -r requirements.txt -y

- To deactivate the virtual environment, run the following command:

      deactivate
