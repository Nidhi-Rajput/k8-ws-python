FROM python:3.12

WORKDIR /app

COPY ./inventory_service/ /app/
COPY requirements.txt /app/

# pip intsall requiremnts will done by RUN command
RUN pip install -r requirements.txt

# CMD - command to run inside container
CMD ["python", "inventory_app.py"]