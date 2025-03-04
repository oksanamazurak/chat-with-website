# Chat-with-webiste.

LLM project designed to retrieve up-to-date data from website by URL and generate response.

## Technologies used:

+ OpenAI API
+ LangChain
+ RAG
+ Streamlit

How to run on your local machine:
### 1. Clone repository
```git
git clone https://github.com/oksanamazurak/chat-with-website.git
cd chat-with-website
```
### 2. Install required libraries
```python
pip install -r requirements.txt
```
### 3. Set up OpenAI API Key
```
OPENAI_API_KEY=your_openai_api_key
```
### 4. Run the application
 ```
streamlit run app.py
```  
# How it wrks:

The user enters a website URL and a query.

The application fetches textual data from the specified site.

Using LangChain and RAG, the model generates a response based on the retrieved content.

# Example usage
