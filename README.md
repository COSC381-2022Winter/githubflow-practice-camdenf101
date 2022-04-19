# Movies Website COSC 381 
## Steps for starting website (developement mode)
steps:
1. Create a virtual environment in root directory: `python3 -m venv venv`
2. Activate virtual environment: `source venv/bin/activate`
3. Install the dependencies: `python3 -m pip install -r requirements.txt`
4. Set up the environment variables for the flask app: `source env-var.sh`
5. Initialize database: `flask init-db`
6. Start website: `flask run`
7. The webpage address is: http://127.0.0.1:5000/movies/