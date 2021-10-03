<<<<<<< HEAD
FROM python:3.8
WORKDIR /app
COPY requirements.txt .
RUN python -m pip install -r requirements.txt
COPY . .
EXPOSE 5000
=======
FROM python:3.8
WORKDIR /app
COPY requirements.txt .
RUN python -m pip install -r requirements.txt
COPY . .
EXPOSE 5000
>>>>>>> d35f8410346250125e89bf6799e0573c0673e438
CMD ["gunicorn","--workers=1", "--bind", "0.0.0.0:5000","app:app"]