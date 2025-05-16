# Mental Health Chatbot using Machine Learning

This project presents a comprehensive implementation of a **retrieval-based mental health chatbot** built using the **Pandora dataset**. The primary goal is to classify user intents and retrieve appropriate responses to support mental well-being.

We explored and compared three different machine learning models:
-  **Support Vector Machine (SVM)**
-  **Artificial Neural Network (ANN)**
-  **Recurrent Neural Network (RNN)**

Each model was evaluated for its effectiveness in intent classification, a key component in determining the chatbot's ability to respond appropriately.

##  Key Highlights

- **Dataset Preprocessing**: Text cleaning, tokenization, and encoding techniques were applied for optimal model performance.
- **Model Architectures**: Designed and trained SVM, ANN, and RNN models to handle multi-class classification of user intents.
- **Training & Evaluation**: Comprehensive training pipelines and evaluation metrics (accuracy, confusion matrix) were used to compare models.
- **Comparative Analysis**: Performance of each model was analyzed to determine the most effective approach.
- **Recommendations**: Actionable suggestions for improving chatbot accuracy, user experience, and real-world deployment.

---

##  How to Run (Google Colab Instructions)

Follow these steps to set up and launch the chatbot in **Google Colab**:

1. **Upload Required Files**
   - Upload the following files to your Colab environment (in the **same folder**):
     - `model.py`
     - `frontend.py`
     - `run.py`
     - `intents/dataset.json` (or equivalent dataset)

2. **Install Dependencies**
   - Upload and install the required packages using the provided `requirements.txt`:
     ```python
     !pip install -r requirements.txt
     ```

3. **Run the Model Script**
   - Execute the model training or loading logic:
     ```python
     %run model.py
     ```

4. **Run the Frontend Script**
   - Set up the frontend interface:
     ```python
     %run frontend.py
     ```

5. **Configure ngrok**
   - Add your ngrok authentication token (replace with your actual token):
     ```python
     !ngrok config add-authtoken "your_auth_token"
     ```

6. **Launch the Chatbot**
   - Start the chatbot server:
     ```python
     %run run.py
     ```

Once the above steps are completed, a public URL from ngrok will be provided. You can use this link to interact with your mental health chatbot in real time.

##  Contributors

- **Vaibhav Walujkar**
- **Tanmay Sharma**
- **Dhroov Waddesai**
- **Mithilesh Singh**


---
>  **Note**: Ensure all Python files are in the same directory in your Colab environment and your ngrok account is properly set up before launching the chatbot.
