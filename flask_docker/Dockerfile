FROM continuumio/anaconda3:5.3.0

COPY . /usr/ML/app
# EXPOSE 80
WORKDIR /usr/ML/app

COPY './requirements.txt' .

RUN pip install --upgrade pip
RUN pip install wrapt --upgrade --ignore-installed
RUN pip install -r requirements.txt
RUN pip install opencv-contrib-python-headless
RUN pip install --upgrade matplotlib

COPY . .

# ENTRYPOINT ["python", "flask_api.py"]
CMD python flask_api.py
