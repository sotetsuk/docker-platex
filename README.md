# docker-platex

Forked from [thii/docker-platex](https://github.com/thii/docker-platex).

## Change history
- 2015.06.08: ```texlive``` => ```texlive-science```

A docker container for pLaTeX, which can be used to build Japanese pLaTeX file.

## Setup

Pull image ([from Docker Hub](https://registry.hub.docker.com/u/thii/platex)):

```bash
docker pull thii/platex
```

or build it yourself:

```bash
docker build -t thii/platex .

```

Usage
-----

```bash
docker run --rm -v `pwd`:/latex thii/platex build example.tex
```

## License

MIT
