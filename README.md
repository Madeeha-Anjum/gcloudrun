# GCloud Server

Using Google Cloud Platform, Cloud Run  to host a FastAPI server. Github actions to automate the deployment process. Docker hub to store the docker image.

- Create a virtual environment

```bash
python -m venv venv
```

- Activate the virtual environment

```bash
source venv/Scripts/activate
```

- Install the dependencies

```bash
pip install -r requirements.txt
```

- run the server

```bash
uvicorn app.main:app  --host 0.0.0.0 --port 80 --reload
```

- open the browser and go to `http://localhost:80/docs`
