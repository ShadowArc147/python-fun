# Dockerfile, Image, Container
# Dockerfile = blueprint
# Image = template for running containers
# Container =  process for running project

FROM python:3.8

ADD main.py . 

RUN pip install requests beautifulsoup4

CMD [ "python", "./main.py" ]

