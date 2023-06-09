FROM python:3.10.6alpine
WORKDIR /app
COPY requirements.txt /app
COPY main.py /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "main.py" ]
