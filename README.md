# NurseMate: Your Personal Nursing Assistant

Welcome to **NURSEMATE**, a custom nursing assistant application built using OpenAI's Assistants API. This project leverages the power of AI to provide basic customer support and assistance for nursing-related queries.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
  

## Introduction

**NURSEMATE** is a project-based application designed to create a personalized assistant for nursing professionals and students. It aims to provide quick, accurate responses to common nursing questions and support needs. This project is built with Nuxt for server-side rendering and incorporates TypeScript for type safety.

## Features

- AI-powered responses to nursing-related queries.
- Remembers past conversations for better context.
- Clean and polished user interface.
- Easy integration with other healthcare tools and services.

## Tech Stack

- **OpenAI Assistants API**: For AI-powered responses.
- **Nuxt**: For server-side rendering and seamless communication.
- **TypeScript**: For enhanced type safety and development experience.

## Installation

### Prerequisites

- Node.js (version 14 or higher)
- npm (version 6 or higher)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/carebot.git
   cd carebot
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file and add your OpenAI API key:

   ```bash
   OPENAI_API_KEY=your_openai_api_key
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`.

## Usage

Once the development server is running, you can start interacting with **NURSEMATE** through the web interface. Type your nursing-related questions, and the bot will provide responses based on the AI model trained with OpenAI's Assistants API.

## Customization

You can customize the bot's personality and responses by modifying the OpenAI API settings in the `api` folder. Adjust the prompts and parameters to tailor the assistant's behavior to your specific needs.

## Contributing

We welcome contributions to enhance NURSEMATE. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.

Feel free to reach out with any questions or feedback. Happy coding!
