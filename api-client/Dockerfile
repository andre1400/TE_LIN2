FROM python
COPY socket_client.py .
RUN pip install -r requests flask
EXPOSE 5000
ENTRYPOINT ["python", "socket_server.py"]
