### MoscowTimeWebApplication

#### Overview

This web application shows the current time in Moscow. The application is built using Flask, a popular web framework in Python.

When the user accesses the main page of the application, it retrieves the current time in Moscow and displays it on a webpage. The time is formatted as "YYYY-MM-DD HH:MM:SS". The application uses the Flask's built-in development server and listens port 8080.

#### Prepare

In order to prepare project to run, it is necessary to install dependencies:

```bash
pip3 install -r requirements.txt
```

#### Usage (Docker)

The application can be easily runned in docker.
First, pull the image:
```bash
docker pull elatypovinno/devops_inno
```

Then it is possible to start container, it will build and run everything automatically:
```bash
docker run -it -p 8080:8080 --name time-app elatypovinno/devops_inno:latest 
```

To build the container was used the following command:
```bash
docker build -t elatypovinno/devops_inno:latest .
```

#### Contact

Emil Latypov, e.latypov@innopolis.university