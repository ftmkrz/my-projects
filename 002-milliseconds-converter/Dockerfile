FROM python:alpine 
COPY . /app
WORKDIR /app
RUN pip3 install -r requirements.txt
CMD python app.py
EXPOSE 80 