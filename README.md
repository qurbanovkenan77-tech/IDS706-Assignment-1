# IDS706-Assignment-1
[![Python tests](https://github.com/qurbanovkenan77-tech/IDS706-Assignment-1/actions/workflows/test.yml/badge.svg)](https://github.com/qurbanovkenan77-tech/IDS706-Assignment-1/actions/workflows/test.yml)

# Data Engineering Python Project

This project is a simple Python application created for the Data Engineering course. It asks the user to enter their name and then displays a personalized welcome message.

## Setup

Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

Install the required dependencies:

```bash
python -m pip install -r requirements.txt
```

## Run the Application

Run the program with:

```bash
python src/main.py
```

Enter your name when prompted.

## Run Tests

Run the tests using:

```bash
python -m pytest
```

Or use the Makefile:

```bash
make test
```

## Docker

Build the Docker image:

```bash
make docker-build
```

Run the application in Docker:

```bash
make docker-run
```

Run the tests inside Docker:

```bash
make docker-test
```

## Example

```text
Enter your name: Kanan
Kanan, welcome to the Data Engineering course.
```

The project also uses GitHub Actions to automatically run the tests and verify the Docker build whenever changes are pushed to the repository.

