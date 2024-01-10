# Text-Generation-Using-GPT-2
---
license: openrail
metrics:
- bleu
pipeline_tag: text-generation
tags:
- code
---

## Story Generation Using GPT-2 in Hugging Face
This repository provides an example of how to use the GPT-2 language model in Hugging Face for story generation tasks. GPT-2 is a powerful natural language processing model that can generate human-like text, and Hugging Face is a popular open-source library for working with NLP models.

## Requirements
- Python 3.6 or higher
- Hugging Face transformers library
- PyTorch or TensorFlow

## Installation
- Clone this repository: git clone ```[https://github.com/BaoToan1704/Deep-Learning/Final%20Project](https://github.com/BaoToan1704/Text-Generation-Using-GPT-2)```
- Navigate to the repository directory: ```cd Final Project```
- Install the required libraries: ```pip install -r requirements.txt```

## Usage
- Download the GPT-2 pre-trained model: ```python download_model.py```
- Edit the ```Gpt_2_to_generate_stories.ipynb``` file to include your desired prompt and generate settings.
- Run the ```Gpt_2_to_generate_stories.ipynb file``` to generate text: ```python Gpt_2_to_generate_stories.ipynb```
  
## Customization
You can customize the GPT-2 model and the text generation settings by editing the ```Gpt_2_to_generate_stories.ipynb``` file. For example, you can change the prompt text, the number of tokens to generate, the temperature setting for the model, and more.

## References
- Hugging Face Transformers library: ```https://github.com/huggingface/transformers```
- GPT-2 model by me: ```https://huggingface.co/baotoan2002/GPT-2```
- OpenAI GPT-2 model: ```https://openai.com/models/gpt-2/```

## License
This repository is licensed under the [openrail] License. See the LICENSE file for details.

## Acknowledgments
- Special thanks to the Hugging Face team for their excellent work on the Transformers library.
- Thanks to OpenAI for providing the pre-trained GPT-2 model.
