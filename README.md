# docker-stacks

[![Join the chat at https://gitter.im/jupyter/jupyter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jupyter/jupyter?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Opinionated stacks of ready-to-run Jupyter applications in Docker.

## Quick Start

If you're familiar with Docker, have it configured, and know exactly what you'd like to run, this one-liner should work in most cases:

```
docker run -d -P jupyter/<your desired stack>
```

## Getting Started

If this is your first time using Docker or any of the Jupyter projects, do the following to get started.

1. [Install Docker](https://docs.docker.com/installation/) on your host of choice.
2. Click the link for the Docker Hub repo or GitHub source for your desired stack.
3. Follow the README for that stack.

## Available Stacks

Branches / tags reflect the version of the primary process in each container (e.g., notebook server). Currently, GitHub master / Docker latest for Jupyter Notebook containers are equivalent to 4.0.x / 4.0

| Docker Hub repo | GitHub source | Git Branch &rarr; Docker Tag |
| --------------- | ------------- | ---------------------------- |
| [jupyter/minimal-notebook](https://hub.docker.com/r/jupyter/minimal-notebook/) | [minimal-notebook](./minimal-notebook) | master &rarr; latest <br /> 4.0.x &rarr; 4.0 <br /> 3.2.x &rarr; 3.2 |
| [jupyter/scipy-notebook](https://hub.docker.com/r/jupyter/scipy-notebook/) | [scipy-notebook](./scipy-notebook) | master &rarr; latest <br /> 4.0.x &rarr; 4.0 <br /> 3.2.x &rarr; 3.2 |
| [jupyter/r-notebook](https://hub.docker.com/r/jupyter/r-notebook/) | [r-notebook](./r-notebook) | master &rarr; latest <br /> 4.0.x &rarr; 4.0 <br /> 3.2.x &rarr; 3.2 |
| [jupyter/datascience-notebook](https://hub.docker.com/r/jupyter/datascience-notebook/) | [datascience-notebook](./datascience-notebook) | master &rarr; latest <br /> 4.0.x &rarr; 4.0 |
| [jupyter/all-spark-notebook](https://hub.docker.com/r/jupyter/all-spark-notebook/) | [all-spark-notebook](./all-spark-notebook) | master &rarr; latest <br /> 4.0.x &rarr; 4.0 <br /> 3.2.x &rarr; 3.2 |
| [jupyter/pyspark-notebook](https://hub.docker.com/r/jupyter/pyspark-notebook/) | [pyspark-notebook](./pyspark-notebook) | master &rarr; latest <br /> 4.0.x &rarr; 4.0 <br /> 3.2.x &rarr; 3.2 |
