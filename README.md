# golang-docker
Simple development environment for golang, made to have a dockerized way to create things.

## Setup

```bash
cp .env.dist .env

# add dcli alias into your OS terminal profile 
alias dcli='docker-compose -f docker-compose.cli.yml run --rm'
```

## How to run

```
dcli go run main.go
```

And that's all to start your project ;)
