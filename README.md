# My Cloud API (`manual_cloud_deployment`)

A lightweight, production-ready Flask REST API designed for manual cloud deployment and continuous integration workflows.

---

##  Features

* Home Endpoint (`/`)*: Returns a welcome message confirming the API is active.
* Health Check Endpoint (`/health`): Provides a system status check for monitoring and orchestration tools.
* Lightweight & Modular: Built with Python and Flask, structured for quick containerization or cloud server deployment.

---

##  Tech Stack

* Language: Python 3
* Framework: Flask
* Version Control: Git / GitHub

---

##  Local Development Setup

Follow these steps to set up and run the project locally on your machine.

### 1. Clone the Repository
```bash
git clone [https://github.com/AmanPandey-hub/manual_cloud_deployment.git](https://github.com/AmanPandey-hub/manual_cloud_deployment.git)
cd manual_cloud_deployment

### 2. Create and Activate a Virtual Environment
Bash
python3 -m venv venv
source venv/bin/activate

### 3. Install Dependencies
Bash
pip install flask

### 4. Run the Application
Bash
python3 app.py

## Testing the Endpoints
With the server running in a separate terminal window, you can verify the endpoints using curl:

Test Home Route:

Bash
curl [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
Expected Output:
<img width="707" height="56" al
t="image" src="https://github.com/user-attachments/assets/92efd8bf-92d1-4dc3-ba28-79da808d1576" />

Test Health Check Route:

Bash
curl http://127.0.0.1:5000/health
Expected Output:
<img width="575" height="56" alt="image" src="https://github.com/user-attachments/assets/bfa7b376-69f3-43e5-bce4-60021d17cb04" />


## Project structure

my-cloud-api/
│
├── venv/              # Python virtual environment (ignored by git)
├── app.py             # Main Flask application logic & routing
└── README.md          # Project documentation

## License
This project is open-source and available under the MIT License.
