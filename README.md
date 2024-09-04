# Multimodal Large Language Model Adaptation Plan

## Project Goal:

To adapt an existing open-source Transformer-based text large language model (LLM) into a model with native multimodal capabilities, enabling it to process both text and audio data.

## Project Principle

The traditional large model principle is illustrated in the following diagram:
![Image](https://github.com/user-attachments/assets/9e32a203-698a-4532-9d89-44f9d54bf2fe)

We can add audio encoder and decoder modules to the open-source LLM and retrain it to achieve native multimodal capabilities. The principle is illustrated in the following diagrams:

![Image](https://github.com/user-attachments/assets/26f78249-1765-44e7-8875-07ad128b7568)

![Image](https://github.com/user-attachments/assets/382c5173-528e-4754-8767-99e33cf3e174)

The audio encoder and decoder can be extracted from open-source audio models, such as the Transformer-based encoder and decoder from Google's open-source text-to-speech synthesis model.
