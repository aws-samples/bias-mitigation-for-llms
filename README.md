# Is Your Language Model Biased? Here is how to fix it!

In this workshop you will learn how to detect and mitigate bias in Large Langauge Models (LLMs).

The work is divided in 3 labs:
1. **Bias Detection**: In this lab you will learn how to use `toxicity`, `regard` and `honest`, metrics (available on HuggingFace) to evaluate your LLMs. 
2. **Counterfactual Data Augmentation (CDA)**: In this lab, you will learn how to use the CDA technique to create data that is more representative of a diverse population, that can be then used to fine-tune your LLMs.
3. **Model fine-tuning**: In this lab you will use the data generated in the previous lab to fine-tune an LLM and mitigate representational differences present in model outputs regarding diverse populations.

## How to use
These notebooks are intended to be executed on a SageMaker Studio Domain Notebook or SageMaker Notebook. Each notebook comes with its pre-configured image and instance type. In order to run those notebooks outside SageMaker Studio, you will need to configure our python installation with the required packages that include, but are not limited to: `PyTorch`, `pandas`, `numpy`.
These notebooks also assume that you have at least 1 instance of `ml.g5.2xlarge` for SageMaker Endpoints and one instance of `ml.g4dn.2xlarge` for SageMaker Studio notebooks (or bigger) available on your account.

## Contacts
* **Bharathi Srinivasan** (bhrsrini@amazon.com)
* **Kimessha Paupamah** (kimessha@amazon.com)
* **Mia Mayer** (mimayer@amazon.com)
* **Maira Ladeira Tanke** (mttanke@amazon.com)

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

