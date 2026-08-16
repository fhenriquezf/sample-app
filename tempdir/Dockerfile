FROM python:3.8
RUN pip install --progress-bar off flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  sample_app.py /home/myapp/
EXPOSE 8888
CMD python /home/myapp/sample_app.py
