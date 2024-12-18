# Backend Application

This backend application is built using [Quart](https://quart.palletsprojects.com/), a Python framework for asynchronous web applications. It powers the backend of the RAG chat app, handling API requests, data processing, and communication with external services.

## Table of Contents

- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Environment Variables](#environment-variables)
- [API Endpoints](#api-endpoints)
- [Running the Application](#running-the-application)
- [Testing](#testing)

## Getting Started

To get started with the backend application, ensure you have Python 3.8 or higher installed. Follow the steps below to set up the development environment.

### Prerequisites

- Python 3.8+
- pip (Python package installer)
- virtualenv (optional but recommended)

### Installation

1. Clone the repository:

    ```sh
    git clone <repository-url>
    cd <repository-directory>/app/backend
    ```

2. Create and activate a virtual environment:

    ```sh
    python3 -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

## Project Structure

The backend application has the following structure:
