# PDF Unlocker Web App

This PDF Unlocker is a web application that allows users to upload password-protected PDF files, enter the password, and download the unlocked PDF. It's built with Flask for the backend and basic HTML/CSS for the frontend, and it's designed to be run in a Docker container.

## Features

- Upload password-protected PDF files.
- Input the PDF file's password to unlock it.
- Download the unlocked PDF file.

## Prerequisites

- Docker Desktop
- WSL (For Windows Users)

## Local Setup

1. **Clone the Repository**

    ```bash
   git clone https://your-repository-url.git
   cd your-project-directory
    ```
2. **Build the Docker Image**

Navigate to the project directory where the Dockerfile is located and run:

   ```bash
   docker build -t pdf-unlocker-app .
   ```

