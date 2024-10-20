# AIForge - Redefining AI
Welcome to AI Forge! This repository offers a simple yet powerful Python system designed for training and conversing with custom-trained models using CSV files. Whether you're a beginner eager to explore AI or an expert looking for a flexible tool to craft bespoke conversational models, AI Forge provides the framework to build and interact with your unique AI systems effortlessly.

# Features
- Train custom models on .CSV based corpora
- Converse with your custom models
- VRAM Usage Estimation Algorithm
- Interactive and intuitive user interface
- Supports multiple languages and dialects
- Customizable training parameters for fine-tuning models
- Real-time conversation capabilities
- Detailed documentation and examples
- Export training models for use in other applications
- Lightweight and efficient, suitable for deployment on low-resource devices
- Community-driven support and contributions

# Installation
## Prerequisites
Python 3.10 or newer

## Steps
1. Clone the repository:
```
git clone https://github.com/ConnerAdamsMaine/AIForge
cd AIForge
```

2. Create and activate a virtual environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate # On windows use 'venv\Scripts\activate'
```

3. Install the required libraries:
```
pip install -r requirements.txt
```

# Requirements
[Pandas](https://pandas.pydata.org/) for handling the CSV files
[Numpy](https://numpy.org/)
[Skikit-Learn](https://scikit-learn.org/stable/)
[Tensorflow](https://www.tensorflow.org/)
[Keras](https://keras.io/)

# Usage
1. Prepare your training data in a CSV file.
2. Use the provided scripts to train your model.
3. Start a conversation with your trained model.

## Training
```py
from AIForge import Trainer
trainer = Trainer('path_to_your_csv_file.csv')
model = await trainer.Train()
```

## Conversing
```py
from AIForge import Conversationalist
conversationalist = Conversationalist(model)
response = await conversationalist.converse('Your input here')
print(response)
```

