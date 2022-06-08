FROM python
COPY requirements.txt /app/requirements.txt
RUN pip install -r /app/requirements.txt
WORKDIR /app
COPY . .
EXPOSE 80
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=80"]