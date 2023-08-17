## Simple API using Flask

### Run using flask

```bash
python app/app.py
```

### Run Docker

```bash
# for develop environment
docker-compose -f compose.yaml up --build -d

# down service develop
docker-compose -f compose.yaml down

# for production environment
docker-compose -f compose.production.yaml up --build -d

# down service production
```

### Config
