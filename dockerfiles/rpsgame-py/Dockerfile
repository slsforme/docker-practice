FROM python:3.13.0

RUN python -m venv /opt/venv 

RUN . /opt/venv/bin/activate

WORKDIR /app

COPY . /app/

CMD . /opt/venv/bin/activate && exec python RockPaperScissorsGame.py



