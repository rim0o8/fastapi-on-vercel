# FastAPI on Vercel

This project demonstrates how to deploy a FastAPI application on Vercel.

English | [日本語](README.ja.md)

## Features

- Build high-performance APIs with FastAPI framework
- Easy deployment on Vercel
- Automatic OpenAPI (Swagger) documentation generation

## Prerequisites

- Python 3.9 or higher
- Vercel account
- Vercel CLI (for local testing)

## Setup Instructions

1. Clone the repository

    ```bash
    git clone https://github.com/yourusername/fastapi-on-vercel.git
    cd fastapi-on-vercel
    ```

## Deploying to Vercel

1. Install Vercel CLI (optional)

    ```bash
    npm i -g vercel
    ```

2. Deploy to Vercel

    Using Vercel CLI:
    ```bash
    vercel login
    vercel
    ```

    Via GitHub repository:
    1. Push your repository to GitHub
    2. Import the repository in the Vercel dashboard
    3. Verify the deployment settings and click "Deploy"

## File Structure

- **app.py**: Entry point for the FastAPI application
- **requirements.txt**: Project dependencies (fastapi, uvicorn)
- **vercel.json**: Vercel configuration file (build settings and routes)
- **.vercelignore**: Files to exclude from deployment

## Reference

- [FastAPI Official Documentation](https://fastapi.tiangolo.com/)
- [Vercel Project Configuration](https://vercel.com/docs/project-configuration)
- [Vercel Python Runtime](https://vercel.com/docs/functions/serverless-functions/runtimes/python)
