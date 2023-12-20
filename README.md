# How I Built an Okta Documentation Chatbot in Python

This repo is a Python chatbot example that uses OpenAI to quickly access information through [Okta's Developer Documentation](https://developer.okta.com). 

Please read How I Built an Okta Documentation Chatbot in Python to see how it was created.

### Prerequisites:

- Library installation: The script begins with installing the required Python packages: [OpenAI](https://pypi.org/project/openai/), [Panel](https://panel.holoviz.org/getting_started/installation.html), and [LlamaIndex](https://pypi.org/project/llama-index/). These packages work with the GPT-3.5 model, create the web interface, and manage the chatbot's conversations.

- [OpenAI API account](https://help.openai.com/en/articles/4936850-where-do-i-find-my-api-key) 

- Download these [files](https://drive.google.com/drive/folders/11W-cjmkTztmnGgJCsJRtE395Iji6JX53?usp=share_link) and make sure the files are saved on your drive (not within any folders) and that you are mounting the files from the correct account.
- Jupyter Notebook via [Collab](https://colab.google/) 
---
- [Help](https://github.com/oktadev/okta-python-chatbot-example/edit/main/README.md#help)
- [License](https://github.com/oktadev/okta-python-chatbot-example/edit/main/README.md#license)
- [Run the app](https://github.com/oktadev/okta-python-chatbot-example/edit/main/README.md#run-the-app)


## Run the app
1. With a Google account, ensure you have access to [Colab](https://colab.google/); this will be the environment we will use to run the Python scripts. 

2. Library installation: The script begins with installing the required Python packages: [OpenAI](https://pypi.org/project/openai/), [Panel](https://panel.holoviz.org/getting_started/installation.html), and [LlamaIndex](https://pypi.org/project/llama-index/). These packages work with the GPT-3.5 model, create the web interface, and manage the chatbot's conversation. Note, LlamaIndex was used only to read the data.

3. Create an OpenAI account and follow these [instructions](https://help.openai.com/en/articles/4936850-where-do-i-find-my-api-key) to obtain an API Key. Replace the API Key code snippet with your API Key. ChatGPT used to offer free credits to use, but it now costs five or more dollars to purchase API usage.

4. Download the Okta Developer Documentation files [here](https://github.com/oktadev/okta-python-chatbot-example/tree/tar-file) and make sure the files are saved in a 
 separate folder on your drive (not within any folders) and you are mounting the files from your Google account. Also, make sure to name the folder 'oktanaut'. Alternatively, you can download the files directly from the [Okta Developer Documentation Repository](https://github.com/okta/okta-developer-docs).

5. Run the GPTChatbot.ipynb notebook in your Colab development environment.

6. After running the script, a web interface displays an input field and a "Chat with Oktanaut!" button.

7. Enter your questions or statements about the Okta or OAuth developer documentation in the input field

8. To submit your question, click the "Chat with Oktanaut!" button to begin conversation with the Python chatbot.

9. Oktanaut will answer your question with an ai-generated response using its knowledge from the developer documentation, training data from internal support engineers, and the OpenAI API.

10. Continue the conversation by entering additional questions or prompts and clicking the button. This will lead to better answers due to the self-learning nature of the chatbot.

11. To end the session, say "thank you," which is also mentioned by the chatbot in its introductory message.

12. The chatbot answers questions and converses based on your prompts. It uses the GPT-3.5 Turbo model to generate responses.

Note: The conversation and responses will appear on the web interface in real-time. Feel free to try it out and have a conversation with Oktanaut!


## Help
Please post any questions as comments on the blog post, or visit our Okta Developer Forums.

## License
Apache 2.0, see [LICENSE](https://github.com/oktadev/okta-python-chatbot-example/blob/main/LICENSE).
