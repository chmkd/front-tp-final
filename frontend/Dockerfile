FROM python

WORKDIR /app


COPY . /app

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

ENV FLASK_APP=main.py

ENTRYPOINT [ "flask"]
CMD [ "run", "--host", "0.0.0.0", "--port", "5000" ]