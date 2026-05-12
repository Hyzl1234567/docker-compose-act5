# Activity 5: Docker Compose Configuration

## Overview

Run a **multi-container application** inside Docker using **Docker Compose**, and make sure the services can communicate properly. You should be able to access your application in your browser.

---

## Requirements

You must:

- Create your own `Dockerfile` and `docker-compose.yml`
- Include at least **three services**:
    - Web application
    - Database
    - phpMyAdmin
- Use **official Docker images** for your services
- Configure **ports** and **environment variables**
- Make the app accessible at: http://localhost:<your-port>

---

## Required Docker Naming Convention

- **Service names**:
    - `platform_docker-app`
    - `platform_docker-db`
    - `platform_docker-phpmyadmin`
- **Container names**:
    - `<your-name>-app`
    - `<your-name>-db`
    - `<your-name>-phpmyadmin`

---

## Rules

- Do **NOT** copy a full solution from classmates or the internet
- You may read documentation and guides
- You must understand and be able to **explain your work**

---

## Expected Output

When everything is working:

- You can open a browser and go to your configured port
- All services defined in `docker-compose.yml` are running correctly
- The app can communicate with the database (if applicable)

---

## What to Submit

1. **Screen Recording / Demo Video**
    - Start and run **all containers** (database, application, and phpMyAdmin)
    - Access the web app in the browser
    - Show phpMyAdmin in the browser
    - Create **one (1) product** in the app
    - Explain what is inside your `docker-compose.yml` and `Dockerfile`  
      (services, ports, environment variables, volumes, etc.)

2. **GitHub Repository Link**
    - Include all project files: `docker-compose.yml`, `Dockerfile(s)`, application code, and optional `.env` with placeholders

## TAKE NOTES

    -Do **not** include sensitive information in your submission
    -If your setup requires environment variables, provide an example `.env` file with placeholders only:

## Rubrics

| Category                                   | Points |
| ------------------------------------------ | ------ |
| docker-compose.yml & Dockerfile            | 20     |
| Running containers correctly               | 10     |
| Web app and database functionality         | 10     |
| Naming conventions (services & containers) | 5      |
| Explanation / Understanding                | 15     |
| **Total**                                  | **60** |
# docker-compose-act5
