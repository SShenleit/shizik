FROM python:3.10.6-alpine2.25
WORKDIR /app
COPY requirements.txt /app
COPY main.py /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "main.py" ]
