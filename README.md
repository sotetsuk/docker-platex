# docker-platex

Forked from [thii/docker-platex](https://github.com/thii/docker-platex).

## Change history
- 2016.06.08: ```texlive``` => ```texlive-science```
- 2016.09.16: add ```sudo apt-get install curl jq```

A docker container for pLaTeX, which can be used to build Japanese pLaTeX file.

## Setup

Pull image ([from Docker Hub](https://hub.docker.com/r/sotetsuk/platex/)):

```bash
docker pull sotetsuk/platex
```

or build it yourself:

```bash
docker build -t sotetsuk/platex .

```

Usage
-----

```bash
docker run --rm -v `pwd`:/latex sotetsuk/platex build example.tex
```

## License

MIT
