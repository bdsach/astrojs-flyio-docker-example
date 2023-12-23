# AstroJS Deployment on Fly.io with Docker Example

This repository provides an example of deploying an AstroJS application to [Fly.io](https://fly.io/), a platform for globally distributed applications, using Docker.

## Introduction

[Astro](https://astro.build/) is a modern front-end framework for building faster websites with less client-side JavaScript. This example demonstrates how to deploy an AstroJS application to Fly.io for global distribution using Docker.

## Prerequisites

Before you begin, ensure you have the following prerequisites:

- [Node.js](https://nodejs.org/) installed
- [Docker](https://www.docker.com/) installed
- [Flyctl](https://fly.io/docs/hands-on/install-flyctl/) installed
- [Fly.io](https://fly.io/) account

## Getting Started

1. 🧲 Clone this repository:

```bash
git clone https://github.com/your-username/astrojs-fly-docker-example.git
cd astrojs-fly-docker-example
```

2. 🐳 Build the Docker image:

```bash
docker build -t astrojs-fly-app .
```

3. 🚀 Prepare to deploy:

```bash
fly launch
```

4. ⚙️ Configure the Fly.io deployment settings in fly.toml:

5. 🚀 Deploy to Fly.io:

```bash
fly deploy
```