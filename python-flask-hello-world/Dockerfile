FROM registry.access.redhat.com/ubi8/python-36
WORKDIR /python-flask-hello-world
COPY . .
RUN pip install -r requirements.txt
EXPOSE 8080
CMD ["python", "app.py"]