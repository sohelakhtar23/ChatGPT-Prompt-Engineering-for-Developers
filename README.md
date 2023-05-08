# ChatGPT Prompt Engineering for Developers

- Learn prompt engineering best practices for application development
- Discover new ways to use LLMs, including how to build your own custom chatbot
- Gain hands-on practice writing and iterating on prompts yourself using the OpenAI API

To install the OpenAI Python library:
```
!pip install openai
```

The library needs to be configured with your account's secret key, which is available on the [website](https://platform.openai.com/account/api-keys). 

You can either set it as the `OPENAI_API_KEY` environment variable before using the library:
 ```
 !export OPENAI_API_KEY='sk-...'
 ```

(For this, simply make a file named as `.env` in your root directory and place one line code as with your api key and save the file.)
``` 
OPENAI_API_KEY = 'sk-..' 
```

Or, set `openai.api_key` to its value:

```
import openai
openai.api_key = "sk-..."
```

## Jupyter notebooks of "ChatGPT Prompt Engineering for Developers" taught by DeepLearning.AI and OpenAI.

In this, you will learn how to use a large language model (LLM) to quickly build new and powerful applications.  Using the OpenAI API, you’ll be able to quickly build capabilities that learn to innovate and create value in ways that were cost-prohibitive, highly technical, or simply impossible before now.

This short course will describe how LLMs work, provide best practices for prompt engineering, and show how LLM APIs can be used in applications for a variety of tasks, including:

- Summarizing (e.g., summarizing user reviews for brevity)
- Inferring (e.g., sentiment classification, topic extraction)
- Transforming text (e.g., translation, spelling & grammar correction)
- Expanding (e.g., automatically writing emails)

In addition, you’ll learn two key principles for writing effective prompts, how to systematically engineer good prompts, and also learn to build a custom chatbot. 

All concepts are illustrated with numerous examples, which you can play with directly in our Jupyter notebook environment to get hands-on experience with prompt engineering. 
