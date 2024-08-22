# What is ULM?
ULM (United Language Model)
A ULM is a technique that combines multiple large language models (LLMs) specializing in different domains to create a customized chatbot. This approach offers several benefits:
 * Cost-effectiveness: By using smaller, more affordable models for specific tasks (e.g., GPT-4o mini for chatting), ULM can be more cost-effective than using a single, large model for all purposes.
 * Efficiency: LLMs can focus on their areas of expertise, leading to more accurate and efficient responses.
 * Customization: ULMs can be tailored to meet specific needs and requirements.
Example: A ULM might combine:
 1. GPT-4o mini for general chat and conversation.
 2. GPT-4 latest for complex tasks like math problem-solving and critical thinking.
 3. Claude 3.5 sonnet for coding-related requests.
By combining these models, the ULM can provide a powerful and versatile chatbot capable of handling a wide range of tasks.

# Benefits of ULM:
* we can customize our own model and enhance its skills in specific domains.
 * ULM is more cost-effective and practical to use.
 * It can handle a wide range of tasks efficiently by combining various LLMs.
 * It will provide more accurate responses if we choose the perfect LLMs to combine.
 * It can grow with evaluations of models. This means that in the future, when LLMs become more effective, we can create even more powerful models with ULM.

# Architecture of ULM:
![](https://github.com/cyberytti/ULM/blob/main/Screenshot_2024-08-22-21-49-19-26.jpg)

**Explanation:**

The user will initially input data. This input will be classified into a desired category by the classifier. Based on this classification, a suitable model will be selected. Finally, the output will be generated using the chosen model.

# Future improvements: 
We plan to incorporate high-quality, proprietary models into this project soon, resulting in the development of a supermodel (ULM model).

# Installation:
To install and run this system, follow these steps:
 * Clone the repository. This will download the necessary code files to your local machine.
 * Obtain API keys for Groq, Together AI, and OpenRoute AI. You'll need to create accounts with these services and obtain their respective API keys, which are unique identifiers that allow your code to interact with their APIs.
 * Install Groq and OpenAI libraries. Use the following commands in your terminal to install the required Python libraries:

```bash
# Install Groq module.
pip install groq
# Install openai module.
pip install openai

```

 * Open the main_model.py file. This file contains the core logic of the system.
 * Update the API keys. Locate the designated sections within the main_model.py file and replace the placeholder string with your obtained API keys.
 * Run the model. Once the keys are configured, execute the script.
