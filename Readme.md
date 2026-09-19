
>>> python -m venv venv
>>> venv\Scripts\activate

>>> pip install -r requirements.txt

# To generate Vectore Embeddings 

>>> cd backend
>>> python index.py

Note: Here Vector embeddings are already generated 

# To start Backend

>>> cd backend (if you skip embeddings)
>>> uvicorn main:app --reload 

# now start frontend 
# In new Terminal

>>> cd frontend 
>>> streamlit run app.py 

