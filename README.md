# Domain Name Generator - LLaMA 3.1 Finetuning

A fine-tuned LLaMA 3.1 8B model for generating creative, memorable domain name suggestions for businesses with confidence scores and safety filtering.


## 🔧 Technical Details

### Model Architecture
- **Base Model**: LLaMA 3.1 8B Instruct
- **Fine-tuning**: LoRA
- **Framework**: Unsloth

### Evaluation Metrics
- **Relevance**: Business description alignment
- **Brandability**: Memorability and professionalism  
- **Structure**: Valid JSON format compliance
- **Safety**: Inappropriate content filtering
- **Privacy**: PII leakage prevention
- **Bias**: Discriminatory content detection

## 🚀 Deployment

### HuggingFace Inference Endpoint


## 📚 Notebooks Guide

### Synthetic Data Generation
- **Purpose**: Create diverse training examples
- **Output**: 119 business scenarios with domain suggestions
- **Features**: Safety examples, edge cases, domain validation

### Finetuning and Eval 
- **Purpose**: Train and evaluate the model
- **Sections**: Data prep, LoRA training, custom evaluation
- **Tracking**: Wandb integration, metric logging

