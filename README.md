# py-crdt-collab-editor
CRDT based collaborative code/text editor.

## Requirements  
- flask 
- requests
- python3-crdt
  - The editor is dependent on the [python3-crdt](https://pypi.org/project/python3-crdt/) library which is available on pypi.org and can be installed using 
    ```python
    pip install python3-crdt
    ```
## Usage
1. Clone the project 
   ```
   git clone https://github.com/anshulahuja98/py-crdt-collab-editor
   ```
1. Install requirements
   ```
    pip install pipenv # Installs pipenv
    pipenv install     # Installs the requirements from pipfile
   ```
1. Run one server
   ```
    flask run -p 8000  # In one terminal
    # Open 127.0.0.1:8000 in browser window
   ```
1. Run another server
   ```
    flask run -p 8001  # In another terminal
    # Open 127.0.0.1:8001 in another browser window
   ```

> Experience the power of collaborative text editing.

