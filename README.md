# GENAI_Spoo
My hands on learnings for the Gen AI and RAG pipelines.! Learn on the Code as you GO with me! :)

Advancements in GenAI Models: 
A Brief Overview

Introduction
In recent years, Generative Artificial Intelligence (GenAI) models have witnessed remarkable advancements in terms of complexity, dataset size, and training costs. This README provides a breakdown of the key points surrounding these advancements and their implications.

Model Complexity
The complexity of AI models has surged rapidly, exemplified by the evolution from GPT-1 to GPT-4. GPT-4 now surpasses the complexity of a rat brain in terms of the number of parameters. However, it's crucial to note that we are still far from emulating the complexity of the human brain, which boasts 100 times more parameters than GPT-4.

Dataset Size
AI models like GPT-4 have been trained on datasets larger than the content of English Wikipedia. This substantial dataset size suggests their potential for achieving a deep understanding of human language and generating meaningful text. However, the scarcity of text data availability has prompted a shift towards multi-modal AI, integrating visual and audio data for more comprehensive learning.

Training Costs
Developing Large Language Models (LLMs) demands significant financial investment, with GPT-4's training costs estimated at approximately $100 million. This high cost often favors tech giants, potentially limiting innovation and diversity in AI advancements. Moreover, the environmental impact of training LLMs is notable, with energy consumption projected to rise to concerning levels.

Future Directions
To address the challenges posed by increasing model complexity, dataset size limitations, and exorbitant training costs, there is a pressing need for innovation in several areas. This includes the development of more efficient model architectures capable of scaling with dataset size, leveraging multi-modal data for enhanced learning, and advancements in increasing model parameters.

Conclusion
The advancements in GenAI models hold immense potential for revolutionizing various fields, but they also present challenges that must be addressed. By fostering innovation and collaboration, we can overcome these challenges and unlock the full capabilities of AI for the benefit of society.

You can use this README.md file to provide an overview of your project on GitHub, along with the Python code snippet for training a simple neural network model. Feel free to customize it further based on your project's specific goals and requirements.

About the Code:
Key Points:

This code demonstrates the foundation for training an LLM using PyTorch.
It's essential to provide actual text data for meaningful model training.
The trained model can be used for various language tasks like text generation, language understanding, and machine translation after training.

Overview
This implementation includes the following components:

LLM Class (llm.py): Defines the Large Language Model (LLM) class, which consists of an embedding layer, an LSTM layer, and a fully connected layer.

Training Script (train_lm.py): Contains a function to train the LLM using a given dataset. It initializes the LLM, defines the loss function (CrossEntropyLoss), selects the optimizer (Adam), and runs the training loop for a specified number of epochs.

Example Usage
To train the RNN LM, simply run the train_lm.py script. By default, it will generate random text data to train on. You can modify the hyperparameters such as vocabulary size, embedding dimension, hidden dimension, number of layers, number of epochs, and batch size in the script according to your requirements.

Acknowledgments
This project was inspired by the desire to understand and implement basic language modeling techniques using PyTorch. Special thanks to the PyTorch community for their helpful resources and tutorials.

References
PyTorch: https://pytorch.org/
LSTM Explained: https://colah.github.io/posts/2015-08-Understanding-LSTMs/
CrossEntropyLoss Documentation: https://pytorch.org/docs/stable/generated/torch.nn.CrossEntropyLoss.html
Adam Optimizer Documentation: https://pytorch.org/docs/stable/optim.html#torch.optim.Adam

Credits: This implementation was created by Spoorthy Shivani Pabba. If you find it helpful, consider giving it a star on GitHub!