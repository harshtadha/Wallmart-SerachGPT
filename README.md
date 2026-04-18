

## 📍 Overview

The Walmart SalesBot and SearchGPT repository provides a AI solution to improve customer service and search capabilities. The tool includes an AI chatbot, enabling users to interact with either the'WalmartBot' or'SearchGPT' bot in real-time. It utilizes a robust conversational AI agent that can fetch webpage content, gather weather details, conduct searches, and retrieve news. It provides a sales assistance system for Walmart, implementing stages of sales conversations and managing customer interactions. Additionally, the repository includes an API server for product search and information retrieval.This project draws inspiration from SalesGPT and various other open-source initiatives. It is important to note that no direct copying or borrowing of ideas has occurred, and sincere gratitude is extended to all open source projects. 

### Walmart Bot
The Streamlit interface offers users two distinct options: Walmart Bot and SearchGPT.

#### Walmart Bot Functionality
The Walmart Bot functionality allows users to seamlessly search for products on Walmart. Additionally, it provides responses to specific product-related queries such as pricing inquiries and feature comparisons (e.g., "What is the price of iPhone 12?" or "Compare features of products"). Each response is accompanied by a source link or product link, offering users a comprehensive answer.

#### Technical Implementation
- Language Models: OpenAI models are employed in the project, with the flexibility to utilize any open-source model from Hugging Face.
- Langchain: The system leverages Langchain to enhance its functionality. Techniques such as Prompt Engineering, RetrievalQA, and Vector Database utilization contribute to the robustness of the system.
- Vector Database: Pinecone serves as the vector database, providing efficient storage and retrieval capabilities. The system is adaptable, allowing the use of alternative vector databases or traditional databases via llamaindex.
- Embeddings: OpenAI embeddings are utilized in the current implementation, though open-source embeddings can be seamlessly integrated for further customization.
#### API and Framework Choices
- API Framework: FastAPI is chosen to develop the API, providing a high-performance and user-friendly interface. However, the system is designed to be flexible, allowing the use of alternative frameworks like Flask or others.
- User Interface Framework: Streamlit is employed to construct the interface, offering a visually appealing and interactive platform. Users have the freedom to choose alternative frameworks based on their preferences.

### SearchGPT Functionality
In addition to Walmart Bot, the interface also facilitates the use of SearchGPT, enabling users to search for any question and obtain answers from the internet.

#### Technical Implementation
Language Models: Large language models are utilized in combination with LangChain and various tools to power the SearchGPT system.

---




---


## 📂 Repository Structure

```sh
└── Walmart-SalesBot-and-SearchGPT/
    ├── Data/
    ├── Dockerfile
    ├── Images/
    ├── csv_to_vectore_database(pinecone).ipynb
    ├── requirements.txt
    ├── run_api.py
    ├── search_capabilities.py
    ├── streamlit_interface.py
    └── walmart_functions.py

```


## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system: [requirements.txt](https://github.com/Shaon2221/Walmart-SalesBot-and-SearchGPT/blob/main/requirements.txt)

### 🔧 Installation

1. Clone the Walmart-SalesBot-and-SearchGPT repository:
```sh
git clone https://github.com/harshtadha/Wallmart-SerachGPT.git
```

2. Change to the project directory:
```sh
cd Walmart-SalesBot-and-SearchGPT
```

3. Install the dependencies:
```sh
pip install -r requirements.txt
```

### 🤖 Running Walmart-SalesBot-and-SearchGPT

```sh
python run_api.py
```
### 🕹️ Running using Docker
```
docker build -t bot .
docker run -p 5000:5000 bot
```

### ✨ Interface
```sh
streamlit run streamlit_interface.py
```

---


## 🛣 Project Screenshots

![Walmart_Bot Screenshot](https://github.com/harshtadha/Wallmart-SerachGPT/blob/main/Images/searcGPT_screenshot.png)

![Walmart_Bot Screenshot](https://github.com/harshtadha/Wallmart-SerachGPT/blob/main/Images/walmart_bot-screenshot.png)

---

## 🤝 Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/Shaon2221/Walmart-SalesBot-and-SearchGPT/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Shaon2221/Walmart-SalesBot-and-SearchGPT/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/Shaon2221/Walmart-SalesBot-and-SearchGPT/issues)**: Submit bugs found or log feature requests for Shaon2221.


## 👏 Acknowledgments

- This projects is inspired by SalesGPT and other open source projects. But not copy paste, or any idea has not been stolen. Thanks to all the contributors.

## 🛠️How to deploy the project
You can deploy the project using Docker or Streamlit. You can also deploy the project using Heroku, AWS, or any other cloud platform.

## 🧑‍🚀How to contact the Author
You can contact me at: [Email](tadhaharsh.dev@gmail.com)

[**Return**](#Top)

---
