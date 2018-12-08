# docker
Start this project using Docker 

Here are all services integrated in one project as docker service
It's possible to use local and on server by few tools to deploy:

+ dokku
+ heroku
+ Now


## Deployment


<a href="https://www.heroku.com/deploy/?template=https://github.com/DevOpsTerminal/backend"><img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku" height="25px"></a>

<a href="https://deploy.now.sh/?repo=https://github.com/DevOpsTerminal/backend"><img src="https://deploy.now.sh/static/button.svg" alt="Deploy to Now" height="25px"></a>

Don't forget to set the environment variable `NODE_ENV=production` to avoid the slower, dev version of React. Like so:

```sh
npx now -e NODE_ENV=production DevOpsTerminal/backend
```

