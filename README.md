# tanmaya_DPDzero_project

## 📁 Project Structure

.
├── docker-compose.yml
├── nginx
│ ├── nginx.conf
│ └── Dockerfile
├── service_1
│ ├── main.go
│ └── Dockerfile
├── service_2
│ ├── app.py
│ ├── requirements.txt
│ └── Dockerfile
└── README.md

Access the Services:-
----------------------------
Open your browser and visit:

http://<Public-IP>:8080/service1/ → Go App

http://<Public-IP>:8080/service2/ → Python App

You can also test extra endpoints:

http://<Public-IP>:8080/service2/ping

http://<Public-IP>:8080/service2/hello


Tech Stack Used:-
----------------------
Docker

Docker Compose

Go (service1)

Python Flask (service2)

Nginx





