FROM python:3.6

#RUN groupadd -r uwsgi && useradd -r -g uwsgi uwsgi
RUN pip install Flask
COPY . /app
WORKDIR /app
#EXPOSE 9090 9191
#USER uwsgi
ENTRYPOINT ["python"]
CMD ["app.py"]
#CMD ["/cmd.sh"]

