# Platform Used
* I completed this project in **Google Colab**.  
* I have uploaded **.py** script and **.ipynb (colab file)** along with this readme.
* **Streamlit** used for better user interface.

# Packages required
* Langchain
* Langchain - core and community
* Torch
* Sentence-transformer
* Groq
* Pypdf
* Llama-index
* Ngrok
* FAISS , etc.

# What i have used and why?
* To *store vectors*, i have used **FAISS** here. I tried *SQLiteVSS* but found *FAISS better*.
* In Google colab, i cant directly stream to streamlit, and hence, used **ngrok**, which helps in doing so. I have even provided with my ngrok authorisation key with code.
* Rest everything is just normal.

# Files needed
* **.env** file with **groq api key**.
* **Case compendium** file from where we will *retrieve* information.

# Set-up
* We have to upload both the files using the *first code block* in **.ipynb** file.
* Then install all required packages.
* you just have run the blocks as they are in .ipynb.

# Results
* I have provided few pictures of my project.
* picture 1 : home page
* picture 2 : information page. (Name and other details not added but could be done)
* picture 3 : snapshot of a conversation
