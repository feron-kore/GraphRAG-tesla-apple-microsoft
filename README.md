GraphRAG

1. Set Up Virtual Environment and Install GraphRAG:

pip install graphrag


2. Initialize GraphRAG in the Root Directory:

python -m graphrag.index --init --root .

3. Create an Input Directory and Add Text or CSV Files for Indexing:

mkdir input


4. Add Your OpenAI Key to the .env File and Customize Your Model in settings.yaml

5. Run the Indexing Process:

python -m graphrag.index --root .


6. Query Using GraphRAG:

python -m graphrag.query --root . --method local/global "Your_Question"
