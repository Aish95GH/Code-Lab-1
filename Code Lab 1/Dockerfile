FROM python:latest   

RUN apt-get update
RUN apt-get install wget
RUN wget "https://raw.githubusercontent.com/mschermann/forensic_accounting/master/fb_sub.csv"

RUN pip install regex

ADD main.py .
RUN python main.py

