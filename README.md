# Fetch-Rewards-ML-Apprenticeship-Take-Home

# Installation Guide

## Prerequisites

- Python 3.9 or higher
- Conda

## Steps

1. **Clone the Repository**:

```bash
git clone https://github.com/Robertluo12138/Fetch-Rewards-ML-Apprenticeship-Take-Home.git
cd Fetch-Rewards-ML-Apprenticeship-Take-Home
```
2. **Create a Conda Environment**:

```bash
conda create -n multitask-transformer python=3.9
conda activate multitask-transformer
```

3. **Install Required Packages**:
```bash
pip install -r requirements.txt
```

# Docker

## Prerequisites

Make sure Docker installed on your machine.

You can download and install Docker from [here](https://www.docker.com/products/docker-desktop).

## Setup and Run with Docker

### Step 1: Clone the repository

Clone this repository to your local machine using the following command:

```sh
git clone https://github.com/Robertluo12138/Fetch-Rewards-ML-Apprenticeship-Take-Home.git
cd Fetch-Rewards-ML-Apprenticeship-Take-Home
```


### Step 2: Build the Docker image

In the project directory, build the Docker image using the following command:

```
docker build -t fetch_rewards_apprenticeship .
```


### Step 3: Run the Docker container

Run the Docker container with the following command:

```
docker run -p 8888:8888 fetch_rewards_apprenticeship
```


### Step 4: Access Jupyter Notebook

Once the container is running, you can access the Jupyter notebook by navigating to [http://localhost:8888]() in your web browser. Use the token provided in the terminal to log in.
