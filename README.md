# fastapi-jwt-authentication

This includes pyhton code for authenticating users on a login page using the ```JWT``` token using FastAPI framework along with hashed password protection using ```bcrypt```.

Go to your projects folder and setup a virtual environment
```
cd "your-project-folder-path"

python3 -m venv venv
source venv/bin/activate
```

Before executing the code be sure to have the following packages installed inside your project folder:

```
pip install fastapi
pip install uvicorn[standard]
pip install python-multipart
pip install python-jose
pip install passlib
```

Run the code
```
uvicorn main:app --reload
```

The APIs can be tested in ```localhost:3000/docs```
