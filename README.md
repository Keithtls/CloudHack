# CloudHack
This is for the competition of CloudHack 2024

# How to use
1. cd to directory of KMN code
2. pip install -r requirements.txt
3. Change env.txt openai key to yours
4. streamlit run app.py
5. App will run and you can use it now

This will run the application (credit to: https://github.com/slvg01/10d_RAG_OnTheFly/tree/main for the app template)

# Application features
Upload your documents first, with pdf for example, (PDF, DOCX, or PPTX file format accepted).
You can upload multiple files.
Click on Analyze to prepare RAG chain with the uploaded documents
Converse with the AI, ask questions about the documents to get referenced answers.

#Known Bugs
Doing conversation without uploading and analyzing first breaks the code (add in condition to analyze before doing conversation)

#Possible future changes
Edit RAG prompt to be more efficient and helpful
Add in a more formatted page for uploading documents
Add in main features (mind mapping and TTS conversation)
