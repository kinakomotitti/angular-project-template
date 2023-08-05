# angular-project-template

## steps

### define the new application name.

Change the `ANGULAR_APP_NAME` in .env file.  
This name will be used when you execute the docker compose up command.

### run the docker compose.

`dokcer compose up -d`
Then the docker will creaete a new application "ANGULAR_APP_NAME" in "angular directory"

## Q&A

### how to set variable value in docker compose yaml file?

Can do it with [.env](https://docs.docker.jp/compose/env-file.html#).

### want to disalbe angular CLI analitics. how?

To disable the question of angular CLI analitics, should set the following environment variable.
NG_CLI_ANALYTICS=false
