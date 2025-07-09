## Hey there! 👋

<!--
**mlstudios-ai/mlstudios-ai** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

This is my R&D github account where I experiment everything AI, ML, SE, plus some creative stuff for innovation. And occasional ranting...

It is still under development. I have a few of my research projects that yet to migrate here. Some of them are private due to strict policies.

My plan is to host it so you can see it in action live. 

mlstudios.ai (coming soon)

If you want access to the code on GitHub, please contact me directly.

# Projects
## SecondSight
An end-to-end live hazard detection AI application designed to enhance accident prevention and situational awareness for people with blindness. This project was nominated and won the Best Application AI Showcase.

The hazard detection functionality is implemented as a standalone feature by embedding YOLO 11 Nano object detection on the iPhone paired with Apple Watch to receive haptic and speech alerts as well as application control. With internet access, it also offers live scene description for situational awareness via custom-trained and prompt-engineered visual language models (VLMs), served through FastAPI endpoints.

- https://github.com/vanilla-ai-ml/EnigmaAI (MLOps)
- https://github.com/vanilla-ai-ml/SecondSight-API (FastAPI)
- https://github.com/vanilla-ai-ml/SecondSight (iOS)

## SPARK
A personalised product recommendation agent that can adapt to live user interaction activities utilising deep reinforcement learning, behavioral modeling, and feature engineering. 
This project is implemented with online shopping web interface to gather real-time user data such as clicks, reviews, likes, and purchases. Feature engineering techniques are applied on past and real-time interaction data to provide latent features, effectively allowing the RL model to learn and adapt to changes of user behaviour over time.


- https://github.com/chilliavocado/spark

## APRA Q&A Agent
A retrieval-augmented generation (RAG) system for question and answering on a list of banking regulation documents. I implemented a three-stage optimisation technique that led to a 1200% improvement on BLEU score compared to basic RAG implementation.

The system utilises Amazon Bedrock, Pinecone, and OpenAI for RAG question and answering. The regulatory documents are chunked individually with overlaps to preserve only the relevant context and embedding. Meta data is stored and used for filtering and ordering retrieved vectors. Strict prompt engineering techniques are applied using LangChain and OpenAI LLM for augmented generation and hallucination prevention.

- https://github.com/chilliavocado/ChatBot-Adv-NLP/tree/main/Anna

## Medical AI
Alzheimer’s disease detection on MRI brain scans using Convolutional Neural Network (CNN) image classification. The researched approach achieved 92% accuracy, surpassing human medical professional benchmark of 87%.

This task requires deep analysis of the problem with domain knowledge to design solution approach. The techniques applied include skull stripping to remove data noise, selecting mid brain scans near the hippocampus to detect brain mass shrinkage, image augmentation to increase data variability, and CNN layer regularisation, dropout, and normalisation for performance optimisation. 

- https://github.com/chilliavocado/Dementia-Classification-via-MRI-data 



