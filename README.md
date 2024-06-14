# GTP-3-API-Codex-App

## Overview

This repository contains the source code for a web application that utilizes the OpenAI GPT-3 Codex API to provide code generation and completion functionalities. The project is divided into two main parts: the client and the server.

## Features

- **Code Generation:** Generate code snippets based on natural language descriptions.
- **Code Completion:** Provide suggestions and auto-completions for code based on the current context.

## Project Structure

- **client:** Contains the frontend code built with React.
- **server:** Contains the backend code using Node.js and Express.

## Getting Started

### Prerequisites

- Node.js
- npm or yarn
- OpenAI API Key

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/KrlosDev/GTP-3-API-Codex-App.git
    cd GTP-3-API-Codex-App
    ```

2. Install dependencies for both client and server:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. Set up environment variables:
    Create a `.env` file in the server directory and add your OpenAI API key:
    ```env
    OPENAI_API_KEY=your_openai_api_key
    ```

### Running the Application

1. Start the server:
    ```bash
    cd server
    npm start
    ```

2. Start the client:
    ```bash
    cd client
    npm run dev
    ```

## Usage

1. Enter a natural language description of the code you want to generate.
2. Click the "Generate Code" button to receive the generated code snippet.
3. Use the code completion feature by typing your code and observing the suggestions provided.

## Contributing

Contributions are welcome! Please create an issue or submit a pull request for any enhancements or bug fixes.

