FROM python:3.12
ADD . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD ["gunicorn", "-c", "config.py", "app:app"]
EXPOSE 8000
