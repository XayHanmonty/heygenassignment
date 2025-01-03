# heygenassignment

# Heygen Video Translation Simulation

This project simulates a video translation server and a client library to interact with it. It demonstrates a simple GET API using Express.js, providing an example of a real-world scenario where intelligent polling is implemented to optimize API calls.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
   - [Prerequisites](#prerequisites)
   - [Steps to Install](#steps-to-install)
4. [Configuration](#configuration)
   - [Environment Variables](#environment-variables)
5. [Usage](#usage)
   - [Start the Server](#start-the-server)
   - [API Endpoints](#api-endpoints)
6. [Testing](#testing)
7. [Project Structure](#project-structure)
8. [Scripts](#scripts)
9. [Example Logs](#example-logs)
10. [Future Enhancements](#future-enhancements)
11. [Contributors](#contributors)
12. [License](#license)

---

## Introduction

The **Heygen Video Translation Simulation** project is designed as a demonstration tool for video translation processes. It includes:

- A backend server that simulates translation delays and responses.
- A client library to interact with the backend intelligently, employing exponential backoff to optimize polling frequency.
- Integration tests showcasing the end-to-end workflow.

This project is suitable for learning about API interactions, polling mechanisms, and backend simulation.

---

## Features

- **Simulated Video Translation Backend**: A mock server to emulate translation status.
- **Intelligent Polling**: Client library implements exponential backoff for efficient API calls.
- **Customizable Translation Delay**: Configurable via environment variables.
- **Integration Testing**: Demonstrates client-server interaction and polling in action.

---

## Installation

### Prerequisites

Ensure the following are installed on your system:

- **Node.js** v14 or later
- **npm** v6 or later

### Steps to Install

1. Clone the repository:

    ```bash
    git clone <repository-url>
    cd heygenassignmentv1
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

---

## Configuration

### Environment Variables

Create a `.env` file in the root directory to customize the server configuration. Below is an example `.env` file:

```env
TRANSLATION_DELAY=10000  # Simulated delay for video translation (in milliseconds)
PORT=3000                # Server port
