FROM python:3.9

WORKDIR src
COPY . .
RUN pip3 install --no-cache-dir --upgrade -r requirements.txt
EXPOSE 8765

CMD ["python3", "-u", "manage.py", "runserver", "0.0.0.0:8765"]
