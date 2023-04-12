# Dockerfile for building a custom cvc5

To allow custom builds that are reproducible, trackable, and easier to review

## How to build

```
DOCKER_BUILDKIT=1 docker build -f Dockerfile-cvc5 --rm -t certora/smtenv:current .
```

