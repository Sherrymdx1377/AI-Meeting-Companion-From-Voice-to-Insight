# Table of Contents:

1)
Speech to text to LLM

2)
Step 1. Speech to text

3)
Gradio interface

4)
Step 2: Creating audio transcription app

5)
Step 3. Integrating LLM: Using LLAMA2 in watsonx as LLM

6)
Step 3.1. (Another option) Using HuggingFace hub or OpenAI

7)
Step 4. Put them all together

8)
Conclusion

# At a Glance

Create an app to capture audio (like lectures) and summarize it. Build the app using OpenAI Whisper (text to speech), then summarize it with an open source LLAMA 2 LLM hosted by IBM watsonx. You deploy the app in a serverless environment using IBM Cloud Code Engine.

Imagine that you're a student who records your teacher's lectures. But, what if you need to turn that recorded lecture into text? There's a handy AI app that can do that for you, accurately. It also summarizes the lecture and highlights the main points.

In this project, you use OpenAI's Whisper to transform speech into text. Then, you use IBM watsonx AI to summarize and find key points. This stage couples with prompt engineering through PromptTemplate in Langchain. You'll make an app with HuggingFace Gradio as the user interface.

The output from the LLM not only summarizes and highlights key points, it also corrects minor mistakes made by the speech-to-text model, ensuring a coherent and accurate result.

# A quick recap of what is accomplished:

- Text generation with LLM: You created a Python script to generate text by using a model from the Hugging Face Hub, learned about some key parameters that influence the model’s output, and have a basic understanding of how to switch between different LLM models.

- Speech-to-Ttxt conversion: You used OpenAI’s Whisper technology to convert lecture recordings into text, accurately.

- Content summarization: You implemented IBM Watson AI to effectively summarize the transcribed lectures and extract key points.

- User interface development: You created an intuitive and user-friendly interface by using Hugging Face Gradio, ensuring ease of use for students and educators.

- App deployment: You learned and applied the skills necessary to deploy the application online by using IBM Code Engine, making the tool accessible to a wider audience.
