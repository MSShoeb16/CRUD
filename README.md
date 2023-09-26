
# Flask API

This code will perform CRUD operation with REST API, while docker as the hosting container and postgreSQL as database.


## Run Locally

Clone the project

```bash
  git clone https://github.com/MSShoeb16/CRUD.git
```

Go to the project directory

```bash
  cd my-project
```

Compose/Run the Database

```bash
  docker compose up -d flask_db
```

Build the code

```bash
  docker compose build
```
Compose/Start the app

```bash
  docker compose up flask_app
```


