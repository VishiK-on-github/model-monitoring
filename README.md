# To get the repo working:

1. Make a python env: python -m venv env
2. Activate python env: env\Scripts\activate (Windows)
3. Install dependencies: pip install -r requirements.txt

# To build docker container:

docker-compose up

# To stop docker containers:

docker-compose down | stop

# To start mock data monitoring script

1. Start the containers using docker compose
2. Activate virtual environment in another terminal window
3. Run dummy_metrics_calculation.py file: python dummy_metrics_calculation.py
