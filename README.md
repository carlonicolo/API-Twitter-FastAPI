# Consuming Twitter API with FastAPI

This project has been created during the live session code **[Consumindo a API do Twitter com Python](https://docs.google.com/presentation/d/11DkkyQUIloVQLm8i6hN6w3xyUaP4WSRE/edit?usp=sharing&ouid=102662434190974209165&rtpof=true&sd=true)**.  

## Technologies

- Python 3.8.x
- FastAPI
- MongoDB

## Requisites ✋

- Docker
- Docker compose

## Installation 💽

Install **[Docker](https://www.docker.com)** and **[Docker compose](https://docs.docker.com/compose/)** .

## How to execute the application 🛸

```sh
poetry shell
python main.py
```

Access to **[Swagger UI](http://localhost:8000/docs)** for looking at all endpoints.

Use `Ctrl+C` for exit and stop the server.

## How to test the application 🧪

```sh
poetry shell
pytest
```