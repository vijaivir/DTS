FROM python:3.9

WORKDIR /quoteserver

COPY . .

RUN pip install -r requirements.txt

EXPOSE 5001

CMD gunicorn --bind 0.0.0.0:5001 quoteserver:app