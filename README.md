# :lion: old-holden-diy

[![Build status](https://github.com/ocampco/old-holden-diy/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ocampco/old-holden-diy/actions/workflows/ci.yml)

Documentation site using [mkdocs](https://github.com/mkdocs/mkdocs), deployed to [Github Pages](https://ocampco.github.io/old-holden-diy/)

## :runner: Running

### Local

Ensure you have [python](https://www.python.org/) installed

```sh
# Install dependencies
$ pip install -r ./requirements.txt

# Run app
# Served at http://localhost:8000/old-holden-diy/
$ mkdocs serve
```

### Docker

Ensure you have [Docker](https://www.docker.com/) installed

```sh
# Build app
$ ./auto/build

# Run app
# Served at http://localhost:8000/old-holden-diy/
$ ./auto/run
```

## :ship: Manual Deployment

New commits on the `main` branch are automatically deployed using [Github Actions](https://github.com/ocampco/old-holden-diy/actions)

```sh
# Deploy using local
$ mkdocs gh-deploy

# Deploy using Docker
$ ./auto/deploy
```
