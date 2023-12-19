## EARNINGS CALL LLM PROJECT USING QDRANT AND LANGCHAIN

This project aims to build a LLM Agent for Question-Answering on Earnings call Data for publicly listed companies. Install the dependencies from `requirements.txt`


To start the Qdrant docker container, install docker and run the following command

```shell
docker run -p 6333:6333 \
    -v '$(pwd)/path/to/data:/qdrant/storage' \
    qdrant/qdrant
```

After that, you can start the application by doing

```
streamlit run Database.py
```

DEMO

![Sample Answer](https://github.com/Athe-kunal/Earnings-Call-LLM-Agent/blob/main/demo.png)
