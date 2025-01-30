#  Dockerized Flask App  

##  Project Overview  
This project demonstrates how to **containerize a Flask application** using Docker.  
It allows for easy deployment and ensures that the app runs consistently across different environments.  

##  Features  
-Lightweight Flask application  
-Dockerized for portability  
-Simple setup with minimal dependencies  
-Easily extendable for production use  

---

##  Tech Stack  
- **Backend:** Python, Flask  
- **Containerization:** Docker  

---

##  Getting Started  

###  1. Clone the Repository  
 ```bash
git clone https://github.com/yourusername/dockerized-flask-app.git
cd dockerized-flask-app
 ```bash
###  2. Build the Docker Image
```bash
docker build -t flask-app .
```bash
###  3. Run the Docker Container
```bash
docker run -p 5000:5000 flask-app
```bash
Now, open http://localhost:5000 in your browser.

## License
This project is open-source and free to use under the MIT License.
