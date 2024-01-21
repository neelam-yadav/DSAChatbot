# DSAChatbot

## Introduction
This is a sample chatbot trained on Data Structures and Algorithms. It can be trained on more data and it is open for playing around.

## Setup
1. **Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. **Configure Paths and Settings**:
- Set `DB_FAISS_PATH` and `DATA_PATH` as required for your project.
  - `DB_FAISS_PATH`: This is the path where you want to store your vectorstore db.
  - `DATA_PATH`: Path having your documents to be trained. (At present code supports only PDF documents)

## Usage
1. Train the Chatbot using your custom data:
   1. Put your PDF files under `DATA_PATH` path.
   2. Run:
      ```bash
      python ingest.py
      ```
   
3. Now run Chatbot and play around on the UI using below command:
   ```bash
   chainlit run chatbot.py
   ```

## License
This project is licensed under the [MIT License](License).

