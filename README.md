# FastAPI Simple Sample Project

This is a simple sample project to demonstrate how to use FastAPI and in general some good practices for creating projects.

## Setup Instructions

1. Clone the repository

```bash
git clone https://github.com/eduard-balamatiuc/sample-project.git
```

2. Navigate to the project directory

```bash
cd sample-project
```

3. Create a virtual environemnt

```bash
python3 -m venv venv
```

4. Activate the virtual environment

```bash
source venv/bin/activate
```

5. Install the dependencies

```bash
pip install -r requirements.txt
```

6. Run the application

```bash
uvicorn app.main:app --reload
```

7. Navigate to the following URL in your browser and check the documentation and interact with the API

```
http://127.0.0.1:8000/docs
```

8. Additionally, you can run the tox check with the following command

```bash
tox
```