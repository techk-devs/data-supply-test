FROM python:3.6.8
ENV PYTHONUNBUFFERED 1
RUN mkdir -p /home/projects/b2b-scrapers
RUN apt-get update
RUN apt-get -y install qt5-default libqt5webkit5-dev build-essential
RUN apt-get -y install python-lxml python-pip xvfb
RUN apt-get -y install tesseract-ocr
RUN apt-get -y install tesseract-ocr-spa
RUN apt-get -y install unrar-free
RUN apt-get -y install unar
RUN apt-get -y install vim
WORKDIR /futurama
COPY requirements.txt .
RUN pip install --upgrade pip
RUN pip install -r requirements.txt