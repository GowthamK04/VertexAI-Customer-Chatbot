# Vertex AI Customer Chatbot

Welcome to the Vertex Customer Chatbot repository! This project demonstrates how to utilize Google Cloud's Vertex AI to build and interact with a chat model. The chatbot is designed to handle customer complaints, inquiries, and requests, leveraging Vertex AI's Text Generation Model to simulate real-world customer service interactions.

## Project Overview
The chatbot is built using Google Cloud's Vertex AI, specifically utilizing the `TextGenerationModel` for generating natural responses. It interacts with users, summarizing conversations and handling requests, such as changing shipping addresses or addressing service complaints. The chatbot is designed to be adaptable for various customer service scenarios. It leverages Vertex AI's powerful machine learning capabilities to provide accurate and scalable responses.

This repository provides a Jupyter Notebook (`vertexai_chatbot.ipynb`) that illustrates how to:

- Set up the necessary environment using virtual environments
- Authenticate with Google Cloud services
- Initialize a chat model using Vertex AI
- Customize chat interaction parameters
- Interact with the chat model to generate responses


## Features
- **Summarizes conversations**: The chatbot can summarize a series of interactions between a service representative and a customer.
- **Handles customer complaints**: It responds to detailed customer complaints with suggestions or solutions.
- **Adaptive responses**: Configured to provide diverse responses based on temperature and token parameters.
- **Google Cloud Integration**: Fully integrated with Vertex AI and the Google Cloud platform, ensuring scalability and robustness.


## Technologies Used
- **Google Cloud Vertex AI**
- **Python**
- **Google Cloud SDK**
- **Jupyter Notebook**

## Project Structure
- `VertexAI-Customer-Chatbot/`
  - `README.md`: Provides a detailed overview of the project.
  - `datasets/`: Contains the dataset(s) used for chatbot training or testing.
    - `banking_dataset.csv`: An example dataset containing customer queries and complaints.
  - `notebooks/`: Jupyter notebooks used for building and testing the chatbot.
    - `vertexai_chatbot.ipynb`: The main notebook that demonstrates building and deploying the chatbot using Vertex AI.
    - `demo/`
      - `vertexai_chatbot_demo.ipynb`: A notebook to showcase a demo version of the chatbot for presentation purposes.


## How to Run the Project
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/VertexAI-Customer-Chatbot.git
    cd VertexAI-Customer-Chatbot
    ```

2. **Run the Jupyter Notebook**:
    Start the notebook and follow the code steps to build and deploy the chatbot.
    ```bash
    jupyter notebook vertexai_chatbot.ipynb
    ```

3. **Authenticate Google Cloud SDK**:
    You will need to log in to Google Cloud to authenticate and set the correct project.
    ```bash
    gcloud auth application-default login
    ```

4. **Test the Chatbot**:
    Follow along with the notebook to explore the chat model demo. The notebook allows you to interact with the chatbot by providing sample customer complaints or queries. The chatbot will generate responses based on the input and defined parameters.

## Enjoy experimenting with the Vertex AI Customer Chatbot! If you have any questions or suggestions, feel free to open an issue or contribute to the project. Happy coding! 😊🚀

