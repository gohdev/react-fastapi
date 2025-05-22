# react-fastapi

## How to Create a FastAPI & React Project - Python Backend + React Frontend

**YouTube**: https://www.youtube.com/watch?v=aSdVU9-SxH4

**GitHub**: https://github.com/techwithtim/FastAPI-React-Integration

**Local setup**:
- Install PyCharm
- Create new project using FastAPI

## Python Backend

### requirements.txt
```shell
cd backend
pip3 install -r requirements.txt
```
### unvicorn
- A webserver to run FastAPI app

### Advantages of FastAPI
- It can automatically validate data coming in and it can format data going out based on Pydantic models.

### CORS
Cross-Origin Resource Sharing (CORS) prohibits unauthorized websites, endpoints, or servers from accessing your API.

### API testing

1. PyCharm HTTP Client
2. Swagger http://localhost:8000/docs

## React Frontend

http://localhost:5173

```shell
 npm create vite@latest frontend --template react
 
 cd frontend
 npm install
 npm install axios
```
