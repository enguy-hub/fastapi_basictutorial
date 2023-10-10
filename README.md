# Basic Tutorial for [FastAPI on RealPython](https://realpython.com/fastapi-python-web-apis/)

URL to the tutorial: https://realpython.com/fastapi-python-web-apis/

## Try It Out

### 1. Clone the repo

- HTTP:

      git clone https://github.com/enguy-hub/fastapi_basictutorial.git

- SSH

      git clone ssh://git@github.com:enguy-hub/fastapi_basictutorial.git

### 2. Create and activate Python environment (conda or venv)

- For `CONDA`

  - Create the environment with:

        conda env create --file env.yml

  - Activate the environment with:

        conda activate fastapienv

- For `VENV`

  - Create the environment with:

        python3 -m venv fastapienv

  - Activate the environment with:

        source fastapienv/bin/activate

  - Install the dependencies with:

        pip install -r requirement.txt

### 3. Spin up FastAPI

- For runnning the `First Steps` part in the [tutorial](https://realpython.com/fastapi-python-web-apis/#first-steps):

      uvicorn main_firststeps:app --reload

- For runnning the `Path Parameters: Get an Item by ID` part in the [tutorial](https://realpython.com/fastapi-python-web-apis/#path-parameters-get-an-item-by-id):

      uvicorn main_pathparams:app --reload

- For runnning the `Request Body: Receiving JSON Data` part in the [tutorial](https://realpython.com/fastapi-python-web-apis/#request-body-receiving-json-data):

      uvicorn main_request:app --reload