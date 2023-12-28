# Artificial Stupidity - Markov Chain Style Text Generator

Artificial Stupidity is a Python module that implements a Markov Chain Style Text Generator. This module allows you to create an AI language model, train it on sentences, and generate new text based on the learned patterns.

## Installation

Use pip to install the module:

```
We are currently waiting for PyPI to be open to new package creation.
Until then, please simpily download this repository and place
the ArtificialStupidity directory into your working directory.
```
## How To Use

### 1. Import the Module

```
import ArtificialStupidity as AS
```
### 2. Create a New AI Language Model

```
ai = AS.NewAI()
```
### 3. Train the AI Language Model

```
ai.train("Example sentence to train the language model on.")
```
Repeat the training step with as many sentences as needed.

### 4. Generate Text

```
generated_text = ai.generate()
print(generated_text)
```
### 5. Save and Load the Model

Save the trained AI Language Model to a file:

```
ai.save("FileName.json")
```
Load a saved AI Language Model from a file:

```
ai.load("FileName.json")
```
## Additional Information

- Make sure to train the model with a diverse set of sentences for better results.
- Experiment with different training sentences to generate varied and interesting text.
- Feel free to save and load models to reuse them across different sessions.

Have fun generating text with Artificial Stupidity!

## Credits

- Woodie-07 | Development of the Text Generation System.
- Isaac Cooper | Turning the Text Generation System into a Module & PIP Package.

Have fun generating text with Artificial Stupidity!
