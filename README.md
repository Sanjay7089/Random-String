# Random String Generator 

## Description

This application consists of a Flask backend and a Nginx-served frontend, containerized and orchestrated using Kubernetes. It's designed to generate random string.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Local Setup](#local-setup)
- [Kubernetes Deployment](#kubernetes-deployment)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- Docker
- Kubernetes (Minikube for local development)
- kubectl
- Python 3.8+
- Node.js and npm (if your frontend uses them)

## Local Setup

### Backend

1. Navigate to the backend directory:
   ```sh
   cd backend
