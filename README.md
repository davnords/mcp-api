# MCP API using FastAPI

Learn to actually get your MCP server to connect to your web frontend. See the [video](https://youtu.be/s83SbHjCVtU).

Simply run:
```bash
uvicorn app:app --reload --port 8000
```
And you will have the FastAPI server running and then go to [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs) to get the swagger ui.

You will need to create a .env file and fill it with your anthropic api key like such:
```python
ANTHROPIC_API_KEY=...
```
