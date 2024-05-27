## This project is about creating an end-to-end document Q&A chatbot using an open-source model called Gamma from Google and Groq an inferencing engine.

### The steps involved in creating this chatbot:

1. It is about Gamma models and their variants, including Gamma itself, Code Gamma, LaMDA, and Recurrent Gamma.
2. Then explain Groq and its LPU (Language Processing Unit) which makes inference much faster than GPUs.
3. The code explaining libraries used like Langchain, transformers, and FAISS.
4. Set up the prompt template and vector embedding using Google generative AI embeddings.
5. Finally, create a Streamlit app to run the code. The app allows users to upload PDFs and ask questions related to the content of the PDFs.

Clone the repo and run the
````
streamlit run app.py
````
Click on the button to create the vector db based on your document and then you are ready to perform Q and A.
