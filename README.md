# Quantized-RAG
This project for RAG implementation using RAG 

This project revolse around financial question.


## Configuration

1. Make Virtual Environment:
```virtualenv envs``` 

2.  Activate Virtual Environmnet:
```source envs/bin/activate```

3. Run requirements.txt file:
```pip install -r requirements.txt```

4. Configure ollama:
```curl -fsSL https://ollama.com/install.sh | sh```

5. Pull/Run ollma model:
```ollama run phi3```


## Run API

```python app.py```

## Postman

URL: http://0.0.0.0:5000/query
<br>METJOD: POST</br>
JSON BODY: {"ask": "What is the revenue of apple" }


