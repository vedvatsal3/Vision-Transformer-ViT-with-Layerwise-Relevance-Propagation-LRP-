# Vision-Transformer-ViT-with-Layerwise-Relevance-Propagation-LRP-

This project uses the Vision Transformers (ViTs) and Layerwise Relevance Propagation (LRP) to analyze and interpret image classification results. We use a pre-trained ViT model to classify images from the Natural Adversarials (ImageNet-A) dataset and generate attention maps and relevance maps to understand the model's decision-making process

## Team Members
Name	Student ID

Vatsal Mukeshbhai Ved	6352306

Asjad Afnan [Student ID]

## Project Overview
### Tasks
#### Task 1: Image Classification with ViT
Use a pre-trained Vision Transformer (ViT) to classify images from the ImageNet-A dataset.

Identify correctly and incorrectly classified samples.

#### Task 2: Visualize Attention Maps
Extract and visualize attention maps from the ViT model for selected samples.

#### Task 3: Generate Relevance Maps with LRP
Apply Layerwise Relevance Propagation (LRP) using Zennit to generate relevance maps.

Compare relevance maps for correctly and incorrectly classified images.


## Dataset
We use the Natural Adversarials (ImageNet-A) dataset, which contains challenging images designed to test the robustness of models.

Dataset Link: [ImageNet-A GitHub Repository](https://github.com/hendrycks/natural-adv-examples)

Description: The dataset contains 7,500 natural adversarial examples across 200 classes.

## Models and Tools
### Vision Transformer (ViT)

Model Used: google/vit-base-patch16-224

Source: [Hugging Face Model Hub](https://huggingface.co/google/vit-base-patch16-224)

Description: A pre-trained Vision Transformer model fine-tuned on ImageNet.

### Layerwise Relevance Propagation (LRP)
Library Used: Zennit and LXT

LXT Vision Transformer Documentation: https://lxt.readthedocs.io/en/latest/quickstart.html#vision-transformer-openclip

## Results
### Sample Outputs

#### Attention Maps
![image](https://github.com/user-attachments/assets/5426d6f4-5f13-49ab-b4b3-8104f605d2b4)

#### Relevance Maps
![image](https://github.com/user-attachments/assets/5599e46a-6404-4c3a-b77a-58f14476bfa6)

