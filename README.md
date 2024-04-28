# document query using RAG

#add an environment file and include the following secrets
OPENAI_API_KEY
OPENAI_MODEL
TEMPERATURE

#Install dependencies.
pip install -r requirements.txt

#Create the Chroma DB.
python create_database.py

#Query the Chroma DB.
python query_data.py "How to deploy a cloud function?"
