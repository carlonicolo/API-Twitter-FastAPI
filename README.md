# Consuming Twitter API with FastAPI

This project has been created during the live session code **[Consumindo a API do Twitter com Python](https://docs.google.com/presentation/d/11DkkyQUIloVQLm8i6hN6w3xyUaP4WSRE/edit?usp=sharing&ouid=102662434190974209165&rtpof=true&sd=true)**.  

## Technologies

- Python 3.8.x
- FastAPI
- MongoDB

## Requisites โ

- Docker
- Docker compose

## Installation ๐ฝ

Install **[Docker](https://www.docker.com)** and **[Docker compose](https://docs.docker.com/compose/)** .

## How to execute the application ๐ธ

```sh
poetry shell
python main.py
```

Access to **[Swagger UI](http://localhost:8000/docs)** for looking at all endpoints.

Use `Ctrl+C` for exit and stop the server.

## How to test the application ๐งช

```sh
poetry shell
pytest
```