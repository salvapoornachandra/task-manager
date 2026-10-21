# Task Manager Web Application

A simple task management web application built using Python and Flask.

## Features
- Add and manage tasks
- Web interface using HTML templates
- Python application backend
- Docker support for containerization

## Technologies Used
- Python
- Flask
- HTML
- Docker
- Git and GitHub
- Linux

## Project Structure
```text
task-manager/
├── app.py
├── requirements.txt
├── Dockerfile
├── README.md
└── templates/
    └── index.html
```

## Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/salvapoornachandra/task-manager.git
   cd task-manager
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Start the application:
   ```bash
   python3 app.py
   ```

4. Open the local URL shown in your terminal, commonly `http://127.0.0.1:5000`.

## Docker

Build the Docker image:
```bash
docker build -t task-manager .
```

Run the container:
```bash
docker run -p 5000:5000 task-manager
```

## Author
Salva Poorna Chandra

GitHub: https://github.com/salvapoornachandra
## Application Output

![Task Manager Output](screenshots/task-manager-output.png)
