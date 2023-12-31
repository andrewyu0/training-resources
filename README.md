# training-resources

key actionable takeaways from [twitter spaces w nous 7/27](https://twitter.com/yacineMTB/status/1684577539141033984)

ai tools/flow: otter transcript of the twitter spaces -> claude summary, chat -> bing resources

1.  Start by finding a specific task and iteratively train models till you solve it - fastest way to gain intuition

    -   [How to Train a Large Language Model: A Practical Guide](https://dzone.com/articles/custom-training-of-large-language-models-a-compreh) - This blog post provides a step-by-step guide on how to train a large language model from scratch, with tips and tricks on data preparation, model architecture, training configuration, and evaluation.
    -   [How to Train a Large Language Model in 24 Hours](https://research.aimultiple.com/llm-fine-tuning/) - This video tutorial shows how to train a large language model using the Megatron-LM framework on a cluster of GPUs, with examples and code snippets.
    -   [How to Train a Large Language Model in 10 Minutes](https://towardsdatascience.com/how-to-use-large-language-models-llm-in-your-own-domains-b4dff2d08464) - This article explains how to use the Hugging Face Accelerate library to train a large language model on multiple devices with minimal code changes.
2.  Optimize your dev loop - validate end-to-end as fast as possible

    -   [How to Optimize Your Development Loop for Large Language Models](https://medium.com/@atmabodha/pre-training-fine-tuning-and-in-context-learning-in-large-language-models-llms-dd483707b122) - This blog post discusses some best practices and tools for optimizing your development loop when working with large language models, such as using checkpoints, logging metrics, debugging errors, and testing hypotheses.
    -   [How to Use Streamlit to Build Interactive Dashboards for Large Language Models](https://towardsdatascience.com/guiding-a-huge-language-model-lm-to-perform-specific-tasks-prompt-design-and-soft-prompts-7c45ef4794e4) - This video tutorial demonstrates how to use Streamlit, a Python library for creating web apps, to build interactive dashboards for exploring and validating large language models.
    -   [How to Use PyTorch Lightning to Simplify Your Large Language Model Training](https://rentry.org/llm-training) - This article introduces PyTorch Lightning, a high-level framework for PyTorch, that helps you write less boilerplate code and focus more on the logic of your large language model training.
3.  Look at your data extensively - clean/filter it iteratively

    -   [How to Process Data for Large Language Models](https://stackabuse.com/guide-to-fine-tuning-open-source-llms-on-custom-data/) - This report covers some common steps and challenges for processing data for large language models, such as handling junk data, de-duplication, decontamination, toxicity and bias control.
    -   [How to Use Dask to Scale Up Your Data Processing for Large Language Models](https://www.simform.com/blog/completeguide-finetuning-llm/) - This blog post shows how to use Dask, a Python library for parallel computing, to scale up your data processing tasks for large language models, such as reading, filtering, tokenizing, and shuffling data.
    -   [How to Use Pandas Profiling to Explore Your Data for Large Language Models](https://wandb.ai/wandb_gen/llm-data-processing/reports/Processing-Data-for-Large-Language-Models--VmlldzozMDg4MTM2) - This article explains how to use Pandas Profiling, a Python library for generating descriptive statistics and visualizations of your data, to explore your data for large language models and identify potential issues.
4.  Use human prompting to evaluate models during training

    -   [A Complete Introduction to Prompt Engineering for Large Language Models](https://webz.io/blog/machine-learning/structured-web-data-the-key-to-optimized-llm-preprocessing/) - This blog post provides a comprehensive overview of prompt engineering, the art and science of designing effective prompts for large language models, with examples and tips.
    -   [How to Use W&B Artifacts to Track and Evaluate Prompts for Large Language Models](https://webz.io/blog/machine-learning/optimize-llm-data-preprocessing-with-structured-historical-web-data/) - This tutorial shows how to use W&B Artifacts, a feature of Weights & Biases that allows you to track and version your data and models, to track and evaluate prompts for large language models.
    -   [How to Use Prompt Tuning to Fine-Tune Large Language Models with Fewer Parameters](https://www.mihaileric.com/posts/a-complete-introduction-to-prompt-engineering/) - This paper introduces prompt tuning, a method of fine-tuning large language models by learning soft prompts that can guide the model to perform various tasks.
5.  Leverage tools like Weights & Biases for hyperparameter sweeps

    -   [Tune Hyperparameters with W&B Sweeps](https://www.surgehq.ai/blog/how-good-is-hugging-faces-bloom-a-real-world-human-evaluation-of-language-models) - This documentation page explains how to use W&B Sweeps, a feature of Weights & Biases that allows you to automatically search through combinations of hyperparameter values and find the best ones.
    -   [How to Use W&B Sweeps with Hugging Face Transformers](https://www.analyticsvidhya.com/blog/2023/05/how-to-evaluate-a-large-language-model-llm/) - This blog post demonstrates how to use W&B Sweeps with Hugging Face Transformers, a popular library for working with large language models, with code examples and results.
    -   [How to Use W&B Sweeps with PyTorch Lightning](https://arxiv.org/abs/2301.13848) - This video tutorial shows how to use W&B Sweeps with PyTorch Lightning, a high-level framework for PyTorch that simplifies your large language model training.
6.  Fine-tune a pretrained model rather than a downstream model - keep the "blank canvas"

    -   [Fine-Tuning LLMs Made Easy with LoRA and Generative AI-Stable Diffusion (LoRA)](https://learn.microsoft.com/en-us/semantic-kernel/prompt-engineering/) - This blog post introduces LoRA (Low-Rank Adaptation), a method of fine-tuning large language models with fewer parameters and faster convergence, and Generative AI-Stable Diffusion (GASD), a method of generating high-quality texts from large language models.
    -   [Fine-Tuning Large Language Models: A Survey](https://haystack.deepset.ai/blog/beginners-guide-to-llm-prompting) - This paper surveys the recent advances and challenges in fine-tuning large language models, covering topics such as data selection, optimization, regularization, and evaluation.
    -   [Fine-Tuning Large Language Models with Hugging Face](https://hackernoon.com/using-weights-and-biases-to-perform-hyperparameter-optimization) - This documentation page provides a guide on how to fine-tune large language models with Hugging Face, a popular library for working with large language models, with code examples and tutorials.
7.  Use smaller models (e.g. 300M params) for faster experimentation

    -   [How to Use DistilBERT: Smaller, Faster, Cheaper BERT](https://docs.wandb.ai/tutorials/sweeps) - This blog post explains how to use DistilBERT, a smaller and faster version of BERT, a large language model for natural language understanding, with code examples and results.
    -   [How to Use MiniLM: Small and Fast Pre-Trained Models for Natural Language Understanding and Generation](https://wandb.ai/site/articles/running-hyperparameter-sweeps-to-pick-the-best-model-using-w-b) - This paper introduces MiniLM, a family of small and fast pre-trained models for natural language understanding and generation, with experiments and comparisons.
    -   [How to Use TinyBERT: Distilling BERT for Natural Language Understanding](https://wandb.ai/site/articles/introduction-hyperparameter-sweeps) - This paper presents TinyBERT, a method of distilling BERT for natural language understanding tasks, with experiments and analyses.
8.  Consider on-device deployment - constraints lead to more scalable solutions

    -   [How to Deploy Large Language Models on AWS Inferentia2 using Large Model Inference Containers](https://wandb.ai/wandb_fc/mlops_course/reports/Hyperparameter-Tuning-with-W-B-Sweeps--VmlldzozMjI0NzAz) - This blog post shows how to deploy large language models on AWS Inferentia2, a high-performance and low-cost ML inference accelerator, using large model inference containers powered by Deep Java Library (DJLServing).
    -   [How to Deploy Large Language Models on Edge Devices using TensorFlow Lite](https://huggingface.co/blog/trl-peft) - This tutorial demonstrates how to deploy large language models on edge devices using TensorFlow Lite, a framework for running TensorFlow models on mobile and embedded devices.
    -   [How to Deploy Large Language Models on Mobile Devices using PyTorch Mobile](https://quiq.com/blog/pretrained-language-model-training/) - This documentation page explains how to deploy large language models on mobile devices using PyTorch Mobile, a framework for running PyTorch models on iOS and Android devices.
