FROM alpine
RUN apk add --no-cache --upgrade bash
RUN mkdir /opt/app2
COPY hello.sh /opt/app2/hello.sh
RUN chmod 777 /opt/app2/hello.sh
CMD ["/opt/app2/hello.sh"]
