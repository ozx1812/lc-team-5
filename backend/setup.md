*Note*: docker must be installed

# git clone repo

# start backend
- `cd docker`
- `docker compose up --build`

# expected terminal output
```bash
backend  | INFO:     Started server process [1]
backend  | INFO:     Waiting for application startup.
backend  | INFO:     Application startup complete.
backend  | INFO:     Uvicorn running on http://0.0.0.0:80 (Press CTRL+C to quit)
```

# Install mongosh to connect mongodb from cli
- refer installation steps from [here](https://www.mongodb.com/docs/mongodb-shell/install/) for your OS.
- test if its working properly.
```bash
docker compose up # this will start both backend and mongo container
mongosh # this will connect to mongodb
```


# Thunder client setup 
- to test endpoints from vscode install thunder client extenstion
- load the thunder-collection_users.json file