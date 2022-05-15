FROM python:3.9

WORKDIR /RTA

COPY requirements.txt .

COPY RTA_model.pkl .

COPY model.py .

COPY app1.py .

RUN pip install -r requirements.txt

CMD ["python", "./app1.py"]
