FROM python:3
#RUN apk --update add bash nano
#ENV STATIC_URL /static
#ENV STATIC_PATH /var/www/app/static
COPY ./requirements.txt /var/www/requirements.txt
RUN pip install -r /var/www/requirements.txt
CMD ["python3","mongoSearch.py"]