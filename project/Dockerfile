FROM python:3.8
EXPOSE 3111

WORKDIR /usr/src/app
COPY ./techtrends ./

RUN pip install --no-cache-dir -r requirements.txt
CMD [ "python", "app.py" ]
