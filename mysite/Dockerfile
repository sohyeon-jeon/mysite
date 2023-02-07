FROM python:3.8.10
ENV PYTHONUNBUFFERED 1 

RUN mkdir /srv/mysite 
ADD . /srv/mysite 

WORKDIR /srv/mysite 

RUN pip install --upgrade pip 
RUN pip install -r requirements.txt 

# EXPOSE 8000
# CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]