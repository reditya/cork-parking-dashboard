FROM influxdb:1.2.4-alpine

WORKDIR /app
COPY entrypoint.sh ./
RUN chmod u+x entrypoint.sh

ENTRYPOINT ["/app/entrypoint.sh"]
