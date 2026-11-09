# Sarfees App

## Requirements

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)

## Run

1. Clone the repository and enter the folder:

```
git clone https://github.com/HAMZA98755/sarfees-app.git
cd sarfees-app
```

2. Create a file named `.env` in the project root:

```
DB_PASSWORD=chose_simple_password
```

3. Start the project:

```
docker compose up -d
```

4. Open the map:

```
http://localhost:8080
```

## Stop

```
docker compose down
```
