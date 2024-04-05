# :lion: old-holden-diy

- Documentation site using [mkdocs](https://github.com/mkdocs/mkdocs)
- Deployed with [Github Pages](https://ocampco.github.io/old-holden-diy/)

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

## :ship: Deployment

```sh
# Deploy using local
$ mkdocs gh-deploy

# Deploy using Docker
$ ./auto/deploy
```
