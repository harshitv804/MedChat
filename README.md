<h1 align="center">MedChat - ✨RAG based AI Chatbot🤖 for Indian Medicines 🇮🇳</h1>
<h3 align="center">Explore 15K+ Indian Medicines💊 with Ease!</h3>
<p align="center">
<img src="https://github.com/harshitv804/MedChat/assets/100853494/86b9efcc-32cd-42ae-a2ce-90e5c6c0401e" width="700"/>
</p>

## About The Project
MedChat🤖 is an innovative RAG-based generative AI chatbot designed for inquiries regarding Indian medicines💊. Leveraging Open web data on Indian Medicines, this project was meticulously developed using Streamlit, LangChain, and the TogetherAI API, powered by Mistral-7B. Users can pose questions or seek information about medications, and MedChat, through its advanced similarity search capabilities, delivers accurate responses in most cases. The chatbot features a chat history that spans up to two conversations, enhancing user experience and facilitating seamless interactions.

**_⚠️Disclaimer: The results furnished by the chatbot are for informational purposes only and may not always be accurate. It is crucial to seek advice from a qualified medical professional for precise healthcare recommendations._**

`Vector DB: FAISS`
`Embedding Model: nomic-ai/nomic-embed-text-v1`
`LLM: Mistral-7B-Instruct-v0.2`

### Check out the live demo on Hugging Face <a href="https://huggingface.co/spaces/harshitv804/MedChat"><img src="https://static.vecteezy.com/system/resources/previews/009/384/880/non_2x/click-here-button-clipart-design-illustration-free-png.png" width="120" height="auto"></a>

## Getting Started

#### 1. Clone the repository:
   - ```
     git clone https://github.com/harshitv804/MedChat.git
     ```
#### 2. Install necessary packages:
   - ```
     pip install -r requirements.txt
     ```
#### 3. Signup and get 25$ of free credit (or just pay for it If you wish to use for long-term, they are more cheaper than OpenAI API. You can also use other LLMs or APIs if you wish so. Check this link: [python.langchain.com/docs/integrations/llms](https://python.langchain.com/docs/integrations/llms) for more options.), and then set TogetherAI API Key in environment variable in python. 
   - ```
      os.environ["TOGETHER_API_KEY"] = "YOUR_TOGETHER_API_KEY"`
     ```
   - If you are going to host it in streamlit, huggingface or other...
      - Save it in the secrets variable provided by the hosting with the name `TOGETHER_API_KEY` and key as `YOUR_TOGETHER_API_KEY`.

#### 4. To run the `app.py` file, open the CMD Terminal and and type `streamlit run FULL_FILE_PATH_OF_APP.PY`.

## Contact
If you have any questions or feedback, please reach out to [harshitvenkatesan88@gmail.com]
