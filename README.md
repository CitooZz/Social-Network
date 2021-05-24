# Social-Network

How to run:

-   Put environment settings on file .django
-   docker-compose -f local.yaml up --build

Try API endpoints: localhost:8002/api/swagger/

Run test case:

-   create virtualenv
-   activate virtualenv
-   cd social_network
-   pip install -r tests/requirements.txt
-   export PYTHONPATH=/:tests/
-   python -m pytest --ds=component.test_settings tests/component
-   python -m pytest --ds=unit.test_settings tests/unit
