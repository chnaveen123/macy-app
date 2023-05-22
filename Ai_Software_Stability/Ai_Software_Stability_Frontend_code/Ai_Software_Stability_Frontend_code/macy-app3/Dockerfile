FROM python:3.12-rc-alpine3.17

WORKDIR . /Ai_software_stability_Frontend_code

COPY . /api

COPY requirements.txt .

RUN pip install -r requirements.txt

CMD ["python","api.py"]
