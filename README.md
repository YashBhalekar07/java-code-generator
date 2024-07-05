
# Finetuned LLama3 8b to Generate Java Codes

This repository contains code for fine-tuning the LLama3 8b model using Alpaca prompts to generate Java codes. The code is based on a Google Colab notebook.

## 🚀 Overview

The provided notebook demonstrates how to fine-tune the LLama3 8b model for generating Java codes using Alpaca prompts. It utilizes the unsloth library for language model operations and the Hugging Face Transformers library for training and inference tasks.

## 🔗 Links
1.[ Google Colab Notebook](https://colab.research.google.com/drive/1FG6MQo3kcc6yNKQj34kxgq7lrZtg0U0l?usp=sharing/)

2.[ Hugging Face Finrtuned Model](https://huggingface.co/rahulAkaVector/java_code_generator_finetuned_model/tree/main)

## 🛠️ Usage

Install necessary packages by executing the following commands:

```bash
  !pip install "unsloth[colab-new] @ git+https://github.com/unslothai/unsloth.git"
  !pip install --no-deps "xformers<0.0.26" trl peft accelerate bitsandbytes
```

## Training the Model

1.Load the LLama3 8b model with pre-defined settings.

2.Format prompts using Alpaca prompt template and load the dataset.

3.Train the model using the provided dataset and Huggingface TRL's SFTTrainer.

## Inference

1.Run inference on the trained model by providing an instruction and input. Leave the output blank for generation.

2.Optionally, use a TextStreamer for continuous inference to see the generation token by token.

## Saving and Loading Fine-tuned Models

1.Save the final model with LoRA adapters for inference.

2.Load the saved LoRA adapters for inference if needed.

## 📝 Notes

1.Adjust parameters and settings as per your requirements.

2.Ensure to replace placeholder file paths with actual paths in the notebook.
    


## 📚 References
1.[ Huggingface Transformers Documentation](https://huggingface.co/docs/transformers/index.html)

2.[ Unsloth GitHub Repository](https://github.com/unslothai/unsloth)

## 🍰 Contribute

Contributions are always welcome! Please create a PR to add 
Github Profile. Feel free to explore and modify the provided notebook as needed for your Java code generation tasks!

## 🛡️ License
1.[ MIT](https://opensource.org/license/MIT)



## 💖 Show your support

Give a ⭐️ if this project helped you!
